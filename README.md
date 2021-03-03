# dwebdomains

Experimental none enumerable trie for stuff like domains

```
npm install dwebdomains
```

## Usage

``` js
const DWebDomains = require('dwebdomains')
const domains = new DWebDomains(storage, key)

domains.register('foo', ddatabaseKey, cb)
domains.lookup('foo', cb)
```

## License

MIT
