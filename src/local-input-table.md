---
title: local input table
---


```js
import * as Inputs from "@observablehq/inputs";

```

```js
const launches = FileAttachment("data/launches.csv").csv({typed: true});
```

```js
Inputs.table(launches)
```

# Header below table
