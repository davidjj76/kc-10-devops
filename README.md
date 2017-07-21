# Práctica de devops

## Ejercicio 1: https://wordplease.davidjj76.com/

Despliegue de la práctica de python-django
https://github.com/davidjj76/kc-05-wordplease

## Ejercicio 2: https://nodepop.davidjj76.com/

Despliegue de la práctica de node
https://github.com/davidjj76/kc-06-nodepop

Están disponibles los endpoints: 

- /apiv1/users/ (POST) -> Da de alta un usuario
```
name
email
password
```

- /apiv1/users/authenticate (POST) -> Nos genera un token necesario para los siguientes endpoints
```
email
password
```

- /apiv1/advertisements (GET) -> Obtiene un listado de anuncios
```
token
```

- /apiv1/advertisements/tags (GET) -> Obtiene un listado de tags
```
token
```
