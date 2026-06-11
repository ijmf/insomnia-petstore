# insomnia-petstore

Collection da Petstore API construída no Insomnia, cobrindo o ciclo completo de um recurso: POST, GET, PUT e DELETE.

## O que é

Collection com 5 endpoints da API pública do Petstore (swagger.io), organizada no Insomnia com variável de environment para a URL base. Cobre o fluxo completo de gerenciamento de um pet — cadastro, consulta, atualização, busca por status e remoção.

## Stack

- Insomnia v5
- API testada: Petstore Swagger (https://petstore.swagger.io/v2)

## Estrutura

```
insomnia-petstore/
└── petstore-insomnia.json    # Collection exportada do Insomnia
```

## Como importar

1. Abre o Insomnia
2. Clica em **Import**
3. Seleciona o arquivo `petstore-insomnia.json`
4. A collection **Petstore API** aparece com os 5 endpoints prontos

## Environment

| Variável | Valor |
|---|---|
| baseUrl | https://petstore.swagger.io/v2 |

## Endpoints

| Nome | Método | Endpoint | O que faz |
|---|---|---|---|
| POST - Cadastrar Pet | POST | /pet | Cadastra um novo pet |
| GET - Buscar Pet por ID | GET | /pet/{id} | Busca pet pelo ID gerado no POST |
| PUT - Atualizar Pet | PUT | /pet | Atualiza nome e status do pet |
| GET - Buscar por Status | GET | /pet/findByStatus | Lista pets por status |
| DELETE - Remover Pet | DELETE | /pet/{id} | Remove o pet cadastrado |
