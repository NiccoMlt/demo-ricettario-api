# demo-ricettario-api

Fake REST API per esercitazioni su Fetch API e async/await nel modulo JavaScript ITS.

Basato su [my-json-server](https://my-json-server.typicode.com/) (typicode).

> **Nota**: le modifiche (POST, PUT, DELETE) non vengono persistite. Il server usa `db.json` come sola sorgente di dati.

## Endpoint

Base URL: `https://my-json-server.typicode.com/NiccoMlt/demo-ricettario-api`

| Metodo | URL | Descrizione |
|--------|-----|-------------|
| GET | `/recipes` | Lista di tutte le ricette |
| GET | `/recipes/:id` | Singola ricetta per ID |
| POST | `/recipes` | Aggiunge una ricetta (non persistita) |
| PUT | `/recipes/:id` | Modifica una ricetta (non persistita) |
| DELETE | `/recipes/:id` | Elimina una ricetta (non persistita) |

## Schema

```json
{
  "id": 1,
  "title": "Nome della ricetta",
  "ingredients": ["320g di pasta", "Pepe nero q.b."],
  "instructions": "Testo libero con i passi di preparazione."
}
```

## Ricette incluse

1. Spaghetti alla Carbonara
2. Spaghetti Cacio e Pepe
3. Bucatini all'Amatriciana
4. Pasta alla Gricia
5. Pasta e Fagioli
