> # Usage


The SDK provides two distinct modules for uploads: **Rental** and **Dev**. Each module is designed for different environments, depending on whether you're in development or production.
Before utilizing the SDK, initialize an instance of RentHub and while providing an API key.

### Initialize the SDK

To upload files or JSON data, you need to initialize an instance of the `RentHub` class using your API key. 

```javascript
const RentHub = require("@ellumina/renthub-btfs").default;

const instance = new RentHub('your-api-key-here');
```

Make sure to replace `'your-api-key-here'` with the actual API key. You can find instructions on how to generate your API key in our [API Key Guide](/guides?id=creating-and-managing-your-api-key).

---
