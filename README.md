# descubre_dolores
# 🏛️ Descubre Dolores Hidalgo — Guía Turística Multimedia

Una aplicación móvil interactiva desarrollada con **Flutter** bajo los principios estrictos de **Clean Architecture (Arquitectura Limpia)** y el patrón de presentación **MVVM (Model-View-ViewModel)**.

Permite a los usuarios explorar los sitios históricos más emblemáticos de la Cuna de la Independencia Nacional, visualizando fotografías de alta calidad, escuchando audio-guías narradas y reproduciendo videos informativos.

---

## 📸 Características

- 🖼️ **Galería e Imágenes:** Fotografías optimizadas de cada sitio turístico emblemático.
- 🎧 **Audio-guía Narrada:** Control de reproducción interactivo (Play / Pause) utilizando el paquete `audioplayers`.
- 🎬 **Video Informativo:** Reproductor integrado mediante `video_player` con controles directos en pantalla.
- 🏛️ **Clean Architecture Estricta:** Desacoplamiento total entre lógica de negocio, acceso a datos y la interfaz de usuario.
- 🧪 **TDD & Pruebas Unitarias:** Cobertura de pruebas unitarias sobre la capa de Dominio con dobles de prueba (*Fake Repository*), sin depender de emuladores ni paquetes multimedia reales.

---

## 🏛️ Las 3 Capas y la Regla de Dependencia

El proyecto respeta la **Regla de Dependencia**, donde las dependencias siempre apuntan hacia el centro: **Presentación ➔ Dominio 🠔 Datos**.
<img width="792" height="239" alt="image" src="https://github.com/user-attachments/assets/cc677a6f-67bf-4f5d-838b-751cb9df7409" />
<img width="607" height="314" alt="image" src="https://github.com/user-attachments/assets/ba9e2c45-0a45-4d7f-86a5-811900670b53" />
<img width="607" height="316" alt="image" src="https://github.com/user-attachments/assets/a851d887-144a-4c0d-9def-97406b91ae2f" />

