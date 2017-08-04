## en forma de tarjetas

```

<div class="card row">
    <div class="photo col-2"
        style="background-image: url(${obj.id + '.jpg'})"></div>
    <div class="col-10">
        <div class="name">${obj.name}</div>
        <div class="row">
            <div class="labels col-4">
                Area:<br/>
                Position:<br/>
                Skills:
            </div>
            <div class="values col-8">
                ${obj.area}<br/>
                ${obj.position}<br/>
                ${obj.skills}
            </div>
        </div>
    </div>
</div>

```