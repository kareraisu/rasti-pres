## {pages} - url

```

app.pages.main = {

    url : 'main',

    in : function(params) {
        if (params) {
        	app.set('name=user', params.user).show()
        }
    },

    out : function(params) {
        app.get('name=user').hide()
    },
    
}

```