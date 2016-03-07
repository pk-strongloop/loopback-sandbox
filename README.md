# loopback-sandbox

For reproducing issue strongloop/loopback#2123

POST multiple records:

http://localhost:3000/explorer/#!/Contact/Contact_create

```
[{
  "firstname": "P",
  "middlename": "K",
  "lastname": "Tippa"
},
{
  "firstname": "Pradeep",
  "middlename": "K",
  "lastname": "T"
}]
```

PUT mltiple records:

http://localhost:3000/explorer/#!/Contact/Contact_upsert

```
[
  {
    "firstname": "P",
    "middlename": "Kumar",
    "lastname": "Tippa",
    "id": 1
  },
  {
    "firstname": "Pradeep",
    "middlename": "K",
    "lastname": "Tippa",
    "id": 2
  }
]
```