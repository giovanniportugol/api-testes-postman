# Caso de Teste – GET Posts

## Identificação

**ID:** CT-API-001

**Funcionalidade:** Consulta de lista de posts

**Método HTTP:** GET

**Endpoint:** /posts

---

## Objetivo

Validar se a API retorna com sucesso a lista de posts cadastrados.

---

## Pré-condições

* API disponível para acesso.
* Conexão com a internet ativa.
* Postman instalado e configurado.
* Endpoint acessível.

---

## Dados da Requisição

### URL

```http
https://jsonplaceholder.typicode.com/posts
```

### Método HTTP

```http
GET
```

---

## Passos para Execução

1. Abrir o Postman.
2. Criar uma requisição do tipo GET.
3. Informar a URL da API.
4. Executar a requisição clicando em **Send**.
5. Analisar o retorno da API.

---

## Resultado Esperado

* Status Code igual a 200.
* Resposta retornada em formato JSON.
* Lista de posts disponível.
* Tempo de resposta dentro do esperado.
* Nenhum erro apresentado pela API.

---

## Resultado Obtido

A requisição foi executada com sucesso utilizando o Postman.

* Método: GET
* Endpoint: /posts
* Status Code: 200 OK
* Tempo de Resposta: 157 ms
* Formato da Resposta: JSON
* Registros Retornados: 100 posts

---

## Validações Implementadas

* Status Code igual a 200.
* Resposta em formato JSON.
* Retorno contendo registros.
* Estrutura da resposta validada.

---

## Evidência

Teste executado com sucesso no Postman utilizando o endpoint:

```http
GET https://jsonplaceholder.typicode.com/posts
```

---

## Status

**Aprovado**
