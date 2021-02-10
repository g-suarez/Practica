[![Work in Repl.it](https://classroom.github.com/assets/work-in-replit-14baed9a392b3a25080506f3b7b6d57f295ec2978f6f33ec97e36a161684cbe9.svg)](https://classroom.github.com/online_ide?assignment_repo_id=3489329&assignment_repo_type=AssignmentRepo)
# **Quiz 1**

La siguiente evaluación es para que demuestres tus conocimientos en la materia, es importante **no** usar librerías externas, y solo usar las herramientas que hemos visto hasta ahora para su solución. **Es necesario el uso de la función main en su código.**

**Nota**: Si no haces push al repositorio no se corregirá el quiz.

- [**Quiz 1**](#quiz-1)
  - [**Ejercicio 1**](#ejercicio-1)
  - [**Ejercicio 2**](#ejercicio-2)

___

## **Ejercicio 1**

Un número curioso es todo número natural n que cumple que n^2 tiene al propio n como última cifra. Por ejemplo, 25 y 36 son números curiosos. Realice una función que dado un número n cualquiera, determine si ese número es o no un número curioso.

___

## **Ejercicio 2**

Una empresa organizadora de eventos te ha contratado para que realices un programa que los ayude a administrar la venta de entradas de los eventos que ofrecen. El software debe contener lo siguiente:
Solicitar nombre, cédula y correo electrónico del cliente
Permitir que el usuario seleccione uno de los eventos ofertados por la empresa (guardados con tipo, fecha, hora, precio, cantidad de entradas vendidas y cantidad de entradas disponibles en un diccionario dado), y decida cuántas entradas comprará (siempre que están disponibles)
Si la suma de la cantidad de letras del primer nombre del cliente es un número primo, se le otorgará un 7% de descuento a su compra (por ejemplo, “Ana” tiene 3 letras y 3 es un número primo, así que tendrá dicho descuento)
Al finalizar la compra, debe mostrarse un resumen por pantalla, incluyendo datos del cliente, datos del evento, cantidad de entradas adquiridas, el monto sin descuento y el monto final a pagar por el cliente
Cada vez que se finalice una compra, debe actualizarse la cantidad de entradas vendidas y disponibles de los eventos
El programa debe contener validaciones para todos los datos que las requieran


***Nota: trabajar con funciones.***

```python
eventos = {
'Limbo World Tour' : {'Type' : 'Concierto', 'Date' : '04/11/2020', 'Time' : '09:00 PM', 'Price per ticket' : 260.80, 'Available' : 15, 'Sold' : 1325},
    'Hamlet' : {'Type' : 'Obra de teatro', 'Date' : '15/11/2020', 'Time' : '12:45 PM', 'Price per ticket' : 0.00, 'Available' : 32, 'Sold' : 132},
    'El Cascanueces' : {'Type' : 'Presentación de danza', 'Date' : '01/12/2020', 'Time' : '05:30 PM', 'Price per ticket' : 100.00, 'Available' : 10, 'Sold' : 1100},
    'The Tenderloins' : {'Type' : 'Stand-up', 'Date' : '30/11/2020', 'Time' : '07:00 PM', 'Price per ticket' : 85.00, 'Available' : 30, 'Sold' : 640},
    'Manic World Tour' : {'Type' : 'Concierto', 'Date' : '16/12/2020', 'Time' : '08:20 PM', 'Price per ticket' : 460.50, 'Available' : 165, 'Sold' : 5970},
    'Trippy Caribbean Tour' : {'Type' : 'Concierto', 'Date' : '10/01/2021', 'Time' : '06:00 PM', 'Price per ticket' : 120.00, 'Available' : 230, 'Sold' : 240},
    'Macho Beta' : {'Type' : 'Stand-up', 'Date' : '23/01/2021', 'Time' : '08:40 PM', 'Price per ticket' : 30.60, 'Available' : 160, 'Sold' : 20},
    'Hamilton' : {'Type' : 'Obra de teatro', 'Date' : '12/12/2020', 'Time' : '03:25 PM', 'Price per ticket' : 80.00, 'Available' : 49, 'Sold' : 12},
    'El Rey León' : {'Type' : 'Obra de teatro', 'Date' : '20/01/2021', 'Time' : '11:50 AM', 'Price per ticket' : 21.00, 'Available' : 164, 'Sold' : 6},
    'Bailaora' : {'Type' : 'Presentación de danza', 'Date' : '03/02/2020', 'Time' : '05:00 PM', 'Price per ticket' : 68.22, 'Available' : 1200, 'Sold' : 300}
}
```

---