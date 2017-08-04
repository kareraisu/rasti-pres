## {ajax}

Luego se declara la función en {ajax}, a la cual rasti va a proveer un objeto con los valores de los [field]s del contenedor y, en caso de que el botón esté bindeado a un template, la función correspondiente al mismo

```

app.ajax.getPeople = function(reqdata, render) {

  myRESTService.getPeople(reqdata).then( function(resdata) {
    render(resdata) // si es que hay un template bindeado
  })

}

```