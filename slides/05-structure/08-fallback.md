## [header] y [label] tienen fallback

Se pueden dejar sin valor, en cuyo caso el framework usará el valor de [field], [section], [panel] o [page].

```

<div page="login" header > <!-- el header dirá "login" -->

    <input type="text" field="user" label /> <!-- la label dirá "user" -->

    <input type="password" field="pass" label /> <!-- la label dirá "pass" -->

    <button btn>LOG IN</button>

</div>

```

(Algo muy conveniente cuando se lo combina con i18n)