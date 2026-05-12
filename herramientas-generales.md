# Herramientas Generales de OSINT
 
Herramientas de uso general, independientes del contexto geográfico. Ordenadas por categoría.
 
---
 
## Reconocimiento de identidad
 
### Sherlock
Busca un username en cientos de redes sociales y plataformas simultáneamente.
 
- **Tipo:** CLI
- **Costo:** Gratuito
- **Repo:** https://github.com/sherlock-project/sherlock
- **Instalación:**
```bash
pip install sherlock-project
sherlock usuario_objetivo
```
 
---
 
### Holehe
Verifica en qué servicios está registrado un email usando el flujo de recuperación de contraseña — sin alertar al objetivo.
 
- **Tipo:** CLI
- **Costo:** Gratuito
- **Repo:** https://github.com/megadose/holehe
- **Instalación:**
```bash
pip install holehe
holehe objetivo@gmail.com
```
 
---
 
### WhatsMyName
Alternativa a Sherlock con mayor cobertura de plataformas. También tiene interfaz web.
 
- **Tipo:** CLI / Web
- **Costo:** Gratuito
- **Web:** https://whatsmyname.app
- **Repo:** https://github.com/WebBreacher/WhatsMyName
---
 
### Infoga
Recolecta información sobre un email o número de teléfono desde múltiples fuentes públicas: motores de búsqueda, redes sociales, servidores PGP y filtraciones conocidas. Combina en un solo comando lo que otras herramientas hacen por separado.
 
- **Tipo:** CLI
- **Costo:** Gratuito
- **Repo:** https://github.com/m4ll0k/Infoga
- **Instalación:**
```bash
git clone https://github.com/m4ll0k/Infoga.git
cd Infoga && pip install -r requirements.txt
# Consulta por email
python infoga.py --info objetivo@gmail.com --source all
 
# Consulta por número de teléfono
python infoga.py --info +5491100000000 --source all
```
 
---
 
### Have I Been Pwned
Verifica si un email aparece en filtraciones de datos conocidas.
 
- **Tipo:** Web / API
- **Costo:** Gratuito (API con límites)
- **Web:** https://haveibeenpwned.com
---
 
## Metadata y archivos
 
### ExifTool
Extrae y edita metadata de imágenes, videos y documentos. Puede revelar coordenadas GPS, dispositivo usado, fecha y hora de creación.
 
- **Tipo:** CLI
- **Costo:** Gratuito
- **Web:** https://exiftool.org
- **Uso básico:**
```bash
exiftool archivo.jpg
```
 
---
 
## Reconocimiento de infraestructura
 
### Shodan
Motor de búsqueda de dispositivos conectados a internet. Indexa servidores, cámaras, routers y cualquier dispositivo con IP pública.
 
- **Tipo:** Web / API / CLI
- **Costo:** Freemium
- **Web:** https://www.shodan.io
---
 
### crt.sh
Enumera subdominios usando registros públicos de certificados SSL/TLS.
 
- **Tipo:** Web
- **Costo:** Gratuito
- **Web:** https://crt.sh
- **Uso:** `https://crt.sh/?q=dominio.com`
---
 
### theHarvester
Recolecta emails, subdominios, IPs y nombres de empleados desde fuentes públicas.
 
- **Tipo:** CLI
- **Costo:** Gratuito
- **Repo:** https://github.com/laramies/theHarvester
- **Uso básico:**
```bash
theHarvester -d dominio.com -b google
```
 
---
 
### ViewDNS / DNSDumpster
Consulta registros DNS, WHOIS histórico y relaciones entre dominios.
 
- **Tipo:** Web
- **Costo:** Gratuito
- **Web:** https://viewdns.info · https://dnsdumpster.com
---
 
## Google Dorks — referencia rápida
 
```
"nombre apellido" filetype:pdf
site:linkedin.com "nombre objetivo"
intext:"@empresa.com" filetype:xls
intitle:"index of" "passwords"
"@gmail.com" site:github.com
```
 
Referencia completa: https://www.exploit-db.com/google-hacking-database
 
---
 
## Visualización y análisis
 
### Maltego CE
Herramienta de visualización de relaciones entre entidades (personas, dominios, IPs, emails). La versión Community Edition es gratuita con algunas limitaciones.
 
- **Tipo:** GUI
- **Costo:** Freemium
- **Web:** https://www.maltego.com
---
 
## Identidades ficticias (Sockpuppets)
 
### This Person Does Not Exist
Genera fotos de personas que no existen usando redes generativas. Útil para crear sockpuppets con foto de perfil no rastreable.
 
- **Tipo:** Web
- **Costo:** Gratuito
- **Web:** https://thispersondoesnotexist.com
