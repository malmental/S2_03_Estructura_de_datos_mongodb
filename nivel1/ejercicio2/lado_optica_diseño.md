Entidad Gafa:
    .- id_gafa PK
    .- marca
    .- tipo_montura
    .- precio

Entidad Proveedor:
    .- id_proveedor PK
    .- nombre
    .- direccion 
    .- (o algun otro dato de contacto)

Entidad Suministro
    .- id_suministro PK
    .- id_gafa
    .- id_proveedor FK
    .- fecha_suministro

Entidad Cliente
    .- id_cliente
    .- nombre
    .- ...otros datos

Entidad Compra
    .- id_compra PK
    .- id_gafa FK
    .- id_cliente FK
    .- fecha_compra

Relaciones entre las entidades:
Gafa N:M Proveedor --> A través de la entidad Suministro, 
                    Una gafa puedeser suministrada por arios proveedores.
                    Un proveedor puede suministrar varias gafas.
Gafa N:M Cliente --> A través de la entidad Compra, 
                    Una gafa puede ser comprada por varios clienes.
                    Un cliente puede comprar varias gafas.