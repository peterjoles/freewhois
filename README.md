# domaininfo

A node client that uses the iana RDAP DNS database to lookup WHOIS information for free.

## Usage in code

1. Install via `npm i freewhois --save`

2. Code example:

```javascript
const whois = require("freewhois");

async function whoisLookup() {
    const data = await whois("https://www.gooogle.com");
    console.log(data); // returns as json
}

```

## Usage in CLI

1. Install via `npm i freewhois -g`

2. CLI command:

```bash
$ freewhois "https://www.google.com"
$ # returns as stringified json
```

## License

MIT