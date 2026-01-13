Diseño de formato JSON NoSQL para MongoDB

{
    _id: "gafa_001",
    marca: "Marca Gafa",
    tipo_montura: "Metallic",
    precio: 105.75,
    proveedor: {
        id_proveedor: "proveedor_001",
        nombre: "Googles Associated SL",
        direccion: ...,
    },
    suministros: [
        {
            fecha_suministro: Date("2023-09-01"),
            id_proveedor: "proveedor_001"
        },
        {
            fecha_suministro: Date ("2023-09-02"),
            id_proveedor: "proveedor_002",
        }
    ],
    compras: [
        {
            id_compra: "compra_001",
            fecha_compra: Date("2023-09-23"),
            cliente: {
                id_cliente: "clente_001",
                nombre: "Nombre Cliente",
            }
        },
        {
            id_compra: "compra_002",
            fecha_compra: Date("2023-09-24"),
            cliente: {
                id_cliente: "clente_002",
                nombre: "Nombre Cliente",
            }
        }
    ]
}