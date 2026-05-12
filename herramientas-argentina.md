# Herramientas y Fuentes — Contexto Argentino

Fuentes de información pública y herramientas específicamente útiles para investigaciones OSINT en Argentina (Principalmente CABA y Provincia de Buenos Aires).

> Toda la información listada acá es de acceso público. Su uso debe enmarcarse dentro de la **Ley 25.326** de Protección de Datos Personales y la **Ley 26.388** de Delitos Informáticos.

---

## Identidad y datos fiscales

### AFIP — Consulta de empresas y monotributistas
Permite ver la categoría de monotributo, actividades declaradas y estado ante AFIP de personas y empresas.

- **Web:** https://seti.afip.gob.ar/padron-puc-constancia-internet/ConsultaConstanciaAction.do

---

### AGIP — Administración Gubernamental de Ingresos Públicos (CABA)
Permite consultar el estado tributario de contribuyentes de la Ciudad de Buenos Aires. Útil para cruzar datos de personas o empresas que operan en CABA.

- **Web:** https://agip.gob.ar
- **Qué devuelve:** estado de inscripción, actividades, deudas publicadas

---

### CUIT Online
Agregador que cruza datos de AFIP, Boletín Oficial y otras fuentes públicas para construir un perfil básico a partir de un CUIT/CUIL. No es una fuente oficial pero consolida información útil rápidamente.

- **Web:** https://www.cuitonline.com
- **Qué devuelve:** nombre, actividad, domicilio fiscal, historial de cambios, relaciones societarias

---

## Agregadores de datos personales

### Dateas
Agrega información de múltiples fuentes públicas argentinas. Permite buscar por nombre, DNI, CUIT, teléfono o dirección. Es un ejemplo concreto de cómo los data brokers consolidan información pública.

- **Web:** https://www.dateas.com
- **Qué devuelve:** datos personales, vínculos societarios, historial de domicilios, teléfonos
- **Nota:** requiere registro para acceso completo — fuente semi-abierta

---

### Páginas Blancas
Directorio de personas y empresas de Argentina. Permite buscar por nombre y obtener teléfonos y domicilios registrados.

- **Web:** https://www.paginasblancas.com.ar
- **Qué devuelve:** teléfono, domicilio, localidad
- **Nota:** los datos pueden estar desactualizados; útil para validar o contrastar con otras fuentes

---

### Tirr.app
Herramienta orientada a inteligencia sobre personas jurídicas y físicas en Argentina. Cruza fuentes públicas y permite visualizar relaciones entre personas, empresas y domicilios.

- **Web:** https://tirr.app
- **Qué devuelve:** vínculos societarios, socios, cargos, domicilios, historial
- **Nota:** interfaz más moderna que otras opciones locales; útil para mapear estructuras empresariales

---

## Vehículos y patentes

### Consulta de patentes — Provincia de Buenos Aires
Permite consultar datos del titular de un vehículo a partir de la patente. Devuelve nombre del titular, tipo de vehículo y estado de deudas.

- **Web:** https://www.arba.gov.ar (Provincia)
- **Web:** https://agip.gob.ar (Capital)
- **Nota importante:** **la disponibilidad y el nivel de detalle de esta consulta depende de la provincia.** Cada jurisdicción gestiona su propio registro automotor.

---

## Registros públicos

### Boletín Oficial de la República Argentina
Publicación oficial del Estado. Contiene resoluciones, decretos, designaciones, licitaciones, contratos y sociedades comerciales.

- **Web:** https://www.boletinoficial.gob.ar
- **Casos de uso:** buscar nombramientos de funcionarios, creación de empresas, contratos estatales

---

### Justicia Legis — Poder Judicial de la Nación
Permite consultar causas judiciales con acceso público del fuero federal.

- **Web:** https://www.pjn.gov.ar

---

### Infojus
Base de datos de jurisprudencia y normativa argentina.

- **Web:** http://www.infojus.gob.ar
- **Casos de uso:** buscar sentencias, leyes, decretos y resoluciones

---

## Sociedades y empresas
 
### Registro Nacional de Sociedades (RNS)
Registro nacional que centraliza información de todas las sociedades del país, incluyendo las constituidas en el exterior que operan en Argentina. Depende del Ministerio de Justicia.
 
- **Web:** https://www.argentina.gob.ar/justicia/registro-nacional-sociedades
- **Qué devuelve:** datos de inscripción, estatutos, representantes legales, filiales extranjeras

---

## Dominios y registros web

### NIC Argentina — WHOIS de dominios .ar
Consulta información de registro de dominios `.ar`, incluyendo titular, fecha de registro y estado.

- **Web:** https://nic.ar
- **WHOIS directo:** https://nic.ar/buscar-dominio

---

### Portal de Datos Abiertos
Datasets públicos del Estado Nacional, incluyendo nóminas de empleados públicos, presupuesto y contratos.

- **Web:** https://datos.gob.ar

---

## Notas sobre privacidad y uso

- El hecho de que una fuente sea pública no autoriza cualquier uso de la información
- La **Ley 25.326** protege el tratamiento de datos personales aunque sean de fuente abierta
- Para investigaciones profesionales, documentar el fin y el scope antes de iniciar
- Ante dudas sobre la legalidad de una consulta, consultar con un profesional del derecho antes de proceder
