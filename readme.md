# Información del dataset 'Lili_Pink_Improved.csv'

El dataset está en un archivo CSV, que contiene datos desde el mes de agosto de 2021, hasta las primeras semanas de octubre del año 2023. Lo datos son transacciónes en el e-commerce (VTEX) de la tienda virtual de LiliPink - YOI. La base de datos recuperada se compone de 42 columnas y 630.577 filas, una fila por cada producto vendido.

Las columnas son las siguientes:

## Información de la compra
0.  **Origin:** El origen de la compra.
1.  **Order:** Número de la orden de compra.
2.  **Sequence:** Secuencia de la orden de compra.
3.  **Creation Date:** Fecha de creación de la compra en el sistema.

## Información del cliente
4.  **Client Name:** Nombre del cliente.
5.  **Client Last Name:** Apellido del cliente.
6.  **Client Document:** Documento del cliente.
7.  **Email:** Dirección de correo electrónico del cliente.
8.  **Phone:** Número de teléfono del cliente

## Información del envío
9. **UF:** Departamento de la dirección de envío.
10. **City:** Ciudad a la que se envía.
11. **Address Identification:** ID de la dirección de envío.
12. **Receiver Name:** Nombre de la persona que recibe el pedido.
13. **Street:** Dirección de envío.
14. **Neighborhood:** Barrio de la dirección de envío.
15. **Postal Code:** Código postal de la dirección de envío.
16. **Estimate Delivery Date:** Fecha estimada de entrega.
17. **Delivery Deadline:** Días hábiles para la entrega.
18. **Status:** Estado del envío.


19. **Last Change Date:** Fecha de la última modificación de la orden de compra.

## Información de la campaña de marketing
20. **UtmMedium:** Medio de la campaña de marketing.
21. **UtmSource:** Fuente de la campaña de marketing.
22. **UtmCampaign:** Campaña de marketing.
23. **Coupon:** Cupón de descuento.

## Información de pago
24. **Payment System Name:** Nombre del sistema de pago.
25. **Installments:** Número de cuotas.

## Información del producto
26. **Quantity_SKU:** Cantidad de productos por SKU.
27. **ID_SKU:** SKU del producto.
28. **Category Ids Sku:** ID de la categoría del producto.
29. **Reference Code:** Código de referencia del producto.
30. **SKU Name:** Nombre del producto.
31. **SKU Value:** Valor del producto.
32. **SKU Selling Price:** Precio de vemta del producto.
33. **SKU Total Price:** Precio total del producto por cantidad.
34. **SKU Path:** Ruta del producto en el catálogo.
35. **Shipping Value:** Valor del envío.
36. **Total Value:** Valor total de la compra.
37. **Discounts Totals:** Descuento total de la compra.
38. **Discounts Names:** Nombre del descuento.
39. **Acquirer:** Adquirente.
40. **Cancellation Reason:** Razón de cancelación.
41. **marketingTags:** Etiquetas de marketing.

# ¿CÓMO USAR ESTE CÓDIGO?
El código está escrito en Python, y se necesita contar con la librería pandas instalada. Está escrito en un Jupyter Notebook, por lo que se puede ejecutar en Google Colab, VSCode o en cualquier otro entorno de desarrollo de Python.

No es necesario correr todos los bloques de código, lea bien la descripción de cada bloque, y a partir de ahí, ejecute el código que necesite.