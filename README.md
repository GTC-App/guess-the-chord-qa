# 🎵 Guess The Chord - Beta Testing

> **Competitive ear training for chord recognition**  
> Train your ear through ranked PvP matches. Guess chord progressions, compete globally, and improve your musical skills.

🌐 **Sitio Web Oficial**: [guessthechord.com](https://guessthechord.com/)

---

## 🎯 Introducción

Bienvenido al programa Beta Testing de **Guess The Chord**. Como tester beta, tu rol es fundamental para garantizar que la aplicación funcione correctamente antes del lanzamiento público.

### ¿Qué es Guess The Chord?

Una aplicación iOS de entrenamiento auditivo musical donde dos jugadores compiten en tiempo real para identificar progresiones de acordes en loops musicales.

### Flujo de Partida

🎯 **Find a match** → 🎧 **Listen & analyze** → 🎹 **Assign chords** → ✅ **Submit answers** → 🏆 **Win the round**

---

## 🎯 Objetivos de la Fase Beta

### Objetivos Principales

1. **Validar la estabilidad del sistema** en condiciones reales de uso
2. **Identificar bugs críticos** que afecten la experiencia de usuario
3. **Evaluar la jugabilidad** y balance del sistema de ranking
4. **Probar la conectividad** en diferentes condiciones de red
5. **Recopilar feedback** sobre UX/UI y dificultad de los acordes
6. **Testear la app en español e inglés** - Validar ambos idiomas completamente
7. **Testear el proceso de Music Submissions End-to-End** - Flujo completo de subir música
8. **Encontrar errores gramaticales** - Revisar textos en ambos idiomas

### Objetivos Secundarios

- Identificar problemas de rendimiento
- Detectar edge cases no contemplados
- Validar tiempos de respuesta del backend
- Probar compatibilidad con diferentes versiones de iOS
- Evaluar consumo de batería y datos



---

## 👥 Perfil del Tester Beta

### Requisitos Técnicos

- **Dispositivo iOS**: iPhone con iOS 17.0 o superior
- **Conexión a Internet**: WiFi o datos móviles estables
- **Espacio de almacenamiento**: Mínimo 200 MB disponibles

### Requisitos de Conocimiento

- **Nivel Musical**: Desde principiante hasta avanzado (todos los niveles son valiosos)
- **Experiencia con Apps**: Usuario regular de aplicaciones móviles
- **Disponibilidad**: Mínimo 30-60 minutos diarios durante la fase beta
- **Comunicación**: Capacidad para reportar bugs de forma clara

### Tipos de Testers Ideales

1. **Músicos Principiantes**: Validar curva de aprendizaje
2. **Músicos Intermedios**: Evaluar balance de dificultad
3. **Músicos Avanzados**: Probar tiers superiores y acordes complejos
4. **No Músicos**: Validar onboarding y accesibilidad

---

## ⚙️ Configuración Inicial

### Paso 1: Instalación

1. Instala **Guess The Chord** desde TestFlight
2. Acepta los permisos solicitados (notificaciones, audio)

### Paso 2: Registro

1. Abre la aplicación
2. Crea una cuenta usando:
   - Email y contraseña
   - O inicio de sesión social (Google/Apple)
3. Verifica tu email si es requerido
4. Completa el perfil inicial (nombre de usuario, instrumento preferido)

### Paso 3: Familiarización

Antes de comenzar el testing formal:

1. Juega **2-3 partidas de práctica** para entender la mecánica
2. Explora todas las secciones de la app
3. Revisa la configuración disponible

### Paso 4: Herramientas de Testing

- **Capturas de pantalla**: Para documentar bugs visuales
- **Grabación de pantalla**: Para bugs de flujo o animaciones
- **Notas**: App de notas para registrar observaciones rápidas
---

## 🔬 Metodología de Testing

### Tipos de Testing a Realizar

#### 1. Testing Exploratorio (40% del tiempo)

**Objetivo**: Usar la app de forma natural y descubrir problemas inesperados.

**Cómo hacerlo**:
- Usa la app como lo haría un usuario real
- No sigas un script, sé creativo
- Intenta acciones "fuera de lo común"
- Anota cualquier comportamiento extraño

**Ejemplos**:
- Minimizar la app durante una partida
- Cambiar de WiFi a datos móviles en medio de un match
- Rotar el dispositivo en diferentes pantallas
- Presionar botones rápidamente múltiples veces

#### 2. Testing Funcional (30% del tiempo)

**Objetivo**: Verificar que todas las funcionalidades principales funcionen correctamente.

**Áreas a probar**:
- Autenticación (login, logout, recuperación de contraseña)
- Matchmaking (encontrar oponente, cancelar búsqueda)
- Gameplay (seleccionar acordes, enviar respuestas, ver resultados)
- Perfil (ver estadísticas, cambiar configuración)
- Suscripciones (si aplica)

#### 3. Testing de Regresión (15% del tiempo)

**Objetivo**: Verificar que bugs reportados anteriormente estén resueltos.

**Cómo hacerlo**:
- Revisa el changelog de cada nueva build
- Re-prueba los bugs que reportaste previamente
- Confirma si están resueltos o persisten

#### 4. Testing de Usabilidad (15% del tiempo)

**Objetivo**: Evaluar la experiencia de usuario.

**Preguntas a responder**:
- ¿Es intuitiva la navegación?
- ¿Los textos son claros?
- ¿Los botones son fáciles de presionar?
- ¿Los colores y contrastes son adecuados?
- ¿La app responde rápidamente?

---


## 🐛 Reporte de Bugs (MEGA IMPORTANTE)

### Estructura de un Buen Reporte

Un bug bien reportado es más fácil de reproducir y resolver. Usa esta plantilla:

```markdown
## [ID-ÚNICO] Título Descriptivo del Bug

**Descripción**:
[Descripción clara y concisa del problema]

**Entorno**:
- Dispositivo: [iPhone 14 Pro]
- iOS: [17.2]
- Versión de la App: [1.0.0 (Build 42)]
- Conexión: [WiFi / 4G / 5G]

**Evidencia**:
[Adjunta capturas de pantalla o videos]

```

---


### Herramienta para Reportar

**GitHub Issues** es el canal oficial y único para reportar bugs:

- **Repositorio**: [GTC-App/guess-the-chord-qa](https://github.com/GTC-App/guess-the-chord-qa)
- **Crear Issue**: [Nuevo Bug Report](https://github.com/GTC-App/guess-the-chord-qa/issues/new)
- **Ver Issues Existentes**: [Lista de Issues](https://github.com/GTC-App/guess-the-chord-qa/issues)

**Importante**: 
- Usa la plantilla de reporte mostrada arriba
- Incluye capturas de pantalla o videos como adjuntos
- Revisa primero si el bug ya fue reportado antes de crear uno nuevo

---

## ✅ Checklist Diario (Recomendado)

Usa este checklist cada día de testing:

### Antes de Empezar (5 min)

- [ ] Verificar que tienes la última versión de la app
- [ ] Leer changelog de la nueva build (si aplica)
- [ ] Revisar bugs reportados previamente (para re-testing)
- [ ] Preparar herramientas (capturas, notas)

### Durante la Sesión (30-60 min)

**Testing Exploratorio (15-20 min)**
- [ ] Jugar 3-5 partidas normalmente
- [ ] Probar una funcionalidad nueva o poco explorada
- [ ] Intentar acciones "creativas" o inesperadas

**Testing Funcional (10-15 min)**
- [ ] Ejecutar 2-3 casos de prueba de la lista
- [ ] Rotar entre diferentes módulos cada día

**Testing de Regresión (5-10 min)**
- [ ] Re-probar 1-2 bugs reportados previamente
- [ ] Verificar si están resueltos

**Testing de Usabilidad (5-10 min)**
- [ ] Anotar cualquier fricción en la UX
- [ ] Identificar flujos confusos
- [ ] Sugerir mejoras

### Después de la Sesión (10 min)

- [ ] Reportar todos los bugs encontrados
- [ ] Actualizar estado de bugs re-testeados
- [ ] Anotar feedback general


---




## 📅 Cronograma de Beta Testing

### Período de Testing
- **Inicio**: 11 de febrero de 2026
- **Cierre**: 20 de febrero de 2026
- **Duración**: 10 días

### Objetivos del Período
- **Identificar bugs críticos** que afecten la experiencia de usuario
- **Validar funcionalidades principales** (autenticación, matchmaking, gameplay)
- **Probar estabilidad** en diferentes condiciones de red y dispositivos
- **Recopilar feedback** sobre UX/UI y dificultad

### Dedicación
- **Tiempo mínimo sugerido**: 30-60 minutos diarios
- **Flexibilidad**: Cada tester puede dedicar el tiempo que desee
- **Importante**: Todos los reportes deben ser enviados antes del **20 de febrero a las 23:59 (UTC-3)**

---



## 🙏 Agradecimientos

Gracias por ser parte del programa Beta Testing de Guess The Chord. Tu tiempo y esfuerzo son invaluables para crear una experiencia excepcional para todos los usuarios.

**¡Feliz Testing! 🎵🎮**

---

**Versión del Documento**: 1.0  
*Fecha de última actualización: 10 de febrero de 2026*   