# Detector de Enlaces Rotos y Errores 404

[![Detector Enlaces Rotos](https://img.shields.io/badge/TAVARDT-Broken%20Links-5b3cf5.svg)](https://tools.tavardt.com/es/detector-enlaces-rotos/)
[![Jurisdiccion](https://img.shields.io/badge/Jurisdiccion-Espana-00C853.svg)](https://ag.tavardt.com/es/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Auditoria tecnica de hipervinculos internos y externos, codigos de estado HTTP y experiencia de navegacion.

Desarrollado y mantenido por el equipo de calidad tecnica y SEO de **[TAVARDT Espana](https://ag.tavardt.com/es/)**.

---

## Capacidades de Deteccion de Enlaces Rotos

* **Rastreo Completo de Enlaces**: Identificacion automatica de hipervinculos internos y salientes en codigo HTML.
* **Deteccion de Errores 404 y 410**: Localizacion precisa de paginas no encontradas o recursos eliminados.
* **Optimizacion del Presupuesto de Rastreo**: Prevencion de redireccionamientos invalidos y desgaste de recursos en motores de busqueda.
* **Comprobacion de Protocolo Seguro**: Alerta de referencias mixtas o enlaces que degradan de HTTPS a HTTP.
* **Indice de Integridad de Enlaces**: Evaluacion cuantitativa de 0 a 100 con inventario de URLs fallidas.

---

## Instalacion y Ejecucion

Compatible con Python 3.8 o superior sin necesidad de dependencias externas.

```bash
git clone https://github.com/TAVARDT-Espana/broken-links-checker-es.git
cd broken-links-checker-es
python broken_links_scanner.py https://empresa.es
```

Para generar la salida en formato JSON:

```bash
python broken_links_scanner.py https://empresa.es --json
```

---

## Plataforma Web Oficial

Para realizar auditorias continuas de enlaces rotos en la nube:

* **[Detector de Enlaces Rotos Oficial](https://tools.tavardt.com/es/detector-enlaces-rotos/)**
* **[Portal Corporativo TAVARDT Espana](https://ag.tavardt.com/es/)**

---

## Asistencia Tecnica y Auditoria SEO

Para proyectos integrales de saneamiento web conforme a Directrices de Calidad Web de la UE y Estandares W3C, consulte a **[TAVARDT Espana](https://ag.tavardt.com/es/contacto/)**.
