Tarea 7: El Problema de la Cena de los Filósofos

Descripción
Este proyecto implementa una solución al problema clásico de sincronización conocido como "La Cena de los Filósofos". El problema consiste en cinco filósofos sentados alrededor de una mesa circular que alternan entre pensar y comer. Para comer, cada filósofo necesita dos tenedores (palillos), uno a su izquierda y otro a su derecha.

Estructura del Proyecto
El proyecto está organizado en las siguientes clases:

Filosofo.java: Implementa la interfaz Runnable y define el comportamiento de cada filósofo (hilo).

Palillo.java: Gestiona el estado de cada palillo utilizando semáforos para controlar el acceso.

Principal.java: Clase principal que inicia la ejecución del programa y coordina los filósofos y palillos.

Funcionalidades
Sincronización: Uso de semáforos (Semaphore) para gestionar el acceso a los palillos.

Prevención de interbloqueo: Estrategia para evitar que dos filósofos intenten acceder al mismo recurso simultáneamente.

Prevención de inanición: Liberación adecuada de recursos para permitir que todos los filósofos tengan la oportunidad de comer.

Ejecución del Programa
Al ejecutar el programa, se simula el comportamiento de los filósofos, mostrando en consola:

Cuándo un filósofo intenta comer.

Cuándo un palillo es cogido o liberado.

Cuándo un filósofo termina de comer o vuelve a pensar.

Ejemplo de Salida:
text
El filosofo 5 se encuentra pensando
El filosofo 1 intenta comer
El palillo 1 ha sido cogido
El palillo 2 ha sido cogido
El filosofo 1 se encuentra comiendo
El palillo 1 ha sido liberado
El palillo 2 ha sido liberado
El filosofo 1 ha terminado de comer
El filosofo 1 se encuentra pensando
El filosofo 2 intenta comer
El palillo 2 ha sido cogido
El palillo 3 ha sido cogido
El filosofo 2 se encuentra comiendo
Conclusiones
Este ejercicio permite comprender conceptos fundamentales de la programación concurrente, como:

Sincronización de hilos.

Uso de semáforos para gestionar recursos compartidos.

Prevención de interbloqueos e inanición.

Además, refuerza conocimientos de programación orientada a objetos y su aplicación en problemas del mundo real.

Autor: Enrique de la Fuente Méndez
Asignatura: Programación de Servicios y Procesos
Institución: MEDAC - Instituto Oficial de Formación Profesional
