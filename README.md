# Collection
Utility data structure for Deno (Original Author: **Discord.js Developers**).

# NodeJS
**[Discord.js Collection](https://github.com/discordjs/collection)**

# Example

```js
import { Collection } from "https://raw.githubusercontent.com/Snowflake107/collection/master/mod.ts";

const store = new Collection();

store.set("test", { value: "asdf", id: 1 });

const data = store.find(x => x.id === 1).value;
```

# Documentation
**[https://discord.js.org/#/docs/collection/master/general/welcome](https://discord.js.org/#/docs/collection/master/general/welcome)**