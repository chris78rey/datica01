# CV — Christian Ruiz | Analista de Datos Senior

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Enabled-green)](https://chris78rey.github.io/datica01/)
[![HTML5](https://img.shields.io/badge/HTML5-Valid-orange)](https://validator.w3.org/)
[![License](https://img.shields.io/badge/License-MIT-blue)](#licencia)

CV interactivo, responsive y autocontenido de **Christian Ruiz**, Analista de Datos Senior con 6+ años de experiencia en pipelines, modelado y visualización de datos.

## 🚀 Características

- ✅ **HTML válido y semántico** — Sin dependencias externas
- 🌓 **Tema claro/oscuro** — Con persistencia en localStorage
- 📱 **Responsive** — Optimizado para móvil, tablet y desktop
- 🎨 **Diseño moderno** — Gradientes, iconos y animaciones sutiles
- 🔍 **Navegación fluida** — Scroll suave entre secciones
- 🏆 **Contenido completo** — Experiencia, proyectos, certificaciones, habilidades
- 📊 **Gráficos de habilidades** — Barras animadas de competencia
- 🖨️ **Listo para imprimir** — Estilos optimizados para PDF

## 📋 Secciones

1. **Resumen Profesional** — Presentación ejecutiva con métricas de impacto
2. **Experiencia** — 3 roles con detalles de tecnologías y logros
3. **Proyectos Destacados** — 4 casos de éxito con impacto cuantificado
4. **Habilidades Técnicas** — Gráficos de competencia y herramientas
5. **Formación** — Educación formal y certificaciones
6. **Contacto** — Enlaces a correo, teléfono, LinkedIn y GitHub

## 🛠️ Tecnologías

**Stack del CV:**
- `HTML5` — Estructura semántica
- `CSS3` — Grid, Flexbox, Gradientes, Animaciones
- `Vanilla JavaScript` — Tema dinámico, navegación, scroll suave

**Tecnologías en el CV:**
- Python (Pandas, NumPy, scikit-learn)
- KNIME (ETL, Validaciones, Reporting)
- SQL (Oracle, PostgreSQL)
- Power BI & Tableau
- APIs REST, Git, Excel avanzado

## 📦 Instalación & Uso

### Opción 1: Abrir localmente
```bash
# Clonar el repositorio
git clone https://github.com/chris78rey/datica01.git
cd datica01

# Abrir en navegador
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

### Opción 2: Ver en línea
Visita: **https://chris78rey.github.io/datica01/**

## 🎯 Características de Interacción

### Navegación entre secciones
- Botones en el header para ir a cada sección
- Indicador visual de sección activa
- Scroll suave automático

### Tema dinámico
- Click en el botón 🌙/☀️ para cambiar tema
- Preferencia guardada en localStorage
- Transiciones suave entre temas

### Responsive
- Se adapta automáticamente a:
  - Mobile (< 640px)
  - Tablet (640px - 840px)
  - Desktop (> 840px)

## 📈 Métricas & Impacto

| Métrica | Valor |
|---------|-------|
| Reducción de OOS | -22% |
| Tiempo de cierre | 80% menos (2 días → 4 horas) |
| Validaciones de calidad | 18 checks |
| Empresas atendidas | 3+ |
| Años de experiencia | 6+ |

## 📧 Contacto

- **Correo:** contacto.christianruiz+cv@datica.local
- **Teléfono:** (+57) 300 000 0000
- **LinkedIn:** [/christianruiz-analista](https://linkedin.com/in/christianruiz-analista)
- **GitHub:** [/chruiz-data](https://github.com/chruiz-data)

## 🔧 Personalizacion

Para adaptar este CV a tu perfil:

1. **Editar información personal** en el `<header>`
   ```html
   <div class="name">Tu Nombre</div>
   <div class="role">Tu Rol</div>
   ```

2. **Cambiar experiencia** — Modifica las secciones `<article class="item">`

3. **Actualizar habilidades** — Cambia los porcentajes en `.skill-fill`
   ```html
   <div class="skill-fill" style="width: 88%;"></div>
   ```

4. **Agregar/quitar proyectos** — Duplica o elimina `.project-card`

5. **Modificar colores** — Edita las variables CSS en `:root`
   ```css
   --primary: #0ea5e9;
   --accent: #7c3aed;
   ```

## 🎨 Paleta de Colores

**Modo Claro:**
- Background: #ffffff
- Text: #0f172a
- Primary: #0ea5e9 (Cyan)
- Accent: #7c3aed (Violet)

**Modo Oscuro:**
- Background: #0b1220
- Text: #e5e7eb
- Primary: #0ea5e9
- Accent: #7c3aed

## 📄 Exportar a PDF

### Desde navegador:
1. Abre el CV en tu navegador
2. Presiona `Ctrl+P` (Windows) o `Cmd+P` (Mac)
3. Selecciona "Guardar como PDF"
4. Ajusta márgenes según necesites

### Recomendaciones:
- Usa el tema **claro** para mejor impresión
- Márgenes: 10-15mm
- Formato: A4
- Escala: 100%

## 🚀 Desplegar en GitHub Pages

```bash
# El repositorio ya está configurado para GitHub Pages
# El CV se despliega automáticamente en:
# https://chris78rey.github.io/datica01/

# Para actualizar:
git add .
git commit -m "tu mensaje"
git push origin main
```

## 📋 Estructura del Proyecto

```
datica01/
├── index.html           # CV completo (HTML + CSS + JS)
├── README.md            # Este archivo
├── docker-compose.yml   # (Opcional) Para servir localmente
├── url.md               # URL del repositorio
└── crea.md              # Notas de creación
```

## 📝 Mejoras Futuras

- [ ] Agregar foto/avatar real como data:image
- [ ] Descargar CV en PDF desde botón
- [ ] Sección "Timeline" de carrera
- [ ] Integración con Calendly para agendar
- [ ] QR para compartir contacto rápidamente
- [ ] Versión multilengua (ES/EN)
- [ ] Dark mode refinado con más contrastes
- [ ] Portafolio interactivo de proyectos
- [ ] Blog integrado
- [ ] Analytics con Google Analytics

## 🤝 Contribuir

Si encuentras un bug o tienes una sugerencia:

1. Fork el repositorio
2. Crea una rama: `git checkout -b mejora/mi-mejora`
3. Commit: `git commit -m "feat: agregar mejora"`
4. Push: `git push origin mejora/mi-mejora`
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la licencia **MIT**. Eres libre de usar, modificar y distribuir este CV siempre que incluyas la atribución original.

## 🙏 Agradecimientos

- Inspiración en CVs modernos y minimalistas
- Iconos en emoji (Unicode)
- Paleta de colores basada en Tailwind CSS

---

**Última actualización:** 2024  
**Autor:** Christian Ruiz  
**GitHub:** [chris78rey](https://github.com/chris78rey)