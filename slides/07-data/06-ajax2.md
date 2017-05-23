## {ajax}

```
app.ajax.getPeople = function(reqdata, render) {
  myRESTService.getPeople(reqdata).then(function(resdata) {
    render(resdata) // o no
  })
}
```