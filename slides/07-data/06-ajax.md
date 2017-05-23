## [ajax] + [submit]

```
<div panel="filters" ajax="getPeople">
    <div section="personal">
        <input type="text" field="name" label="name">
    </div>
    <div section="work">
        <select field="skills" label="skills" data="skills"></select>
    </div>
    <button btn submit="getPeople">BUSCAR</button>
</div>
```