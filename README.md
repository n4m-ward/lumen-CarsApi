# Cars api

## Para iniciar o Projeto:

```
php -S localhost:8080 -t public
```

## POST /api/car/
### Endpoint responsavel por criar um novo registro

#### Parametros
name
description
model
date



## GET /api/cars
### Rota Responsavel por listar todos registros

#### Respostas
#### OK! 200
#### Erro interno! 500

```
{
    "id": 2,
    "name": "Hyndai HB20",
    "description": "Caminhonete Foda d+",
    "model": "n conheço de carro mas essa é foda msm",
    "date": "2018-01-21"
  },
  {
    "id": 3,
    "name": "corsa rebaixado",
    "description": "Brabo dms",
    "model": "n conheço de carro",
    "date": "2018-01-21"
  }
  ```
 
## GET /api/car/:id
### Rota responsavel por buscar um registro em especifico pelo id

#### Respostas
#### OK! 200
#### Erro interno! 500

```
{
    "id": 2,
    "name": "Hyndai HB20",
    "description": "Caminhonete Foda d+",
    "model": "n conheço de carro mas essa é foda msm",
    "date": "2018-01-21"
}
```

## PUT /api/car/:id
### Endpoint responsavel por editar um registro em especifico

#### Parametros
Id
name
description
model
date

#### Respostas
#### OK! 200
#### Erro interno! 500



## DELETE /api/car/:id
### Rota responsavel por deletar um registro pelo id.
#### Parametros
Id

#### Respostas
#### OK! 200


#### Erro interno! 500
