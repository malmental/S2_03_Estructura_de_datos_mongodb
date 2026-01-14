┌───────────────────┐
│     Proveedor     │
├───────────────────┤
│ id_proveedor (PK) │
│ nombre            │
│ direccion         │
│... otros datos    │
└───────────────────┘
          │ 1
          │ N
┌───────────────────┐
│    Suministro     │
├───────────────────┤
│ id_suministro(PK) │
│ id_gafa (FK)      │
│ id_proveedor (FK) │
│ fecha_suministro  │
└───────────────────┘
          │ N
          │ 1
┌───────────────────┐
│       Gafa        │
├───────────────────┤
│ id_gafa (PK)      │
│ marca             │
│ tipo_montura      │
│ precio            │
└───────────────────┘
          │ N
          │ 1
┌───────────────────┐
│      Compra       │
├───────────────────┤
│ id_compra (PK)    │
│ id_gafa (FK)      │
│ id_cliente (FK)   │
│ fecha_compra      │
└───────────────────┘
          │ N
          │ 1
┌───────────────────┐
│     Cliente       │
├───────────────────┤
│ id_cliente (PK)   │
│ nombre            │
│ ...otros datos    │
└───────────────────┘