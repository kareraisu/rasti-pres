## [template] + {templates}

```

<div panel="results" template="cards">

</div>

```

```

app.templates.cards = function(data) {

    return data.map( function(obj){
        return `<div class="card row">...` // ES6 interpolated string
    }).join()

}

```
