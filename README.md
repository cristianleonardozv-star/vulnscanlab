# 🛡️ VulnScan Lab — Detección de Vulnerabilidades en Redes Locales con Kali Linux

> Página web informativa y educativa sobre las principales herramientas de ciberseguridad utilizadas para la detección de vulnerabilidades en redes locales. Todo el contenido está en español y orientado al aprendizaje ético y responsable.

🌐 **Demo en vivo:** [https://cristianleonardozv-star.github.io/vulnscanlab/](https://cristianleonardozv-star.github.io/vulnscanlab/)

---

## 📌 ¿Qué es este proyecto?

VulnScan Lab es una plataforma web **estática, informativa y educativa** que documenta 15 herramientas de ciberseguridad organizadas en 6 categorías. No ejecuta herramientas, no realiza escaneos reales ni procesa datos del usuario — es un recurso pedagógico equivalente a un libro digital interactivo sobre seguridad en redes.

Desarrollado como proyecto académico para la asignatura de redes y seguridad informática.

---

## 🧰 Herramientas Documentadas

| Categoría | Herramientas |
|-----------|-------------|
| 🔍 Reconocimiento | Nmap, Netdiscover |
| 📡 Tráfico de red | Wireshark, Tcpdump |
| 🌐 Seguridad web | Nikto, Burp Suite |
| 🛑 Vulnerabilidades | OpenVAS / GVM |
| 💥 Explotación | Metasploit, Hydra, Sqlmap, Deephat |
| 📶 Wi-Fi | Aircrack-ng |
| 🌐 Redes | Netcat |
| 📊 Monitoreo | Grafana, Zabbix |

---

## 🗂️ Estructura del Proyecto

```
vulnscanlab/
├── index.html          # Página principal (hero, catálogo, glosario, ética)
├── README.md           # Este archivo
└── assets/             # (próximamente) imágenes y recursos
```

> Por ahora el proyecto es un único archivo `index.html` autocontenido. Las páginas individuales de cada herramienta se agregarán en los siguientes avances.

---

## ✨ Funcionalidades Actuales (v2.0)

- [x] Navbar fija con navegación por secciones
- [x] Hero section con terminal animada (demo de Nmap)
- [x] Catálogo de 15 herramientas con tarjetas interactivas
- [x] Filtros por categoría (Reconocimiento, Tráfico, Web, Vulnerabilidades, Explotación, Wi-Fi, Monitoreo)
- [x] Modal con documentación completa de **Nmap** (mini avance)
- [x] Modales informativos para Grafana, Zabbix y Deephat
- [x] Sección "¿Cómo funciona una auditoría?" con pasos metodológicos
- [x] Glosario de términos técnicos
- [x] Sección de ética y marco legal (Ley 1273 de 2009)
- [x] Diseño dark mode completamente responsivo

---

## 🚀 Cómo usar este proyecto

### Ver en línea
Visita directamente: [https://cristianleonardozv-star.github.io/vulnscanlab/](https://cristianleonardozv-star.github.io/vulnscanlab/)

### Ejecutar localmente
No necesita servidor ni dependencias. Solo clona el repositorio y abre el archivo:

```bash
git clone https://github.com/cristianleonardozv-star/vulnscanlab.git
cd vulnscanlab
# Abre index.html en tu navegador
```

O con Live Server en VS Code:
1. Instala la extensión **Live Server**
2. Clic derecho en `index.html` → **Open with Live Server**

---

## 🛠️ Tecnologías Utilizadas

| Tecnología | Uso |
|-----------|-----|
| HTML5 | Estructura y contenido semántico |
| CSS3 | Estilos, dark mode y diseño responsivo |
| JavaScript (ES6+) | Filtros, modales e interactividad |
| Font Awesome 6 | Íconos de herramientas y navegación |
| Google Fonts | Tipografía (Space Grotesk + JetBrains Mono) |
| GitHub Pages | Hosting gratuito y despliegue continuo |

---

## 📅 Estado del Proyecto

```
✅ Fase 1 — Formulación y boceto inicial        [Completado]
✅ Fase 2 — Incorporación de nuevas herramientas [Completado]
🔄 Fase 3 — Páginas individuales por herramienta [En progreso]
⏳ Fase 4 — Diagramas, ejemplos visuales y guías [Pendiente]
⏳ Fase 5 — Pruebas, ajustes finales y entrega   [Pendiente]
```

---

## ⚠️ Aviso de Uso Ético

> Este proyecto tiene **fines exclusivamente educativos**. Toda la información presentada está orientada al aprendizaje del hacking ético y la auditoría de seguridad responsable.
>
> En Colombia, la **Ley 1273 de 2009** tipifica como delito el acceso no autorizado a sistemas informáticos. Las herramientas documentadas en este sitio deben usarse **únicamente en redes propias o con autorización expresa** del propietario.

---

## 👥 Equipo de Desarrollo

| Nombre | Código | Rol |
|--------|--------|-----|
| Michell Mahecha | 1152407 | Líder del proyecto |
| Cristian Zambrano | 1152408 | Desarrollador / Diseñador web |
| Scharid Maldonado | 1152418 | Investigador de contenido |

---

## 📄 Licencia

Proyecto académico — uso educativo. 2026.
