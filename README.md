# 🥋 AppScore — Sistema de Torneos de Taekwondo

**AppScore** es una aplicación desarrollada en **Flutter + Isar** para la gestión de torneos deportivos en la disciplina del Taekwondo.  
Permite a los jueces tener el control de los puntos de los competidores,y sincronizar puntajes en tiempo real desde controladores basados en **ESP32**.

---

## Características principales

✅ **Gestión de competidores**  
Ingreso de competidores, envio a sala de espera en cada disciplina, para proximamente envia a competencia. 

✅ **Integración con AppControl (ESP32)**  
Recepción en tiempo real de puntuaciones enviadas por 3 dispositivos vía WIFI, mostrando resultados instantáneos en pantalla.

✅ **Modo Espectador**  
Visualización en pantalla secundaria con puntuaciones, categorías y colores personalizables.

✅ **Base de datos local**  
Uso de **Isar** para almacenamiento offline, con opción futura de sincronización en la nube.

---

## Tecnologías utilizadas

- **Flutter (Dart)** — Interfaz y lógica multiplataforma  
- **Isar Database** — Persistencia local ultra rápida  
- **ESP32 (Arduino)** — Controladores inalámbricos de puntuación  
- **CMake / Desktop support** — Compilación multiplataforma (Linux / Windows)

---

## Vista previa

| Control móvil (AppControl) | Pantalla de puntuación (AppScore) |
|-----------------------------|-----------------------------------|
| ![AppControl](readme-assets/appcontrol.jpg) | ![AppScore](readme-assets/appscore.jpg) |

*(Imágenes de demostración del sistema en acción)*

---

## Próximos pasos

- [ ] Sincronización con nube (Firebase o servidor propio)  
- [ ] Sistema de torneos multi-deporte  
- [ ] Publicación de AppControl en Play Store  

---

## Autor

**Fernando Cruz**  
[LinkedIn](https://www.linkedin.com/in/fernando-cruz)  
[GitHub](https://github.com/fer301175)

---

> Proyecto desarrollado como solución integral para la gestión de torneos de Taekwondo, combinando software, hardware y diseño de sistemas electrónicos.
