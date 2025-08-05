# 🎮 Piedra, Papel, Tijera - Edición Minecraft

<div align="center">
  <img width="250" height="420"   alt="piedra_papel_tijera_portada" src="https://github.com/user-attachments/assets/e56b059a-1b71-46ea-bc6f-9050efad790c" />
</div>

Un juego interactivo de Piedra, Papel, Tijera con temática de Minecraft, desarrollado con HTML, CSS y JavaScript vanilla. Incluye dos modalidades de juego: clásica y especial (con Lagarto y Spock). 

## 📋 Descripción

Este proyecto implementa el clásico juego de Piedra, Papel, Tijera con una interfaz visual inspirada en Minecraft. Ofrece múltiples modos de juego y una experiencia interactiva tanto para navegador como para consola.

### 🎯 Características Principales

- **Modo Clásico**: Piedra, Papel, Tijera tradicional.
- **Modo Especial**: Incluye Lagarto y Spock (versión extendida popularizada por "The Big Bang Theory")
- **Modo Un Jugador**: Juega contra la máquina.
- **Modo Dos Jugadores**: Juega contra otro jugador.
- **Modo Consola**: Versión para navegador con interfaz de consola.
- **Modo Página**: Versión visual completa
- **Sistema de Puntuación**: Seguimiento de victorias por partida.
- **Temática Minecraft**: Fuentes, imágenes y fondos personalizados.

## 🚀 Demo

El juego incluye múltiples páginas interconectadas:
- Página de inicio con animaciones.
- Selección de modo de juego.
- Interfaces de selección para 1 y 2 jugadores.
- Páginas de resultados con tablas de puntuación.
- Sistema de navegación completo.

## 🛠️ Tecnologías Utilizadas

```
Piedra_Papel_Tijera/
│
├── index.html (pagina_comienzo.html)
├── style.css
│
├── 📁 Páginas principales
│   ├── eleccionModo.html
│   ├── ModoPagina.html
│   ├── ModoConsola.html
│   ├── ModoJuegoNormal.html
│   └── ModoJuegoEspecial.html
│
├── 📁 Juego Un Jugador
│   ├── UnJugador.html
│   ├── UnJugadorEspecial.html
│   ├── versus.html
│   ├── versusEspecial.html
│   ├── Resultado1JugadorNormal.html
│   └── Resultado1JugadorEspecial.html
│
├── 📁 Juego Dos Jugadores
│   ├── DosJugadores.html
│   ├── DosJugadoresEspecial.html
│   ├── versus2Jugadores.html
│   ├── versus2JugadoresEspecial.html
│   ├── Resultados2JugadoresNormal.html
│   └── Resultado2JugadoresEspecial.html
│
├── 📁 Recursos
│   ├── img/
│   │   ├── fondos (fondoAnimado.gif, fondoMinecraft.jpg, etc.)
│   │   ├── opciones (piedra.png, papel.png, tijeras.png, lagarto.png, spock.png)
│   │   ├── interfaz (versus.png, cuadro.png, etc.)
│   │   └── decorativos (steve.png, gifCreaper.gif, etc.)
│   │
│   └── fonts/
│       └── minecraft/
│           └── Minecraft.ttf
│
└── ExplicarJuego.html
```

## 🎮 Modos de Juego

### Modo Clásico (Normal)
- **Piedra** vence a Tijera
- **Papel** vence a Piedra
- **Tijera** vence a Papel

### Modo Especial (Lagarto Spock)
- **Piedra** vence a Tijera y Lagarto
- **Papel** vence a Piedra y Spock
- **Tijera** vence a Papel y Lagarto
- **Lagarto** vence a Papel y Spock
- **Spock** vence a Piedra y Tijera

## 🎯 Funcionalidades

### Sistema de Usuario
- Registro de nombre de usuario
- Persistencia de datos con LocalStorage
- Visualización de nombre en todas las páginas

### Sistema de Puntuación
- Seguimiento independiente para cada modo
- Puntuación separada para 1 y 2 jugadores
- Tablas de resultados visuales
- Persistencia de puntuaciones entre sesiones

### Navegación
- Sistema de navegación completo entre páginas
- Botones "Atrás" en todas las secciones.
- Flujo de juego intuitivo

## 📱 Compatibilidad

- ✅ Chrome/Chromium
- ✅ Firefox
- ✅ Safari  
- ✅ Edge
- ✅ Dispositivos móviles (responsive)

## 🐛 Problemas Conocidos

- Las fuentes personalizadas pueden no cargar en algunos navegadores antiguos
- El LocalStorage se limpia si el usuario borra los datos del navegador

## ✨ Autor

**Diego André Cornejo Giraldo**
- Fecha: 13/10/24
- Versión: 1.0

⭐ ¡Si te gusta este proyecto, no olvides darle una estrella!
