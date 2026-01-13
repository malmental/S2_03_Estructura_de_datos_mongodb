Entidad Cliente:
    .- id_cliente PK
    .- nombre
    .- direccion
    .- telefono
    .- email
    .- fecha registro 

Entidad Compra:
    .- id_compra PK
    .- id_cliente FK
    .- fecha_compra

Entidad Gafas:
    .- id_gafa
    .- id_compra
    .- tipo
    .- graduacion_izq
    .- graduacion_der
    .- color_cristal_izq
    .- color_cristal_der
    .- tipo_montura
    .- precio

Relaciones entre las entidades: 
Cliente 1:N Compra --> puede tener multiples compras
Compra 1:N Gafa --> una compra puede tener varias gafas