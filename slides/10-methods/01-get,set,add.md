## get(), set(), add()

```
var user = app.get('field=user')
var skills = app.get('field=skills')

user.val() // 'Fulano'
app.set('field=user', 'Mengano')
user.val() // 'Mengano'

skills.val() // ['git']

var langs = ['html', 'css', 'js']
var frames = ['backbone', 'react', 'vue']
app.add('field=skills', langs, frames, 'rasti')

skills.val() // ['git', 'html', 'css', 'js', 'backbone', 'react', 'vue', 'rasti']

```