# Fluira — privacidad y soporte

Sitio estático localizado para las URL de privacidad y soporte de Fluira 1.0.
No usa cookies, analítica, fuentes remotas ni JavaScript. El diseño reproduce la
atmósfera de Fluira con CSS propio y recursos del sistema.

## Rutas

| Idioma | Privacidad | Soporte |
|---|---|---|
| Inglés | `/en/privacy.html` | `/en/support.html` |
| Español | `/es/privacy.html` | `/es/support.html` |
| Francés | `/fr/privacy.html` | `/fr/support.html` |
| Alemán | `/de/privacy.html` | `/de/support.html` |

`index.html` ofrece selección manual de idioma. No detecta, registra ni conserva
la preferencia de la persona.

## Datos públicos confirmados

- Base HTTPS prevista: `https://agmstudio.github.io/fluira-support`.
- Canal público de soporte y privacidad:
  `https://github.com/AGMStudio/fluira-support/issues/new`.
- Email público de soporte y privacidad: `adrigm.admin@gmail.com`.
- Titular público: `Adrian Guerra Marrero`.
- Copyright de la ficha: `2026 Adrian Guerra Marrero`.

GitHub Issues muestra las consultas públicamente, por lo que todas las páginas
avisan de no incluir títulos, notas, historial, copias u otros datos sensibles.
El email de soporte se publica con autorización expresa. El teléfono y la
dirección, así como el contacto privado de App Review, no forman parte de este
sitio.

## Publicación

Publicar únicamente estos archivos estáticos mediante un host HTTPS. Si se usa
GitHub Pages, emplear despliegue desde la rama predeterminada y no GitHub Actions.
El repositorio público no debe incluir código de la app, archives, credenciales,
capturas sin revisar ni datos de usuarios.

Antes de cada versión:

1. Contrastar la política con el archive exacto y sus PrivacyInfo.
2. Verificar que todos los enlaces y alternates respondan por HTTPS.
3. Ejecutar una captura dinámica de red y revisar cualquier servicio nuevo.
4. Revisar legalmente los datos del responsable y las obligaciones territoriales.
5. Obtener revisión lingüística humana para los cuatro idiomas.

## Fuente de verdad

- `README.md`, sección Privacidad y seguridad.
- `PLAN.md`, contratos de privacidad, companions y fase 13.
- Los cuatro `PrivacyInfo.xcprivacy`.
- Implementación de persistencia, portabilidad, notificaciones locales,
  App Groups, ActivityKit, WidgetKit y WatchConnectivity.

Última revisión técnica del borrador: 27 de agosto de 2026.
