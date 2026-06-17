# KAIST Digital Serendipity

A **Flask + Material Design Bootstrap** web-application prototype for a *Digital Serendipity*
project — an HCI exploration of designing interfaces that foster **serendipitous discovery**
(surfacing unexpected-yet-relevant content/encounters).

> **Status:** early-stage prototype / scaffold. The front-end theme and project skeleton are
> in place; application routes are still minimal placeholders.

## Repository structure

```
KAIST_Digital_Serendipity/
├── start_flask.py                      # Entry point — runs the Flask dev server (host 0.0.0.0)
└── Application_Flask/
    ├── __init__.py                     # Flask app + route definitions
    ├── templates/
    │   └── home-page.html              # Landing page (Material Design Bootstrap layout)
    └── static/                         # MDB (Material Design Bootstrap) assets
        ├── css/                        #   Bootstrap + MDB stylesheets
        ├── js/                         #   Bootstrap + MDB scripts
        ├── font/ , img/                #   Roboto fonts, icons, images
```

## Tech stack

- **Python** + **Flask** (server, routing, Jinja2 templates)
- **MDB — Material Design Bootstrap** (Bootstrap 4 + Material Design UI kit)
- jQuery, Font Awesome

## Getting started

```bash
pip install flask
python start_flask.py
```

Then open <http://localhost:5000/> in your browser.

Current routes (in `Application_Flask/__init__.py`):

| Route | Response |
|-------|----------|
| `/`   | placeholder greeting |
| `/gg` | placeholder greeting (demonstrates Flask's request-context `g`) |

The `home-page.html` template (titled *Digital Serendipity*) provides the intended landing-page
UI and is the starting point for wiring up the application views.

## Related

- **KAIST_Prototype_DigitalSerendipity** — front-end (CSS) prototype for the same project.

---

*KAIST project — a Flask-based prototype exploring digital serendipity in HCI.*
