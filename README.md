# 🚀 Guía Básica de Flutter

Este documento contiene los comandos esenciales para trabajar con Flutter: desde la instalación, creación y ejecución de aplicaciones, hasta la gestión de dependencias y builds.

---

## 📦 Instalación y Configuración

### 1️⃣ Verificar instalación de Flutter
```bash
flutter doctor
```
Muestra el estado del entorno de desarrollo, verificando SDKs, IDEs y dependencias.

### 2️⃣ Ver la versión actual
```bash
flutter --version
```

### 3️⃣ Actualizar Flutter
```bash
flutter upgrade
```
Actualiza el SDK a la última versión estable.

---

## 🧱 Crear un Nuevo Proyecto

### 1️⃣ Crear una nueva aplicación Flutter
```bash
flutter create nombre_app
```

### 2️⃣ Entrar en el directorio del proyecto
```bash
cd nombre_app
```

---

## ▶️ Ejecutar la Aplicación

### 1️⃣ Ver los dispositivos conectados
```bash
flutter devices
```

### 2️⃣ Ejecutar en modo debug
```bash
flutter run
```

### 3️⃣ Ejecutar en modo release
```bash
flutter run --release
```

---

## 🧩 Dependencias

### 1️⃣ Añadir un paquete al proyecto
Ejemplo para agregar **http**:
```bash
flutter pub add http
```

### 2️⃣ Obtener dependencias
```bash
flutter pub get
```

### 3️⃣ Limpiar caché del proyecto
```bash
flutter clean
```

---

## 🧪 Modo Desarrollo

### Hot Reload (recarga rápida)
Guarda los cambios y presiona:
```
r
```
en la terminal donde corre la app.

### Hot Restart (reinicio completo)
Presiona:
```
R
```
en la terminal.

---

## 🏗️ Construir la Aplicación

### 1️⃣ Build para Android
```bash
flutter build apk --release
```

### 2️⃣ Build para iOS (solo en macOS)
```bash
flutter build ios --release
```

### 3️⃣ Build para Web
```bash
flutter build web
```

---

## 🧰 Comandos Útiles

| Comando | Descripción |
|----------|--------------|
| `flutter doctor` | Diagnostica problemas en la instalación. |
| `flutter pub get` | Descarga las dependencias del proyecto. |
| `flutter pub upgrade` | Actualiza las dependencias a sus últimas versiones. |
| `flutter format .` | Formatea automáticamente el código. |
| `flutter analyze` | Analiza el código en busca de errores o advertencias. |

---

## 💡 Tips

- Usa **VS Code** o **Android Studio** para mejor integración.
- Siempre ejecuta `flutter clean` y `flutter pub get` si tienes errores raros.
- Si usas **Git**, añade al `.gitignore` los archivos de compilación (`/build/`).

---

## 🧾 Recursos

- [Documentación Oficial Flutter](https://docs.flutter.dev)
- [Pub.dev (paquetes)](https://pub.dev)
- [Guía de instalación](https://docs.flutter.dev/get-started/install)

---

📱 *Hecho con ❤️ por tu equipo de desarrollo Flutter*
