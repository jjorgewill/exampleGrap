# exampleGrap

Este es un ejemplo de integracion de graphene
Esta plantilla integra la configuracion basica para el desarrollo de backend con django-graphene 

#configuracion paso a paso
1. pip install -r conf/base/requeriments.txt
2. en el settings.py  agregar la siguente linea en las aplicaciones instaladas 
INSTALLED_APPS = [
...
'graphene_django',
...
]

GRAPHENE = {
    'SCHEMA': 'exampleGrap.schema.schema'
}

crear dentro de la aplicacion el fichero schema y aqui hacer las configuraciones 

luego en la raiz del proyecto crear otro fichero schema revisar el eejmplo



# Guia de referencia que seguí para el aprendizaje: 
https://media.readthedocs.org/pdf/graphene-django/stable/graphene-django.pdf
