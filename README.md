# FixWord

A nodejs package with a leetspeak randomizer for making usernames unique. Also has a password strength checking function.

<h2>Installation</h2>

```npm install fixword```

<h2>Usage</h2>

```
const {get_alts, get_strength }= require("./index")
console.log(get_alts("sarthyparty", 5, 0.3))
console.log(get_strength("NotActuallyMyP4$$"))
```
