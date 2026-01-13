Entidad Gafa:
    .- id_gafa PK
    .- marca
    .- tipo_montura
    .- precio

Entidad Proveedor:
    .- id_proveedor PK
    .- nombre
    .- direccion (o algun otro dato de contacto)

Entidad Suministro
    .- id_suministro PK
    .- id_gafa
    .- id_proveedor FK
    .- fecha_suministro

Entidad Cliente
    .- id_cliente
    .- nombre
    .- ...datos

Entidad Compra
    .- id_compra PK
    .- id_gafa FK
    .- id_cliente FK
    .- fecha_compra

Relaciones entre las entidades:
Gafa N:M Proveedor --> a través de suministro, una gafa puedeser suministrada por arios proveedores y viceversa.
Gafa N:M Cliente --> a través de compra, una gafa puede ser comprada por varios clienes y viceversa.