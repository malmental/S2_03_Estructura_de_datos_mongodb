┌───────────────────┐
│     Cliente       │
├───────────────────┤
│ id_cliente (PK)   │
│ nombre            │
│ direccion         │
│ telefono          │
│ email             │
│ fecha_registro    │
└───────────────────┘
          │ 1
          │ N
┌───────────────────┐
│     Compra        │
├───────────────────┤
│ id_compra (PK)    │
│ id_cliente (FK)   │
│ fecha_compra      │
└───────────────────┘
          │ 1
          │ N
┌───────────────────┐
│       Gafa        │
├───────────────────┤
│ id_gafa (PK)      │
│ id_compra (FK)    │
│ tipo_modelo       │
│ graduacion_izq    │
│ graduacion_der    │
│ color_cristal_izq │
│ color_cristal_der │
│ tipo_montura      │
│ precio            │
└───────────────────┘