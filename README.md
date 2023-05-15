
# Ventas de Tienda de Cascos de Moto
Este programa permite registrar las ventas de una tienda de cascos de moto y mostrar el total de ventas para cada vendedor y tipo de casco.

## Requisitos
Java Development Kit (JDK) 8 o superior.
Un IDE o editor de texto para Java, como Eclipse, IntelliJ IDEA o Visual Studio Code.
Consola o terminal para ejecutar el programa.

## Instrucciones

1. Clonar o descargar el repositorio del programa.
2. Abrir el proyecto en el IDE o editor de texto.
3. Ejecutar el archivo VentasTiendaCascos.java.
4. Ingresar el tipo de casco, número del vendedor y monto de la venta.
5. Presionar la tecla "s" o "S" para continuar ingresando ventas, o cualquier otra tecla para terminar.
6. El programa mostrará el total de ventas para cada vendedor y tipo de casco.

## Cómo funciona
El programa utiliza programación orientada a objetos para representar las ventas y la tienda de cascos.

La clase Venta representa una venta individual con su tipo de casco, número de vendedor y monto.

La clase TiendaCascos representa el conjunto de ventas de la tienda. Se encarga de almacenar las ventas en una matriz, calcular el total de ventas para cada vendedor y tipo de casco, y mostrar los resultados.

En el archivo VentasTiendaCascos.java, se crea una instancia de la clase TiendaCascos, se ingresan las ventas a través de su método agregarVenta() y se muestran los resultados con su método imprimirVentas().

## Limitaciones
El programa está diseñado para registrar ventas de hasta 5 tipos de cascos y 5 vendedores.
No se realizan validaciones de los datos ingresados por el usuario.
El programa no guarda las ventas registradas en una base de datos o archivo.

## Contribuciones
Si deseas contribuir al desarrollo de este programa, puedes hacerlo a través de pull requests o abriendo issues en el repositorio. Cualquier aporte será bienvenido.