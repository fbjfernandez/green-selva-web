# Green Selva S.A.C — Sitio Web Corporativo

Green Selva S.A.C. es una empresa del sector Inmobiliario.
Se me contrató como freelance para desarrollar y optimizar su sitio 
web corporativo desde cero.

**Rol:** Desarrollador Web Freelance  
**Año:** 2026  
**Estado:** Entregado ✅

## LINK DE LA WEB
https://sumaknature.com

## 🛠 Tecnologías usadas
- WordPress + Breakdance (page builder)
- PHP (configuración vía hosting)
- HTML / CSS personalizado
- Optimización de imágenes y caché

## ⚙️ Problemas resueltos

### Errores de servidor (500 / 403)
El servidor colapsaba al intentar cargar o subir imágenes por 
sobrecarga de memoria.

**Solución:** Aumento del memory_limit en php.ini desde el hosting, 
identificación y eliminación de plugins en conflicto.

### Salud del sitio
El panel de WordPress marcaba 2 errores críticos y 6 advertencias.

**Solución:** Diagnóstico y resolución de todos los errores desde 
el panel de salud del sitio.

## 📱 Diseño Responsivo
El cliente entregó únicamente el diseño para versión desktop. 
La versión móvil fue diseñada de forma independiente, adaptando 
la estructura y componentes visuales para garantizar usabilidad 
en todos los dispositivos.

## ⚡ Rendimiento
El sitio tenía un score de **29/100 en Google PageSpeed Insights**.
Imágenes sin optimizar de hasta 73MB (el estándar es <0.7MB) 
colapsaban el servidor.

**Resultado: Score mejorado de 29 → 61 (+110%)** en el momento 
de la optimización. Score actual variable debido a que el equipo 
de marketing continúa subiendo imágenes sin comprimir post-entrega.

> 💡 Nota técnica: Se recomendó al cliente implementar un plugin 
> de compresión automática (como ShortPixel o Smush) para mantener 
> el rendimiento sin depender de optimización manual.

## 📸 Capturas

**Antes: Imágenes sin optimizar (63MB)**

<img width="1361" height="645" alt="WhatsApp Image 2026-05-05 at 11 20 40 PM" src="https://github.com/user-attachments/assets/99a0f626-91d6-4b3a-a8a7-a59d2659b5be" />

**Después: Imágenes comprimidas**

<img width="1365" height="661" alt="WhatsApp Image 2026-05-05 at 11 20 11 PM" src="https://github.com/user-attachments/assets/d827d634-87d2-44f1-959c-9f1087de7d29" />

**PageSpeed antes de optimización: 29/100**

<img width="1299" height="494" alt="WhatsApp Image 2026-05-05 at 11 21 22 PM" src="https://github.com/user-attachments/assets/3c5a92e4-60c5-4dc5-8ed7-47d38d6d34fb" />

**PageSpeed después de optimización: 61/100**

<img width="1369" height="726" alt="WhatsApp Image 2026-05-05 at 11 21 54 PM" src="https://github.com/user-attachments/assets/7b66e510-b627-4385-b95b-c34de544f7b3" />

## 📚 Lo que aprendí

- **WordPress desde cero en entorno real:** Este fue mi primer proyecto 
  con WordPress. Aprendí a manejarlo directamente en producción, con 
  un cliente real y problemas reales que resolver.

- **Diagnóstico de rendimiento web** con Google PageSpeed Insights, 
  identificando cuellos de botella como imágenes sobredimensionadas 
  (hasta 73MB cuando el estándar es <0.7MB).

- **Configuración de servidor PHP** desde el panel de hosting: ajuste 
  de memory_limit para resolver errores 500/403 por sobrecarga de memoria.

- **Gestión de plugins en WordPress:** auditoría, identificación de 
  conflictos y limpieza de plugins innecesarios que afectaban 
  el rendimiento.

- **Diseño responsivo autónomo:** adaptar una interfaz desktop a móvil 
  sin guía del cliente, tomando decisiones de diseño de forma independiente.

- **Comunicación con cliente:** identificar un problema técnico complejo 
  (imágenes pesadas) y explicarlo en términos simples para que el equipo 
  no técnico lo entendiera.

- **Mantenimiento post-entrega:** aprendí que el trabajo no termina 
  con la entrega — el equipo del cliente siguió subiendo imágenes sin 
  comprimir, lo que me llevó a recomendar una solución automática 
  (plugin de compresión) para que el rendimiento se mantuviera sin 
  intervención técnica constante.
