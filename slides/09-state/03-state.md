## [state]

```

<select field="skills" data label state ></select>

<div panel="results" template="cards" state ></div>

```

Propiedades creadas automágicamente en {state} :

```

app.state.skills // contiene el valor del campo skills

app.state.results // contiene los datos actuales del template

```

Si se declara en un contendor, se crea en {state} un objeto con el estado de todos los [field]s que contenga dicho contenedor. Y sí, tiene fallback.