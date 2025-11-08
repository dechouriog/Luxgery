
# Luxgery - Django informational site (minimal)

Proyecto Django minimalista para mostrar información de una clínica/servicio médico.
- Django app: `web`
- Páginas: inicio, servicios, about, testimonios, contacto
- Sin modelos ni formulario funcional

## Uso

1. Crear y activar un virtualenv
2. Instalar Django: `pip install django`
3. Ejecutar:
```bash
python manage.py migrate
python manage.py runserver
```

Abre http://127.0.0.1:8000/


Deployment

The Luxgery project was deployed using Render, a cloud platform that simplifies the deployment of web applications built with Django.
The deployment process included setting up the production environment, configuring static files, applying database migrations, and defining environment variables for email and localization settings.
The live version of the application can be accessed through the public Render URL, allowing users to interact with the multilingual interface and test the core functionalities of the MVP in a production-ready environment.

https://luxgery.com/en/
