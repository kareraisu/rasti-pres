## [navparam] + [params]

```
<div page="login">
    <input type="text" field="user"
    	navparam="user"/>
    <input type="password" field="pass"/>
    <button nav="main"
    	params="user">LOG IN</button>
</div>
<div page="main">
    <div name="user"></div>
</div>
```
