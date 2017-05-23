## render()

```
var cards = app.get('template=cards')

app.render(cards) // usa la data bindeada via atributo

var data = myRESTService.getData()

app.render(cards, data) // usa la data pasada por parámetro
```