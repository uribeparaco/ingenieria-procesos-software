# 🔥 HabitUp — App de Hábitos y Retos Diarios

> JUAN CAMILO BAEZ BAUTISTA- ACTIVIDAD 
> Requisitos Funcionales y No Funcionales

---

## 📋 Descripción del Problema

Muchas personas quieren mejorar su vida adoptando nuevos hábitos (hacer ejercicio, leer, tomar agua, estudiar), pero se les olvida o se desmotivan a los pocos días porque no tienen un sistema que los acompañe. La solución es una app sencilla donde el usuario registra sus hábitos diarios, recibe retos semanales y puede ver su progreso en el tiempo para mantenerse motivado.

---

## ✅ Requisitos Funcionales

Los requisitos funcionales describen **qué debe hacer** el sistema.

### RF-01 — Registro e inicio de sesión
El sistema debe permitir que el usuario cree una cuenta con correo y contraseña, o inicie sesión con Google.

### RF-02 — Crear hábitos personalizados
El sistema debe permitir al usuario crear hábitos propios indicando nombre, descripción, frecuencia (diario, semanal) y hora de recordatorio.

### RF-03 — Marcar hábito como completado
El sistema debe permitir al usuario marcar cada hábito como completado en el día actual con un solo toque.

### RF-04 — Retos semanales
El sistema debe sugerir al usuario un reto nuevo cada semana (por ejemplo: "toma 8 vasos de agua al día por 7 días") que pueda aceptar o rechazar.

### RF-05 — Racha de días (streak)
El sistema debe registrar y mostrar cuántos días consecutivos el usuario ha cumplido cada hábito, motivándolo a no romper la racha.

### RF-06 — Estadísticas y progreso
El sistema debe mostrar al usuario un resumen visual de su progreso: porcentaje de cumplimiento semanal y mensual por cada hábito.

### RF-07 — Notificaciones y recordatorios
El sistema debe enviar una notificación al usuario a la hora configurada para recordarle completar su hábito del día.

### RF-08 — Logros y recompensas
El sistema debe desbloquear insignias o logros cuando el usuario alcance metas (7 días seguidos, 30 días, primer reto completado, etc.).

---

## 🔒 Requisitos No Funcionales

Los requisitos no funcionales describen **cómo debe comportarse** el sistema.

### RNF-01 — Rendimiento
El sistema debe cargar la pantalla principal con los hábitos del día en menos de 2 segundos.

### RNF-02 — Disponibilidad
El sistema debe funcionar sin conexión a internet para marcar hábitos, sincronizando los datos cuando haya conexión disponible.

### RNF-03 — Seguridad
El sistema debe proteger los datos personales del usuario y almacenar las contraseñas de forma cifrada, cumpliendo la Ley de Protección de Datos Personales.

### RNF-04 — Usabilidad
La interfaz debe ser simple e intuitiva. Un usuario nuevo debe poder registrar su primer hábito en menos de 2 minutos.

### RNF-05 — Compatibilidad
El sistema debe funcionar en dispositivos Android (versión 8 o superior) e iOS (versión 13 o superior).

### RNF-06 — Escalabilidad
El sistema debe soportar hasta 5.000 usuarios activos sin afectar el tiempo de respuesta.

### RNF-07 — Mantenibilidad
El código debe estar organizado por módulos y documentado, facilitando agregar nuevas funciones en el futuro.

