*This project has been created as part of the 42 curriculum by paapahid

# 📦 Nombre del Proyecto

## 📖 Description

Este proyecto forma parte del currículo de **42**. Su objetivo principal es **describir claramente qué se ha construido, por qué se ha construido y qué se aprende con él**.

Incluye:

* 🎯 El propósito del proyecto
* 🧠 Los conceptos técnicos clave
* 🧩 Una visión general de su funcionamiento

Este README está diseñado para que **cualquier persona externa (estudiantes, staff, recruiters)** pueda entender rápidamente el proyecto.

---

## ⚙️ Instructions

### 🔧 Compilation / Installation

```bash
git clone https://github.com/tuusuario/nombre_proyecto.git
cd nombre_proyecto
make
```

Limpieza de archivos compilados:

```bash
make fclean
```

### ▶️ Execution

```bash
./nombre_del_programa [argumentos]
```

Ejemplo:

```bash
./programa ejemplo1 ejemplo2
```

---

## 🖥️ Project Description – System & Design Choices

### 🐧 Operating System Choice

Este proyecto ha sido desarrollado utilizando **Debian / Rocky Linux**.

#### Debian

**Pros:**

* Estabilidad y fiabilidad
* Amplia documentación
* Gran comunidad

**Cons:**

* Paquetes más conservadores
* Menor frecuencia de actualizaciones

#### Rocky Linux

**Pros:**

* Compatibilidad con entornos empresariales
* Seguridad reforzada
* Cercano a Red Hat Enterprise Linux

**Cons:**

* Curva de aprendizaje más pronunciada
* Comunidad más pequeña que Debian

---

### 🔐 Security Framework

#### AppArmor vs SELinux

| AppArmor                 | SELinux                      |
| ------------------------ | ---------------------------- |
| Más simple de configurar | Más granular y potente       |
| Basado en perfiles       | Basado en políticas          |
| Ideal para principiantes | Usado en entornos enterprise |

---

### 🔥 Firewall

#### UFW vs firewalld

| UFW               | firewalld         |
| ----------------- | ----------------- |
| Simple y directo  | Más flexible      |
| Ideal para Debian | Estándar en Rocky |
| Fácil de mantener | Gestión avanzada  |

---

### 🧱 Virtualization Tool

#### VirtualBox vs UTM

| VirtualBox       | UTM                      |
| ---------------- | ------------------------ |
| Multiplataforma  | Optimizado para macOS    |
| Amplio soporte   | Interfaz moderna         |
| Más configurable | Menos opciones avanzadas |

---

### 🛠️ Main Design Choices

* 📂 Particionamiento del sistema
* 👤 Gestión de usuarios y grupos
* 🔐 Políticas de seguridad aplicadas
* 🔌 Servicios instalados y justificación

---

## 📂 Project Structure

```bash
.
├── src/
├── include/
├── config/
├── scripts/
├── Makefile
└── README.md
```

---

## 📚 Resources

### 📖 Technical References

* Documentación oficial de Debian / Rocky Linux
* Manuales de AppArmor / SELinux
* Documentación de UFW / firewalld
* VirtualBox / UTM official docs

### 🤖 Use of AI

La inteligencia artificial se ha utilizado de forma **responsable y transparente** para:

* Aclarar conceptos teóricos
* Revisar documentación
* Mejorar la redacción del README

No se ha utilizado IA para generar código evaluable del proyecto.

---

## 📌 Additional Notes

Secciones adicionales pueden añadirse según el proyecto:

* Ejemplos de uso
* Features
* Decisiones técnicas
* Limitaciones conocidas

---

## 👤 Author

**Nombre Apellido**
42 Student
Campus: ___

[GitHub Profile](https://github.com/tuusuario)

---

> 💡 *Un README claro y honesto es tan importante como el propio proyecto.*
