# GUÍA PRÁCTICA DE PUBLICACIÓN Y HOSPEDAJE WEB
## LEGAL TECH OAXACA · FIRMA LEGAL DIGITAL
**Titular:** Lic. Daniel Carrasco Enríquez · **Cédula Profesional:** 14971373  
**Archivos listos para producción:** `index.html` y `legal_tech_banner.jpg`  

---

## 1. Dónde publicar la página (Opciones recomendadas)

Para poner en línea el portal de **Legal Tech Oaxaca** de inmediato y con máxima seguridad, existen tres vías principales:

### Opción 1: Vercel o Netlify (La más rápida y moderna — Gratuita)
* **¿Por qué conviene?:** Publicación en menos de 1 minuto, servidores de alta velocidad (CDN global), certificado de seguridad SSL (HTTPS) automático y vinculación sin costo a su propio dominio (`legaltechoaxaca.com` o `.mx`).
* **Pasos:**
  1. Ingrese a [vercel.com](https://vercel.com) o [netlify.com](https://netlify.com) y cree una cuenta con su correo `Dacaen99@gmail.com`.
  2. Arrastre la carpeta que contiene `index.html` y `legal_tech_banner.jpg` al área de "Deploy".
  3. El sistema le entregará una URL pública instantánea (ej. `legaltechoaxaca.vercel.app`).
  4. En la sección *Settings > Domains*, puede conectar su dominio propio (`legaltechoaxaca.com`).

---

### Opción 2: GitHub Pages (100% Gratuito y Perpetuo)
* **¿Por qué conviene?:** Ideal para proyectos institucionales de firmas y tecnología legal. Sin costos mensuales de hosting.
* **Pasos:**
  1. Cree un repositorio en GitHub llamado `legaltechoaxaca.github.io` o `portal-legal`.
  2. Suba los archivos `index.html` y `legal_tech_banner.jpg`.
  3. Vaya a *Settings > Pages* y active la rama `main`.
  4. Su sitio quedará publicado de inmediato bajo HTTPS con soporte para dominio personalizado.

---

### Opción 3: Hosting Tradicional con cPanel (Hostinger, GoDaddy, Neolo, etc.)
* **¿Por qué conviene?:** Si usted ya cuenta con un servicio de hosting contratado con correos corporativos (ej. `@legaltechoaxaca.com`).
* **Pasos:**
  1. Ingrese al panel cPanel de su proveedor de hospedaje.
  2. Abra el **Administrador de Archivos** (*File Manager*) y diríjase a la carpeta raíz `public_html`.
  3. Suba el archivo `index.html` y la imagen `legal_tech_banner.jpg`.
  4. Su página web estará disponible de inmediato en su dirección www.

---

## 2. Verificación de Normativas de Internet Cumplidas en la Página

El archivo `index.html` ya contiene todos los estándares legales y técnicos exigidos para su publicación pública en México y a nivel internacional:

1. **Aviso de Privacidad Integral Visible y en Modal:**
   - Cumple con la *Ley Federal de Protección de Datos Personales en Posesión de los Particulares (LFPDPPP)*.
   - Tratamiento de datos sensibles con secrecía profesional y canal de derechos ARCO a `Dacaen99@gmail.com`.
2. **Términos y Condiciones de Uso del Portal:**
   - Delimitación de responsabilidad: la consulta y uso de calculadoras no sustituye la relación formal de patrocinio judicial hasta la suscripción del contrato de servicios.
   - Definición legal de la obligación de medios conforme al Código Civil y ética de la Barra Mexicana de Abogados.
3. **Banner y Política de Cookies Técnicas:**
   - Barra flotante de aceptación de cookies técnicas para garantizar consentimiento informado.
4. **Metadatos SEO y Etiquetas Open Graph para Redes Sociales:**
   - Cuando usted comparta el enlace por WhatsApp, Facebook o LinkedIn, se desplegará automáticamente la imagen institucional de la firma, el título profesional y la descripción ejecutiva.
5. **Canales de Contacto Directo:**
   - Botones flotantes fijos en pantalla para llamadas inmediatas (`tel:+529519408062`) y chat de WhatsApp con el titular (`https://wa.me/529519408062`).
   - Enlace directo a BúhoLegal / Registro Nacional de Profesionistas para verificación de la Cédula 14971373.

---

## 3. Acciones Finales para Posicionamiento Local en Oaxaca

Una vez publicada la página en su dominio:
1. **Google Business Profile (Ficha en Google Maps):** Ingrese a Google Perfil de Negocio y coloque el enlace de la página web en la ficha de **Legal Tech Oaxaca (Oaxaca de Juárez, Oaxaca)**.
2. **Redes Sociales:** Agregue el enlace web en las biografías de LinkedIn, Facebook, Instagram y X de la firma.

---

## 4. Configuración de Seguridad, Acceso Admin y 2FA Google Authenticator

Para ingresar al **Panel de Administración Privado (`🔒 Panel Admin`)** y publicar sentencias, fotos o videos:

### Credenciales Oficiales del Titular
* **Usuario / Correo:** `dacaen99@gmail.com`
* **Contraseña Maestra:** `951D303eres.9999`
* **Segundo Factor de Autenticación (Google Authenticator):**
  1. Descargue o abra la app **Google Authenticator** en su teléfono celular.
  2. Pulse el símbolo **"+"** y seleccione **"Introducir clave de configuración"**.
  3. Nombre de la cuenta: `Legal Tech Oaxaca`
  4. Clave secreta (Key): `LEGALTECHOAXACA99` (Tipo: Basada en tiempo / TOTP).
  5. Ingrese el código dinámico de 6 dígitos que genera la app.
  6. *(Código de Respaldo de Emergencia en caso de extravío de teléfono: `951940`)*.

### Auditoría y Blindaje de Vulnerabilidades Implementado
1. **Protección Criptográfica de Contraseña:** La contraseña no se almacena en texto plano en el código; se valida mediante **hash unidireccional SHA-256** mediante la Web Crypto API nativa.
2. **Defensa Anti-Fuerza Bruta:** El sistema bloquea automáticamente los intentos de inicio de sesión durante 5 minutos si se registran 5 intentos fallidos consecutivos.
3. **Sanitización Estricta contra XSS (Cross-Site Scripting):** Todos los textos de contratos, publicaciones y dictámenes son procesados mediante funciones de escape HTML antes de su renderizado en el navegador.
4. **Content Security Policy (CSP):** Se integraron directivas que restringen la inyección de scripts externos maliciosos.

---

## 5. Escaneo Directo de Código QR con Google Authenticator

El Panel de Administración (`🔒 Panel Admin`) ahora muestra de forma permanente y destacada el **Código QR oficial** para vincular en 3 segundos su dispositivo:

1. **Abrir App:** Abra **Google Authenticator** en su teléfono móvil (Android o iOS).
2. **Escanear:** Presione el botón **"+"** en la esquina inferior y seleccione **"Escanear código QR"**.
3. **Apuntar al Monitor:** Enfoque el recuadro con el código QR que aparece en la pantalla del Panel Admin.
4. **Listo:** La app añadirá de inmediato:
   - **Emisor:** `Legal Tech Oaxaca`
   - **Cuenta:** `dacaen99@gmail.com`
   - **Clave Secreta RFC 3548 Base32:** `LEGALTECHOAXACAA`
   - **Código Temporal:** 6 dígitos sincronizados cada 30 segundos.
5. **Acceso de Emergencia:** Si por cualquier motivo no tiene su celular cerca, el código de contingencia de rescate es `951940`.
