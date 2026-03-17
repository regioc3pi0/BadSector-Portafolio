# Bad Sector 👾

[![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-3.x-0175C2?style=for-the-badge&logo=dart&logoColor=white)](https://dart.dev)
[![Flame](https://img.shields.io/badge/Flame-Engine-FF6600?style=for-the-badge)](https://flame-engine.org)
[![iOS](https://img.shields.io/badge/iOS-13%2B-000000?style=for-the-badge&logo=apple&logoColor=white)](https://apps.apple.com/mx/app/bad-sector/id6758281840)
[![App Store](https://img.shields.io/badge/App_Store-Descargar-0D96F6?style=for-the-badge&logo=app-store&logoColor=white)](https://apps.apple.com/mx/app/bad-sector/id6758281840)

> Un juego arcade retro de pixel-art donde pilotas un núcleo digital a través de un sistema CRT corrompido — recolectando frecuencias de hertz mientras sobrevives mortales scanlines y entidades glitch.

---

## 🎮 Acerca del Juego

**Bad Sector** es un juego arcade de supervivencia ambientado dentro de un monitor de rayos catódicos corrompido. Controlas a **CORE.EXE**, un píxel blanco que navega una pantalla negra llena de errores de sistema hostiles.

La amenaza principal es el **scanline REFRESH** — un rayo verde que barre la pantalla a velocidad creciente con cada hertz que recolectas. Tocarlo significa fin del juego. Tus únicas herramientas son el movimiento, una **mecánica de sigilo** (mantén presionado para volverte invisible y atravesar el scanline), y los power-ups que aparecen conforme avanzas.

A medida que tu puntaje sube, el sistema se degrada aún más: aparecen entidades glitch, un campo magnético te desvía del camino y el scanline acelera sin piedad. ¿Cuántos hertz puedes recolectar antes de que el sistema colapse?

---

## ✨ Características

### 🕹️ Mecánicas Principales
- **Arrastra para moverte** — controles táctiles fluidos usando gestos de deslizamiento
- **Mantén para entrar en sigilo** — toca y mantén presionado para activar el modo invisible y evitar el scanline
- **Velocidad progresiva** — el scanline acelera con cada hertz recolectado

### ⚡ Power-Ups
- **FIREWALL (Escudo)** — absorbe un impacto fatal del scanline antes de romperse, con efecto de explosión de partículas
- **LAG_SWITCH (Dilatación del Tiempo)** — ralentiza todo el mundo del juego por 5 segundos, dándote espacio para respirar

### 👾 Tipos de Enemigos
- **REFRESH** — el scanline principal, barre verticalmente a velocidad creciente
- **BURN-IN (Píxel Muerto)** — bloque cian sólido que repele físicamente al jugador
- **WHITE NOISE (Estática)** — círculo de interferencia vibrante con empuje suave
- **MAGNET** — te atrae hacia él con fuerza creciente mientras más cerca estés

### 🎯 Sistema de Dificultad
- Aparición de enemigos basada en puntaje: los glitches aparecen cada 2 hertz recolectados
- La variedad de enemigos se desbloquea progresivamente (Burn-In → White Noise → Magnet)
- Mensajes de alerta avisan al jugador en umbrales clave de dificultad

### 📺 Diseño Visual y de Audio
- **Efecto CRT personalizado** con superposición de scanlines, viñeta y tinte verde fósforo
- Sistema de partículas pixeladas para recolección de hertz, rotura de escudo y fin del juego
- **Secuencia de arranque BIOS** retro al inicio con pantallas de diagnóstico animadas
- Pantalla de advertencia de fotosensibilidad antes del juego
- Audio chiptune con soporte para silenciar

### 📱 Plataforma y Monetización
- Modo retrato, optimizado para iPhone
- **Google AdMob** — anuncios banner e intersticiales (mostrados cada 4 partidas)
- **App Tracking Transparency** — compatible con iOS 14+
- Persistencia del puntaje máximo mediante SharedPreferences
- Retroalimentación háptica en recolección, rotura de escudo y fin del juego

---

## 🛠️ Tecnologías Utilizadas

| Tecnología | Propósito |
|---|---|
| **Flutter** | Framework de UI |
| **Dart** | Lenguaje de programación |
| **Flame Engine** | Motor de juego 2D |
| **flame_audio** | Efectos de sonido y música de fondo |
| **google_mobile_ads** | Integración con AdMob |
| **shared_preferences** | Persistencia del puntaje máximo |
| **app_tracking_transparency** | Cumplimiento ATT de iOS |
| **url_launcher** | Links de política de privacidad y EULA |

---

## 📱 Descarga

<a href="https://apps.apple.com/mx/app/bad-sector/id6758281840">
  <img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Descargar en App Store" height="50"/>
</a>

---

## 📸 Capturas de Pantalla

> Próximamente — consulta las imágenes de vista previa en la App Store.

---

## 👨‍💻 Desarrollador

**regioc3pi0**
- GitHub: [@regioc3pi0](https://github.com/regioc3pi0)

---

## 📄 Licencia

Este proyecto es software propietario. El código fuente es privado.  
Todos los derechos reservados © 2025
