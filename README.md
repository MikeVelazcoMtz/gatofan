# gatofan
A fanpage for kitten lovers :)

## Instalación

*    Se descarga y descomprime el [repositorio](https://github.com/MikeVelazcoMtz/gatofan/archive/master.zip).
*    Se instalan los paquetes necesarios (`pip install -r requirements.txt`).
*    Crea una base de datos MySQL llamada 'gatofan'.
*    Se pobla la base de datos (`python manage.py migrate`).
*    Se crea el superusuario (`python manage.py syncdb`).

>Notas adicionales:
>
>   En la carpeta **templates** hay un template llamado **base.html** el 
>   cual ya carga con [Bootstrap](http://getbootstrap.com) (por medio de [django-bootstrap3](https://github.com/dyve/django-bootstrap3), [Documentación](http://django-bootstrap3.readthedocs.org/))
>   . Es recomendable agregar las apps en la carpeta **apps**.


