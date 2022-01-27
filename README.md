# FixWord

A nodejs package with a leetspeak randomizer for making usernames unique. Also has a password strength checking function.

```npm install fixword```

```const {get_alts, get_strength }= require("./index")


console.log(get_alts("sarthyparty", 5, 0.3))
console.log(get_strength("NotActuallyMyP4$$"))```
