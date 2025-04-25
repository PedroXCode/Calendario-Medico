# 🩺 Agenda Médica en C++

Este proyecto es una agenda médica de consola desarrollada en C++, diseñada para manejar citas entre pacientes y doctores. Permite registrar, visualizar y eliminar citas médicas, además de mostrar un calendario visual por mes.

---

## 📌 Funcionalidades

- **Login básico**
  - Usuario: `admin`
  - Contraseña: `admin123`
  - El usuario "admin" accede como doctor con más privilegios.
  - Cualquier otro usuario se identifica como paciente.

- **Menú del Doctor**
  - Ver citas por paciente
  - Ver citas por doctor
  - Ver calendario mensual
  - Eliminar citas

- **Menú del Paciente**
  - Ver sus citas
  - Crear nueva cita médica
  - Cancelar cita
  - Ver calendario mensual

- **Calendario**  
  Visualización del mes con días organizados (Lunes a Domingo).


## 📁 Archivos generados

- `citas.txt`: Se guarda automáticamente en el mismo directorio que el ejecutable y contiene todas las citas registradas.

---

## 🛠 Compilación

Puedes compilar el programa con cualquier compilador de C++. Por ejemplo, en Windows con g++:

```bash
g++ -o agendaMedica agendaMedica.cpp
./agendaMedica
