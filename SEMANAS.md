# SEMANA 11

## REGISTROS SEGMENTO Y PROPÓSITO GENERAL

### REGISTRO SEGMENTO
Poseen 16 bits de longitud y facilita un área de memoria para direccionamiento conocido como segmento y son:  
- CS: 
- DS:
- SS:
- ES:
- FS:
- GS:

### REGISTROS DE PROPÓSITO GENERAL
Cada registro es de 16 bits y tienen 2 partes alta (H) y baja (L).
- AX, es el acumulador, empleado en operaciones de E/S y aritmética
- BX, es registro base, se emplea como índice, en direccionamiento
- CX, registro contador, se emplea como contador para el desplazamiento de bits
- DX, registro de datos, participa en operaciones de E/S y operaciones de multiplicación y división

## REGISTROS IP Y PUNTEROS

### REGISTRO IP (Index Pointer)

Contiene el desplazamiento en la dirección a la siguiente instrucción a ejecutar.
El IP está asociado con CS, para direccionar la instrucción actual del segmento de código.
Los procesadores 80386 y posteriores presenten un IP de 32 bits, llamado EIP (Extended IP).

### REGISTROS PUNTEROS

- SP, registro puntero de pila
- BP, registro puntero de base
Están asociados con el registro SS y permiten ingresar datos en el segmento pila. Son registros de 16 bits.
En los procesadores actuales son de 32 bits

## REGISTROS INDICE

Los registros SI y DI se usan para direccionamiento indexado y sumas y restas.

### REGISTRO SI (Source Index)

Es de 16 bits, se emplea en operaciones con cadenas de caracteres. Se asocia con DS.
Los procesadores 80385 y posteriores tienen 32 bits (ESI)

### REGISTRO DI

También es empleado en operaciones de cadenas y está asociado con el registro ES. 
En los procesadores posteriores al 80386, tienen 32 bits.

### REGISTRO DE BANDERAS

De 16 bits, sirven para indicar características del resultado obtenido por la ALU. 
Algunos indicadores son: OF, DF, SF, ZF, PF, CF.

## ALGORITMO DE BOOTH'S 

Algoritmo de multiplicación binaria con bit de signo

![image](https://github.com/AFO10/Arquitectura2024/assets/89848233/dfe1815a-5620-401d-86e4-aeac4354f31a)

# SEMANA 12:

## COMPONENTES

### TARJETA MADRE

Es el elemento principal, en la que se conectan dispositivos propios del computador. 
Desde hace mucho tiempo se sigue utilizando el formato ATX (Advanced Technologye Xtended), aunque ahora se utilizan formatos más reducidos como el micro ATX y el mini ITX

### SOCKET

El socket es el conector donde se coloca el microprocesador. Existen dos tipos de zócalos muy utilizados, el PGA y el LGA.

- Socket PGA: se compone de una matriz de contactos, mientras que los pines residen en el microprocesador.
  Son sockets utilizados en los procesadores AMD.

- Socket LGA: los pines están en el socket, mientras: Estos sockets son más delicados al tener los pines sobre sí mismos.
  Este tipo de sockets son usados por los microprocesadores Intel.

![image](https://github.com/AFO10/Arquitectura2024/assets/89848233/182d834b-dc28-4beb-91d2-ef558f4d486c)

### BIOS

Es el acrónimo base de Basic Input Output System (Sistema Básico de Entrada y Salida).
La BIOS realiza una serie de funciones antes de que el sistema operativo se haga con el control del equipo y realiza opraciones básicas de entrada y salida del sistema.
Una de las funciones de la BIOS es identificar los componentes básicos del equipo (microprocesador, memoria, unidades de almacenamiento, chipset, etc.).

### CHIPSET

Es un grupo de microprocesadores. Actualmente, la mayoría de las funciones las realiza un chip principal.
El chipset tiene la función de comunicar los elementos del computador (Unidad SSD, moemoria, microprocesador, tarjeta gráfica).

### MEMORIA RAM 

Está presente en muchos dispositivos electrónicos (dentro del procesador como caché, en unidades SSD como buffer o caché, en tarjetas gráficas como memorias de video, etc).
No obstante, cuando se habla de memoria RAM, la mayoría de las veces se refiere a la memoria principal.
La RAM, son circuitos integrados de color negro que están soldados a la placa base de color verde.
El conjunto de componentes, se llama módulo de memoria.

### TARJETA GRÁFICA

Es la responsable de enviar al monitor la información que el sistema desea visualizar por pantalla. 
Desde hace tiempo los microprocesadores incluyen un procesador gráfica en el encapsulado que permite al sistema la colaboración estrecha entre este procesador y el microprocesador principal, haciendo más rápida la fluidez de la información.






# SEMANA 13:
# SEMANA 14:
