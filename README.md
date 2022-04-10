### KryCode ▽ 𝐆𝐚𝐬𝐂𝐨𝐦 𝐈𝐓  ```ﾉ
Krakinz API for all KrakinzBot

Full API Implementation inside NodeJS Module

More info at https://api.krakinz.xyz/
Get **APIKEY** here https://api.krakinz.xyz/register
## Usage
```ts
import { API: KryCode } from 'krakinz-api'

// Set Your APIKEY
KryCode.apikey = 'your-apikey'
```

## Example
TTP
```ts
const json = await KryCode.free.ttp('hello')
```

ATTP
```ts
const json = await KryCode.free.attp('hello')
```
