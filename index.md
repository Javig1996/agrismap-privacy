# Política de Privacidad — Agris Map

**Última actualización:** 23 de mayo de 2026  
**Desarrollador:** INNOVA 3DR  
**Contacto:** xavierguevara277@gmail.com

---

## 1. Información que recopilamos

### 1.1 Datos de cuenta
- Nombre y correo electrónico al registrarte
- Foto de perfil (opcional)

### 1.2 Datos de ubicación
- **Ubicación en primer plano:** cuando la app está activa, recopilamos tu posición GPS para mostrarla en el mapa y calcular rutas.
- **Ubicación en segundo plano:** cuando activas el seguimiento GPS, recopilamos tu ubicación continuamente aunque la app esté minimizada. Esto es necesario para registrar recorridos de campo en tiempo real. Puedes desactivar este permiso en cualquier momento desde los ajustes de tu dispositivo.

### 1.3 Contenido generado por el usuario
- Fotos adjuntadas a eventos de ruta
- Nombres y descripciones de proyectos, rutas y eventos
- Archivos KML/KMZ importados

### 1.4 Datos técnicos
- Token de notificaciones push (para enviarte alertas de eventos críticos)
- Registros de actividad dentro de la app

---

## 2. Cómo usamos la información

| Dato | Uso |
|------|-----|
| Correo electrónico | Autenticación y recuperación de cuenta |
| Ubicación en primer plano | Navegación en mapa, cálculo de rutas |
| Ubicación en segundo plano | Seguimiento de recorridos de campo |
| Fotos | Documentación de eventos en ruta |
| Token push | Envío de alertas de eventos críticos |

**No vendemos, alquilamos ni compartimos tus datos personales con terceros con fines comerciales.**

---

## 3. Almacenamiento y seguridad

- Los datos se almacenan en servidores seguros de **Supabase** (región us-east-1) con cifrado AES-256 en reposo y TLS en tránsito.
- Las fotos se almacenan en **Supabase Storage** con acceso restringido por proyecto.
- Solo los miembros de tu proyecto pueden ver los datos de ese proyecto.
- Aplicamos Row Level Security (RLS) en la base de datos para garantizar el aislamiento de datos entre proyectos.

---

## 4. Ubicación en segundo plano — Declaración específica

Agris Map solicita el permiso `ACCESS_BACKGROUND_LOCATION` únicamente para la funcionalidad de **seguimiento GPS de recorridos de campo**. Este permiso:

- Se activa solo cuando el usuario lo habilita manualmente desde la pantalla de mapa
- Se desactiva cuando el usuario detiene el seguimiento
- Los datos de ubicación se usan exclusivamente para registrar y visualizar el recorrido dentro de la app
- No se comparten con terceros ni se usan con fines publicitarios

Puedes revocar este permiso en cualquier momento en: **Ajustes del dispositivo → Apps → Agris Map → Permisos → Ubicación → Solo mientras se usa la app**

---

## 5. Compartir datos

Tus datos solo se comparten:
- **Con miembros de tu proyecto:** los colaboradores que invites ven el mapa, eventos y rutas del proyecto compartido.
- **Con proveedores de infraestructura:** Supabase (base de datos y almacenamiento), Expo (notificaciones push). Estos proveedores no tienen acceso a tus datos para sus propios fines.

---

## 6. Retención de datos

- Los datos de tu cuenta se conservan mientras la cuenta esté activa.
- Al eliminar tu cuenta, tus datos personales se eliminan en un plazo de 30 días.
- Las fotos adjuntas a eventos se eliminan junto con el evento o proyecto correspondiente.

---

## 7. Tus derechos

Tienes derecho a:
- **Acceder** a tus datos personales
- **Corregir** información incorrecta
- **Eliminar** tu cuenta y datos asociados
- **Exportar** tus datos en formato KML/KMZ

Para ejercer estos derechos, escríbenos a: **xavierguevara277@gmail.com**

---

## 8. Menores de edad

Agris Map no está dirigida a menores de 13 años. No recopilamos conscientemente datos de menores.

---

## 9. Cambios a esta política

Notificaremos cambios significativos mediante un aviso en la app o por correo electrónico. El uso continuado de la app tras los cambios implica aceptación.

---

## 10. Contacto

**INNOVA 3DR**  
Correo: xavierguevara277@gmail.com  
