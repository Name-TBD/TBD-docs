> # Dev Usage

The **Dev** module is best suited for testing and development purposes. Files uploaded in this mode are temporary and will be cleared after a certain duration by the garbage collector.

#### 1. **Upload a File**

```javascript
const fs = require("fs");

const stream = fs.createReadStream("path/to/your/file.png");

instance.dev.pinFile(stream)
  .then((data) => {
    console.log("File pinned successfully:", data);
  })
  .catch((err) => {
    console.error("Error pinning file:", err);
  });
```

#### 2. **Upload a JSON Object**

```javascript
instance.dev.pinJson({ "key": "value" })
  .then((data) => {
    console.log("JSON pinned successfully:", data);
  })
  .catch((err) => {
    console.error("Error pinning JSON:", err);
  });
```

#### 3. **Retrieve a JSON Object**

```javascript
instance.dev.getJson("file-hash-here")
  .then((data) => {
    console.log("JSON data retrieved:", data);
  })
  .catch((err) => {
    console.error("Error retrieving JSON:", err);
  });
```