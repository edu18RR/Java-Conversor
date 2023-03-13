# Challenge ONE-ORACLE NEXT EDUCATION
![Badge en Desarollo](https://img.shields.io/badge/Status-En%20Beta-green)
![Badge Creador](https://img.shields.io/badge/Created%20BY-Eduardo%20Rosas-blue) 
![Badge version](https://img.shields.io/badge/Version-1.0.0-blue)
![Badge thanksto](https://img.shields.io/badge/From-AluraLatam-red)

# Conversor de Divisas

El conversor de divisas es un reto propuesto por el programa [Oracle Next Education] 
(https://www.oracle.com/cl/education/oracle-next-education/) en conjunto con [Alura Latam](https://www.aluracursos.com/), para aplicar los conocimientos adquiridos durante los cursos de Java.

## Reglas
Las características solicitadas por nuestro cliente son las siguientes:

Este cuadro de dialogo debe permitir al usuario escoger entre las opciones de conversión, según los requisitos solo es necesario hacer un conversor de moneda pero en caso que desees implementar otras funciones en la foto anexada podemos ver una opción de menú con otras funciones.

- Utilice el método **showMessageDialog** para mostrar el valor de la conversión.
  
               
Recuerda que este input debe estar validado y no debe aceptar otro tipo de caracteres que no sean del tipo numéricos.

Utilice el método showInputDialog para que el usuario inserte un valor.


 
Utilice la clase  	**JOptionPane**  de la biblioteca **Javax**;
- Utilice el método **showInputDialog** como un objeto para presentar más de una opción;

Requisitos:
- **El convertidor de moneda debe:**

       - Convertir de la moneda de tu país  a Dólar
       - Convertir de la moneda de tu país  a Euros
       - Convertir de la moneda de tu país  a Libras Esterlinas
       - Convertir de la moneda de tu país  a Yen Japonés
       - Convertir de la moneda de tu país  a Won sul-coreano

- **Recordando que también debe ser posible convertir inversamente, es decir:**

       - Convertir de Dólar a la moneda de tu país
       - Convertir de Euros a la moneda de tu país
       - Convertir de Libras Esterlinas a la moneda de tu país
       - Convertir de Yen Japonés a la moneda de tu país
       - Convertir de Won sul-coreano a la moneda de tu país

## Uso


## Estructura del proyecto

Dentro de la carpeta [source](/src) están los archivos del programa. La organización y función de ellos es la siguiente:

- [`Moneda.java`](/src/Moneda.java) Es la clase encargada de realizar la conversión mediante una instancia de ella. Además, usa las constantes definidas en [`Divisas.java`](/src/Divisas.java) para hacer las conversiones.

- [`Divisas.java`](/src/Divisas.java) Es un enum que contiene los factores de conversión de divisas.

- [`ConversorGui.java`](/src/ConversorGui.java) Es la clase que crea la ventana principal del programa. Contiene todos los componentes y estilos, pero sin una funcionalidad determinada.

- [`Main.java`](/src/Main.java) Es la clase principal del programa. Donde se agregan funcionalidad a los componentes de la interfaz gráfica.

En la carpeta [bin](/bin/) se encuentra el bytecode generado por el programa.
 
<details>
<summary>Tecnologias Usadas en este Challenge</summary>

| Herramientas | Languages |
|-----:|-----------|
|  Windows 11    | Java   |
|  IntelliJ IDEA | Spring |
|                |        |

</details>

<p align="center" dir="auto">
<img align="center" src="https://skills.thijs.gg/icons?i=java,idea,git,spring" />
</p>## Java-Conversor
