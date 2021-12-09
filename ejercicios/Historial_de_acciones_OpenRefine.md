# HISTORIAL DE ACCIONES DE OPENREFINE
[
  {
    "op": "core/column-removal",
    "columnName": "19:\"2020-03-18T11:54:15Z,2020-03-18T11:52:12Z,Feliz 101,http://twitter.com/search?q=%22Feliz+101%22,%22Feliz+101%22,\n22:\"2020-03-18T11:54:15Z",
    "description": "Remove column 19:\"2020-03-18T11:54:15Z,2020-03-18T11:52:12Z,Feliz 101,http://twitter.com/search?q=%22Feliz+101%22,%22Feliz+101%22,\n22:\"2020-03-18T11:54:15Z"
  },
  {
    "op": "core/column-removal",
    "columnName": "http://twitter.com/search?q=%22Felices+88%22",
    "description": "Remove column http://twitter.com/search?q=%22Felices+88%22"
  },
  {
    "op": "core/column-removal",
    "columnName": "%22Felices+88%22",
    "description": "Remove column %22Felices+88%22"
  },
  {
    "op": "core/column-removal",
    "columnName": "Column",
    "description": "Remove column Column"
  },
  {
    "op": "core/column-split",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "2020-03-18T11:52:12Z",
    "guessCellType": true,
    "removeOriginalColumn": true,
    "mode": "lengths",
    "fieldLengths": [
      10
    ],
    "description": "Split column 2020-03-18T11:52:12Z by field lengths"
  },
  {
    "op": "core/text-transform",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "2020-03-18T11:52:12Z 1",
    "expression": "value.toDate()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10,
    "description": "Text transform on cells in column 2020-03-18T11:52:12Z 1 using expression value.toDate()"
  },
  {
    "op": "core/row-removal",
    "engineConfig": {
      "facets": [
        {
          "type": "timerange",
          "name": "2020-03-18T11:52:12Z 1",
          "expression": "value",
          "columnName": "2020-03-18T11:52:12Z 1",
          "from": 0,
          "to": 79411752000,
          "selectTime": true,
          "selectNonTime": true,
          "selectBlank": true,
          "selectError": true
        }
      ],
      "mode": "row-based"
    },
    "description": "Remove rows"
  },
  {
    "op": "core/row-removal",
    "engineConfig": {
      "facets": [
        {
          "type": "timerange",
          "name": "2020-03-18T11:52:12Z 1",
          "expression": "value",
          "columnName": "2020-03-18T11:52:12Z 1",
          "from": 1584489600000,
          "to": 1591142400000,
          "selectTime": true,
          "selectNonTime": true,
          "selectBlank": true,
          "selectError": true
        }
      ],
      "mode": "row-based"
    },
    "description": "Remove rows"
  },
  {
    "op": "core/row-removal",
    "engineConfig": {
      "facets": [
        {
          "type": "timerange",
          "name": "2020-03-18T11:52:12Z 1",
          "expression": "value",
          "columnName": "2020-03-18T11:52:12Z 1",
          "from": 1596067200000,
          "to": 1625702400000,
          "selectTime": true,
          "selectNonTime": true,
          "selectBlank": true,
          "selectError": true
        }
      ],
      "mode": "row-based"
    },
    "description": "Remove rows"
  },
  {
    "op": "core/row-removal",
    "engineConfig": {
      "facets": [
        {
          "type": "list",
          "name": "Felices 88",
          "expression": "value",
          "columnName": "Felices 88",
          "invert": false,
          "omitBlank": false,
          "omitError": false,
          "selection": [
            {
              "v": {
                "v": "#FelipeVIesCómplice",
                "l": "#FelipeVIesCómplice"
              }
            },
            {
              "v": {
                "v": "#FelicidadesMerche",
                "l": "#FelicidadesMerche"
              }
            },
            {
              "v": {
                "v": "Feliz 4",
                "l": "Feliz 4"
              }
            },
            {
              "v": {
                "v": "#FelizCumpleLOS40",
                "l": "#FelizCumpleLOS40"
              }
            },
            {
              "v": {
                "v": "#Felices20Flavio",
                "l": "#Felices20Flavio"
              }
            },
            {
              "v": {
                "v": "#Felices21Famous",
                "l": "#Felices21Famous"
              }
            },
            {
              "v": {
                "v": "Felipe VI",
                "l": "Felipe VI"
              }
            },
            {
              "v": {
                "v": "#Felices24Sofia",
                "l": "#Felices24Sofia"
              }
            },
            {
              "v": {
                "v": "#Felices20Anne",
                "l": "#Felices20Anne"
              }
            },
            {
              "v": {
                "v": "#FelizAlzamiento",
                "l": "#FelizAlzamiento"
              }
            },
            {
              "v": {
                "v": "Felicidades PRESIDENTE",
                "l": "Felicidades PRESIDENTE"
              }
            },
            {
              "v": {
                "v": "Feliz Día de Galicia",
                "l": "Feliz Día de Galicia"
              }
            },
            {
              "v": {
                "v": "Felicidades Santi",
                "l": "Felicidades Santi"
              }
            },
            {
              "v": {
                "v": "Rey Felipe",
                "l": "Rey Felipe"
              }
            },
            {
              "v": {
                "v": "#Felices23Mireya",
                "l": "#Felices23Mireya"
              }
            },
            {
              "v": {
                "v": "#FelizDiaDeGalicia",
                "l": "#FelizDiaDeGalicia"
              }
            },
            {
              "v": {
                "v": "Felipe y Letizia",
                "l": "Felipe y Letizia"
              }
            },
            {
              "v": {
                "v": "#YaSobrasFelipeVI",
                "l": "#YaSobrasFelipeVI"
              }
            },
            {
              "v": {
                "v": "Felicidades Ana",
                "l": "Felicidades Ana"
              }
            },
            {
              "v": {
                "v": "Felicidades Albert",
                "l": "Felicidades Albert"
              }
            },
            {
              "v": {
                "v": "#PírateYaFelipeVI",
                "l": "#PírateYaFelipeVI"
              }
            },
            {
              "v": {
                "v": "#FelizSemana",
                "l": "#FelizSemana"
              }
            },
            {
              "v": {
                "v": "#Felices41db",
                "l": "#Felices41db"
              }
            },
            {
              "v": {
                "v": "#AdaraFeliz",
                "l": "#AdaraFeliz"
              }
            },
            {
              "v": {
                "v": "#FelipeGonzález",
                "l": "#FelipeGonzález"
              }
            },
            {
              "v": {
                "v": "Felices 21",
                "l": "Felices 21"
              }
            },
            {
              "v": {
                "v": "Felicitats",
                "l": "Felicitats"
              }
            },
            {
              "v": {
                "v": "Felicidades Roberto",
                "l": "Felicidades Roberto"
              }
            },
            {
              "v": {
                "v": "#Felices26Bruno",
                "l": "#Felices26Bruno"
              }
            },
            {
              "v": {
                "v": "#FelizDiaDelPadre",
                "l": "#FelizDiaDelPadre"
              }
            },
            {
              "v": {
                "v": "#Felices26Anaju",
                "l": "#Felices26Anaju"
              }
            },
            {
              "v": {
                "v": "Felicidades Carmen",
                "l": "Felicidades Carmen"
              }
            },
            {
              "v": {
                "v": "Feliz Día de La Rioja",
                "l": "Feliz Día de La Rioja"
              }
            },
            {
              "v": {
                "v": "Felipe Reyes",
                "l": "Felipe Reyes"
              }
            },
            {
              "v": {
                "v": "Felicidades Juan",
                "l": "Felicidades Juan"
              }
            },
            {
              "v": {
                "v": "#Felices21Aitana",
                "l": "#Felices21Aitana"
              }
            },
            {
              "v": {
                "v": "#FelizDia",
                "l": "#FelizDia"
              }
            },
            {
              "v": {
                "v": "#Felices19Anne",
                "l": "#Felices19Anne"
              }
            },
            {
              "v": {
                "v": "Felicia",
                "l": "Felicia"
              }
            },
            {
              "v": {
                "v": "Contra Felipe González",
                "l": "Contra Felipe González"
              }
            },
            {
              "v": {
                "v": "Felipe González",
                "l": "Felipe González"
              }
            },
            {
              "v": {
                "v": "Felicidades Antonio",
                "l": "Felicidades Antonio"
              }
            },
            {
              "v": {
                "v": "Could Felipe",
                "l": "Could Felipe"
              }
            },
            {
              "v": {
                "v": "Feliz 29",
                "l": "Feliz 29"
              }
            },
            {
              "v": {
                "v": "#FelipeGonzalez",
                "l": "#FelipeGonzalez"
              }
            },
            {
              "v": {
                "v": "#FelizCumpleChenoa",
                "l": "#FelizCumpleChenoa"
              }
            }
          ],
          "selectBlank": false,
          "selectError": false
        }
      ],
      "mode": "row-based"
    },
    "description": "Remove rows"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Felices 88",
    "expression": "value",
    "edits": [
      {
        "from": [
          "#FelizMiercoles",
          "#FelizMiércoles"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "#FelizMiércoles"
      },
      {
        "from": [
          "#FelizDomingo",
          "#Felizdomingo"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "#FelizDomingo"
      },
      {
        "from": [
          "#FelizSabado",
          "#FelizSábado"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "#FelizSábado"
      },
      {
        "from": [
          "#FelizViernesATodos",
          "#FelizViernesAtodos"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "#FelizViernes"
      }
    ],
    "description": "Mass edit cells in column Felices 88"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Felices 88",
    "expression": "value",
    "edits": [
      {
        "from": [
          "#FelizSabadoATodos"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "#FelizSábado"
      }
    ],
    "description": "Mass edit cells in column Felices 88"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Felices 88",
    "expression": "value",
    "edits": [
      {
        "from": [
          "Feliz Sábado"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "#FelizSábado"
      }
    ],
    "description": "Mass edit cells in column Felices 88"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Felices 88",
    "expression": "value",
    "edits": [
      {
        "from": [
          "#FelizFinDeSemana"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "#FelizFinde"
      }
    ],
    "description": "Mass edit cells in column Felices 88"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Felices 88",
    "expression": "value",
    "edits": [
      {
        "from": [
          "#FelizSábado"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "#FelizSabado"
      }
    ],
    "description": "Mass edit cells in column Felices 88"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Felices 88",
    "expression": "value",
    "edits": [
      {
        "from": [
          "#FelizMiércoles"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "#FelizMiercoles"
      }
    ],
    "description": "Mass edit cells in column Felices 88"
  }
]

