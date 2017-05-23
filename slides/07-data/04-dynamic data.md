## no problem

```
<div section="work">
    <select field="skills" data="skills" label="skills"></select>
</div>
```

```
app.data.skills = function(render){
    myRESTService.getTechs().then(function(data){
        // any transformations/validations here
        render(data)
    })
}
```

Note:
mockear una llamada asincrónica con setTimeout