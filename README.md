# semana7

Aplicación para el pago de impuestos vehicular

Los propietarios de vehículos motorizados requieren conocer el valor de la liquidación
de los impuestos anualmente, antes de realizar el pago. Así mismo, las empresas
autorizadas para recaudar dicho impuesto deben saber cuáles son los valores de pago
para poder atender a los usuarios.
Para realizar el cálculo del valor a pagar por impuesto debe tenerse en cuenta el valor
comercial del vehículo el cual depende de la Marca (ej: Ford), la línea (ej: Ford Taurus)
y el modelo (año: 2018); y los descuentos a que puede aplicar de acuerdo con:
- Descuento por pronto pago, que consiste en un porcentaje determinado del
valor comercial del vehículo.
- Descuento por ser de servicio público, el cual es un valor fijo para este tipo de
servicio.
- Descuento por traslado de cuenta, que también es un porcentaje.

En el proceso de liquidación se debe contemplar:

- Realizar búsqueda por Marca, búsqueda por línea y el año para que la
aplicación muestre el valor comercial.
- El porcentaje de descuento por traslado de cuenta debe ser mayor que el
porcentaje de descuento por pronto pago.
- Los descuentos se aplican utilizando el último valor calculado. Por ejemplo, si
en un caso determinado se presenta una liquidación que aplica todos los
descuentos, primero se descuenta el porcentaje por pronto pago, luego a este
valor se le aplica el descuento de servicio público y luego al resultado se le
aplica el descuento por traslado (uso de cheklist por si se aplican todos los
conceptos)
- Una vez se tenga la información, calcular el pago del impuesto dando también
los valores por el o los descuentos a que tenga lugar.
