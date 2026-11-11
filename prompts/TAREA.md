# Tarea: Mi prompt profesional

## Funcionalidad elegida

## Version 1: prompt basico
Escribe un código para calcular el precio de un producto con descuento.
## Version 2
Escribe una función en JavaScript que reciba el precio de un producto y un porcentaje de descuento, y devuelva el precio final calculado.
## Version 3: prompt final
Actúa como un desarrollador web senior experto en JavaScript. 
Escribe una función pura que calcule el precio final de un artículo para un carrito de compras.
Contexto: La función debe recibir el precio original y el porcentaje de descuento. Primero aplica el descuento y, a ese resultado, aplícale un recargo del 18% por concepto de IGV (impuesto). Si el precio o el descuento son números negativos, retorna el string "Error: Valores inválidos".
Ejemplo: 
- Entrada: precio = 100, descuento = 20 -> Salida: 94.40
Restricción: No utilices librerías externas. El resultado debe ser un número redondeado exactamente a 2 decimales.
Formato: Devuelve únicamente el bloque de código JavaScript, sin saludos, sin texto de relleno ni explicaciones adicionales.
## Componentes del prompt final
## Componentes del prompt final

| Componente | Texto de mi prompt |
| :--- | :--- |
| **Rol** | "Actúa como un desarrollador web senior experto en JavaScript." |
| **Instruccion** | "Escribe una función pura que calcule el precio final de un artículo para un carrito de compras." |
| **Contexto** | "Primero aplica el descuento y, a ese resultado, aplícale un recargo del 18% por concepto de IGV... Si son negativos, retorna 'Error...'" |
| **Ejemplo** | "- Entrada: precio = 100, descuento = 20 -> Salida: 94.40" |
| **Formato** | "Devuelve únicamente el bloque de código JavaScript, sin saludos, sin texto de relleno ni explicaciones..." |
| **Restricción** | "No utilices librerías externas. El resultado debe ser un número redondeado exactamente a 2 decimales." |
## Evaluacion del resultado
## Evaluacion del resultado

| Criterio | Cumple (Sí / No) |
| :--- | :---: |
| Genera la función en JavaScript sin usar librerías | Sí |
| Aplica correctamente el orden: primero descuento, luego 18% de impuesto | Sí |
| Valida que no ingresen números negativos devolviendo el error pedido | Sí |
| Devuelve el resultado con exactamente 2 decimales | Sí |
| La respuesta solo contiene el bloque de código, sin texto extra | Sí |
## Errores que evite