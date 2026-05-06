# Green Selva S.A.C — Sitio Web Corporativo

Desarrollo y optimización del sitio web oficial de Green Selva S.A.C. Proyecto freelance realizado en enero de 2026.

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

### Rendimiento crítico
El sitio tenía un score de **29/100 en Google PageSpeed Insights**.
Imágenes sin optimizar de hasta 73MB (el estándar es <0.7MB) 
colapsaban el servidor.

**Resultado: Score mejorado de 29 → 61 (+110%)** mediante:
- Compresión y reemplazo de imágenes pesadas
- Aumento del memory_limit PHP desde el panel de hosting
- Eliminación de plugins innecesarios que ralentizaban la carga
## 📸 Capturas

**Algunas imágenes pesaban 63 MB, lo cual es excesivo para la web.**

<img width="1361" height="645" alt="WhatsApp Image 2026-05-05 at 11 20 40 PM" src="https://github.com/user-attachments/assets/99a0f626-91d6-4b3a-a8a7-a59d2659b5be" />

**Optimiza las imágenes para que pesen menos en la web.**

<img width="1365" height="661" alt="WhatsApp Image 2026-05-05 at 11 20 11 PM" src="https://github.com/user-attachments/assets/d827d634-87d2-44f1-959c-9f1087de7d29" />

**pageSpeed anterior**

<img width="1299" height="494" alt="WhatsApp Image 2026-05-05 at 11 21 22 PM" src="https://github.com/user-attachments/assets/3c5a92e4-60c5-4dc5-8ed7-47d38d6d34fb" />

**pageSpeed actual**

<img width="1369" height="726" alt="WhatsApp Image 2026-05-05 at 11 21 54 PM" src="https://github.com/user-attachments/assets/7b66e510-b627-4385-b95b-c34de544f7b3" />

