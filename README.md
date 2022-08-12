# A package to work with local and session storage on the browser

`npm i storage-save`

and import one of the storage options (locale or session)

### how to work with storage

> `import { localeStorage } from 'storage-save'`
or
> `import { sessionStorage } from 'storage-save'`

## there are 3 methods for both

### 1. ` get ` to get data from storage
```javascript
localeStorage.get("key")
sessionStorage.get("key")
```

### 2. ` set ` to set data to storage
```javascript
localeStorage.set("key", data)
sessionStorage.set("key", data)
```

### 3. ` remove ` to remove data from storage
```javascript
localeStorage.remove("key")
sessionStorage.remove("key")
```
