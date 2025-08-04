# 📱 App Android: Login con Validación de Correo (UNS)

Este proyecto es una aplicación móvil desarrollada con **Android Studio** y **Kotlin**, que implementa un **sistema de inicio de sesión con Firebase Authentication**, personalizado con los colores y el logo institucional de la **Universidad Nacional del Santa (UNS)**.

---

## 🎯 Objetivo

La app permite a los usuarios iniciar sesión validando su **correo electrónico en tiempo real** con Firebase. Si el correo no está registrado, la app lo notifica antes de continuar. Si es válido, permite iniciar sesión y redirige a una pantalla de bienvenida.

---

## 🧰 Tecnologías utilizadas

- 🔹 **Kotlin**
- 🔹 **Android Studio (Gradle KTS)**
- 🔹 **Firebase Authentication (Email/Password)**
- 🔹 **Firebase BoM**
- 🔹 **Diseño XML personalizado**
- 🔹 **Firebase Console para gestión de usuarios**

---

## 🧪 Funcionalidades principales

- ✅ **Validación de correo en tiempo real**
- ✅ **Inicio de sesión seguro con Firebase**
- ✅ **Redirección a pantalla de bienvenida**
- ✅ **Diseño institucional con logo y colores UNS**
- ✅ **Interfaz amigable, clara y funcional**

---

## 🖼️ Capturas de pantalla

Todas las capturas están incluidas dentro del proyecto en la carpeta `res/drawable`.

|
|--------|--------|
| Login inicial con campos vacíos | `drawable/login_correo.png` |
| Validación de correo NO registrado | `drawable/errore_correo.png` |
| Validación de correo registrado y acceso | `drawable/validacion_correo.png` |

*(Puedes visualizar estas imágenes directamente desde Android Studio o incluirlas en un PDF del informe final.)*

---

## 🧱 Estructura del proyecto

📁 app/
├── 📂 src/
│ └── 📂 main/
│ ├── 📄 MainActivity.kt # Lógica del login con validación Firebase
│ ├── 📄 HomeActivity.kt # Pantalla de bienvenida
│ ├── 📂 res/
│ │ ├── 📄 activity_main.xml # Diseño del login
│ │ ├── 📄 activity_home.xml # Diseño institucional UNS
│ │ └── 📂 drawable/
│ │ ├── logo_uns.png
│ │ ├── captura_login_1.png
│ │ ├── captura_login_2.png
│ │ └── captura_login_3.png
├── 📄 AndroidManifest.xml # Registro de las Activities
├── 📄 build.gradle.kts (app & project)

## 🚀 Cómo ejecutar

1. Clona o abre el proyecto en Android Studio
2. Asegúrate de tener configurado Firebase:
   - `google-services.json` en la carpeta `app/`
   - Email/Password activado en Firebase Console
   - -Para nuesto eejmplo el usuario: uns@gmail y password: 123456
3. Sincroniza las dependencias (Gradle)
4. Ejecuta en un emulador o dispositivo físico

---

## 🏁 Resultado final

Al ingresar un correo válido y contraseña correcta, la app muestra una pantalla de bienvenida institucional con el logo y colores oficiales de la UNS, simulando una entrada a un sistema interno.

---

## 📌 Autor

**Lucciano Sebastián Camargo Herrera**  
Universidad Nacional del Santa — Escuela de Ingeniería de Sistemas  
Curso: Desarrollo de Aplicaciones Móviles
