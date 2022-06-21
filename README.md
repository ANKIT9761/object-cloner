## >Hi this package is for helping you create deep copies of Arrays and objects.

### Examples-

```
import deepClone from "@ankitkanyal/object-cloner";

let obj = { name: "ankit", id: 123 };
let objClone = clone(obj);
delete objClone.id;
console.log("- obj", obj);
console.log("- objClone", objClone);

```

> It will print
>
> - obj { name: 'ankit', id: 123 }
> - objClone { name: 'ankit' }

> It is library used to deep clone and is based on json parse and stringify methods to create deep clones.
