# Clientes de tienda de Ordenadores

## En qué clasificamos a nuestros clientes?

Nuestros clientes los clasificamos por *hobbies, altura, peso, nombre...*, además para nosotros tienen mucha importancia los datos que nos ayudan a *contactar* con nuestro cliente, como por ejemplo, **correo electrónico, o número de teléfono**.

<!--Lista sin orden en concreto-->
## Tipo de productos que vendemos

* Ordenadores
* Portátiles
* Hardware
    * Tarjetas gráficas
    * Placas Base
    * Procesadores
* Licencias oficiales de software
* Periféricos

>Nuestro enlace para comprar los productos:  
https://www.pccomponentes.com/  

![Logo de nuestra compañía](https://www.info-computer.com/modules/dbblog/views/img/post/ordenador-portatil-u-ordenador-de-sobremesa.jpg)

### Un ejemplo de JSON i YAML de como tenemos organizados a nuestros clientes

<!--Bloque de código-->
```JSON
"id": 1,
    "nom_cliente": "Jose Vicent",
    "apellido": "Alandí",
    "edad": 19,
    "altura": 1.89,
    "peso": 80,
    "email": "josevicentealandí@gmail.com",
    "hobbies": {
        "futbol": false,
        "videojuegos": true,
        "musica": true,
        "basket": null
    },
```
```YAML
- id: 1
    nom_cliente: Jose Vicent
    apellido: Alandí
    edad: 19
    altura: 1.89
    peso: 80
    email: josevicentealandi@gmail.com
    hobbies:
     - futbol: false
     - videojuegos: true
     - musica: true
     - basket: null
```

| Clientes | Dinero Gastado | Productos Comprados  
| --- | --- | ---
| Jose Vicente | 450 euros | 6 Productos
| Inés Álvarez | 520 euros | 8 Productos
| David Serrano | 800 euros | 12 Productos
