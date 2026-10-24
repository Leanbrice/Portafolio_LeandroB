# Portafolio · Leandro Briceño

Sitio personal de **Leandro Agustín Briceño**, estudiante de Desarrollo de Software (último año) con foco en backend con Python, Flask y MySQL.
Reúne mis servicios, herramientas, proyectos y una página con mi currículum.

## Qué incluye

- **Portafolio** (`/`): presentación, servicios, herramientas, proyectos y contacto.
- **Currículum** (`/cv`): CV de una hoja A4 con estudios, capacitaciones, proyectos con sus lenguajes y habilidades.
  Para guardarlo en PDF: abrir `/cv`, imprimir (Ctrl+P) y elegir *Guardar como PDF*.

## Proyectos destacados

| Proyecto | Lenguajes |
|---|---|
| [IMPULSAR](https://github.com/ImpulsarApp/impulsar) | Python, JavaScript, TypeScript, HTML, CSS, MySQL |
| [AsisTO](https://github.com/Hutchy147/asisto) | Python, JavaScript, SQL, MySQL |
| [Sistema de gestión para farmacia](https://github.com/Toomasmg/gestion_farmacia_programacion) | TypeScript, CSS, MySQL, Docker |
| [API Mundial de Árbitros 2026](https://github.com/Franv-Dev/programacion3_mundial_arbitros) | Python, JavaScript, MySQL, CSS |

## Tecnologías

- **Backend:** Python, Flask, SQLAlchemy, NestJS, JWT, Jinja2
- **Frontend:** HTML, CSS, JavaScript, TypeScript, React, Vite
- **Base de datos y otras:** MySQL, Docker, Git y GitHub

## Estructura

```text
.
├── app.py              # Aplicación Flask y rutas (/ y /cv)
├── requirements.txt    # Dependencias
├── templates/
│   ├── index.html      # Portafolio
│   └── cv.html         # Currículum
└── static/
    ├── style.css       # Estilos del portafolio
    ├── cv.css          # Estilos del CV (formato A4 e impresión)
    └── *.png / *.jpeg  # Imágenes y logos
```

## Cómo ejecutarlo

```bash
git clone https://github.com/Leanbrice/Portafolio_LeandroB.git
cd Portafolio_LeandroB

python -m venv venv
source venv/bin/activate        # En Windows: venv\Scripts\activate
pip install -r requirements.txt

python app.py
```

Después abrir <http://127.0.0.1:5000> para el portafolio y <http://127.0.0.1:5000/cv> para el CV.

## Contacto

- Email: leagustin9@gmail.com
- GitHub: [Leanbrice](https://github.com/Leanbrice)
- LinkedIn: [Leandro Briceño](https://linkedin.com/in/leandro-briceño-9998a9370/)
