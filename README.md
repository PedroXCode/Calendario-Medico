# 🩺 MediScheduler (Agenda Médica en C++)

Este proyecto es una agenda médica simple de consola, desarrollada en C++. Permite que médicos y pacientes gestionen citas médicas, eliminen citas y vean un calendario.

---

## 📌 Funcionalidades

- **Login básico**
  - Usuario: `admin`
  - Contraseña: `admin123`
- **Menú de Doctor**
  - Ver citas por paciente
  - Ver citas por doctor
  - Ver calendario
  - Eliminar citas
- **Menú de Paciente**
  - Ver citas
  - Crear nueva cita
  - Cancelar cita
  - Ver calendario
- **Calendario mensual** (Abril, Mayo y Junio incluidos)
- **Gestión de archivos**: Citas guardadas en `citas.txt`
- **Uso de vectores y estructuras en C++**

---

## 🚀 How to Use

1. Compila el programa en C++.
2. Ejecuta el archivo generado.
3. En el login:
   - Escribe `admin` y `admin123` para entrar como **doctor**.
   - Escribe cualquier otro usuario y contraseña para entrar como **paciente**.
4. Sigue las opciones del menú para gestionar citas.
5. El archivo `citas.txt` se creará automáticamente para guardar la información.

### 💻 Compilación rápida

```bash
g++ -o mediScheduler mediScheduler.cpp
./mediScheduler
```

---

## 📜 Version History

- **v1.0 (Abril 2025)**
  - Versión inicial del proyecto.
  - Funcionalidades básicas de login, gestión de citas, calendario y almacenamiento de datos.
  - Correcciones de warnings (inicialización de miembros, validación de `rename()`).

---
