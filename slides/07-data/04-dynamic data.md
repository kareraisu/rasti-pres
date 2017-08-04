## no problem

La propiedad definida en {data} puede ser una función, en cuyo caso rasti le provee, a su vez, una función de render para poder renderizar los datos cuando uno quiera


```

app.data.skills = function(render){

    myRESTService.getTechs().then( function(data){
        // any transformations/validations here
        render(data)
    })

}

```
