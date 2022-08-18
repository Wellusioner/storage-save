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
> ##### if you want to get data without parsing, pass the second argument false `(default true)`
```javascript
localeStorage.get("key", true)
sessionStorage.get("key", true)
```

### 2. ` set ` to set data to storage
```javascript
localeStorage.set("key", data)
sessionStorage.set("key", data)
```
> ##### if you want the method to stringify data, pass true as the third argument `(deault false)`
```javascript
localeStorage.get("key", data, true)
sessionStorage.get("key", data, true)
```

### 3. ` remove ` to remove data from storage
```javascript
localeStorage.remove("key")
sessionStorage.remove("key")
```

> ##### if you want the method to return data before being deleted, pass true as the second argument `(default false)`
```javascript
localeStorage.remove("key", true)
sessionStorage.remove("key", true)
```
