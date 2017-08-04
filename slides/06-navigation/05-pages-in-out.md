## {pages} - in() y out()

```

app.pages.main = {

    in : function(params) {
        if (params) {
        	app.set('name=user', params.user)
        }
    },

    out : function(params) {
        app.set('name=user', '')
    },

}

```