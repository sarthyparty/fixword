# FixWord

A nodejs package with a leetspeak randomizer for making usernames unique. Also has a password strength checking function.

<h2>Installation</h2>

```npm install fixword```

<h2>Usage</h2>

```
const {get_alts, get_strength} = require("fixword")

console.log(get_alts("sarthyparty", 5, 0.3)) 
// Returns a list of 5 alternative usernames with 30% of its letters swapped for LeetSpeak

console.log(get_strength("NotActuallyMyP4$$"))
// Returns Strong, Medium, or Weak, based on the OWASP guidlines
```

[Chrome Extension](https://github.com/sarthyparty/fixword_ext)

[Website Demo](https://fixword.netlify.app/)
