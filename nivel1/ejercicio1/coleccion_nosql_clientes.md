Diseño de formato JSON NoSQL para MongoDB

{
    _id: "cliente_01",
    nombre: "Nombre de Cliente",
    direccion: "Direccion de Cliene nº 123",
    telefono: "333444555",
    email: "cliente@email.com",
    fecha_registro: Date("1999-12-31"),
    compras: [
        {
            id_compra: "compra_001",
            fecha_compra: Date("2023-09-23"),
            gafas: [
                {
                    id_gafa: "gafa_001",
                    tipo_modelo: "Rayban",
                    graduacion_izq: 2.3,
                    graduacion_der: 2.0,
                    color_cristal_izq: "",
                    color_cristal_der: "",
                    tipo_montura: "Metallic",
                    precio: 127.0
                }
            ]
        }
    ]
}