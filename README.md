# 📊 Análisis de Ventas - Alura Store Latam

Este proyecto analiza las ventas de cuatro tiendas ficticias de **Alura Store Latam**, utilizando datos públicos y herramientas de análisis en Python. El objetivo es explorar, procesar y visualizar la información para poder tomar la decision de que tienda es mejor cerrar para invertir en otro negocio.

## 📂 Datos utilizados
Los datos provienen de archivos CSV disponibles en GitHub:

- **[tienda_1.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_1%20.csv)**
- **[tienda_2.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_2.csv)**
- **[tienda_3.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_3.csv)**
- **[tienda_4.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_4.csv)**

Cada archivo contiene:
- **Producto**: nombre del artículo vendido.
- **Categoría del Producto**: clasificación del producto.
- **Precio**: valor de la venta.
- **Costo de envio**: valor del envio.
- **Fecha de compra**: momento en el que se registró la venta.
- **Lugar de compra**: lugar en donde se ejecuto la compra.
- **Calificacion**: la calificacion que le dio el usuario al producto.
- **Metodo de pago**: el metodo utilizado para comprar dicho producto.
- **Cantidad de cuotas**: en cuantos pagos se dividio el pago.
- **lat**: latitud en donde se registro la compra.
- **lon**: longitud en donde se registro la compra.

## 🛠 Tecnologías utilizadas
- **Python**  
- **Pandas** para la manipulación de datos  
- **Matplotlib** para la visualización gráfica   
- **Jupyter Notebook** para la ejecución y documentación del análisis
  
## 📋 Pasos del análisis

1. **Importación de datos**  
   Se cargan los archivos CSV directamente desde GitHub usando `pd.read_csv`.

2. **Análisis de facturación**  
   Se calcula la facturación total por tienda a partir de la suma de precios.

3. **Ventas por categoria**  
   Se agrupan los datos para conocer la cantidad de ventas por categoria y tienda.

4. **Calificacion promedio de la tienda**  
   Se calculas las calificaciones promedio de los productos por cada tienda y por cada tienda individial.

5. **Productos más y menos vendidos**  
   Se calcula cuales son los productos mas y menos vendidos de cada tienda y en general.

6. **Envio promedio por tienda**  
   Se calcula los gastos promedio de envio por cada tienda, asi como sus ingresos una ves restado los gastos de envio por tienda.

7. **Informe final**  
   Se concluye cual tienda deberia de cerrar y se explican las razones de esto
