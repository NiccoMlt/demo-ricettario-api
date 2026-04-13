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
  "name": "Spaghetti alla Carbonara",
  "image": "https://raw.githubusercontent.com/NiccoMlt/demo-ricettario-api/refs/heads/master/carbonara.png",
  "description": "Un classico della cucina romana, amato in tutto il mondo per la sua cremosità e il sapore deciso.",
  "ingredients": {
    "g di spaghetti": 80,
    "g di guanciale": 40,
    "tuorli d'uovo": 1,
    "g di pecorino romano": 10,
    "Pepe nero": null
  },
  "preparation": [
    "Mettere a bollire l'acqua per la pasta.",
    "Tagliare il guanciale a listarelle e rosolarlo in padella finché non diventa croccante.",
    "In una ciotola, sbattere i tuorli con il pecorino e abbondante pepe nero."
  ]
}
```

## Ricette incluse

1. Spaghetti alla Carbonara
2. Spaghetti Cacio e Pepe
3. Bucatini all'Amatriciana
4. Pasta alla Gricia
5. Pasta e Fagioli
