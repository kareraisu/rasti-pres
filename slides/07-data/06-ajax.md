## [ajax] + [submit]

[ajax] en el contenedor, [submit] en el botón

```

<div panel="filters" ajax="getPeople">

    <div section="personal">
        <input type="text" field="name" label >
    </div>

    <div section="work">
        <select field="skills" data label ></select>
    </div>

    <button btn submit="getPeople">BUSCAR</button>

</div>

```