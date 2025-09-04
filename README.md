# MiniTalk-C-Real-Time-IPC – Comunicación Interprocesos en C

![MiniTalk Banner](./assets/minitalk-banner.webp)

## Descripción del Proyecto

**MiniTalk** es un proyecto de comunicación entre procesos (IPC) desarrollado en **C**, utilizando **señales UNIX** para transmitir mensajes en **tiempo real**.

Este proyecto **demuestra habilidades críticas para roles de desarrollo de sistemas y backend**:

* Programación de bajo nivel y manejo de memoria.
* Arquitectura cliente-servidor robusta y eficiente.
* Resolución de problemas complejos con lógica binaria y sincronización de procesos.
* Implementación de sistemas confiables listos para producción.

## 🚀 Funcionalidades Destacadas

* **Comunicación confiable entre procesos:** mensajes enviados por el cliente y decodificados por el servidor en tiempo real.
* **Codificación a nivel de bits:** cada carácter se transmite mediante `SIGUSR1` y `SIGUSR2`.
* **Arquitectura cliente-servidor escalable:** soporta múltiples mensajes y garantiza integridad de datos.
* **Confirmación de recepción:** asegura que cada mensaje llegue completo y correcto.

## 🛠️ Tecnologías y Herramientas

* **Lenguaje:** C
* **Sistemas:** UNIX / Linux
* **Conceptos aplicados:** IPC, señales UNIX, manipulación de bits, sincronización de procesos, manejo de errores.
* **Herramientas:** GCC, make, terminal Bash

## 📈 Competencias Profesionales

* **Programación de bajo nivel y eficiencia:** interacción directa con memoria y procesos.
* **Resolución de problemas complejos:** lógica precisa para transmisión de datos en tiempo real.
* **Diseño de sistemas robustos:** arquitectura cliente-servidor con control de errores y confirmación de mensajes.
* **Transferible a roles de empresa:** backend de alto rendimiento, sistemas embebidos, operaciones críticas y desarrollo de software escalable.

## ⚡ Cómo Ejecutar el Proyecto

1. Clona el repositorio:

```bash
git clone https://github.com/tuusuario/minitalk.git
cd minitalk
```

2. Compila el proyecto:

```bash
make
```

3. Inicia el servidor en una terminal:

```bash
./server
```

4. Envía mensajes desde el cliente en otra terminal:

```bash
./client <PID_del_servidor> "Tu mensaje aquí"
```
