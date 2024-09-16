> # Rental Usage

The **Rental** module is intended for production, where files are uploaded for a defined duration and pinned on BTFS for that period.

#### 1. **Upload a File**

```javascript
const stream = fs.createReadStream("path/to/your/file.png");

instance.rental.pinFile(stream)
  .then((data) => {
    console.log("File pinned successfully:", data);
  })
  .catch((err) => {
    console.error("Error pinning file:", err);
  });
```

#### 2. **Upload a JSON Object**

```javascript
instance.rental.pinJson({ "key": "value" })
  .then((data) => {
    console.log("JSON pinned successfully:", data);
  })
  .catch((err) => {
    console.error("Error pinning JSON:", err);
  });
```

#### 3. **Retrieve a JSON Object**

```javascript
instance.rental.getJson("file-hash-here")
  .then((data) => {
    console.log("JSON data retrieved:", data);
  })
  .catch((err) => {
    console.error("Error retrieving JSON:", err);
  });
```
