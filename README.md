

# **logify**

A simple and lightweight utility to simplify `console.log` statements in JavaScript. Instead of writing `console.log()`, just use `write()` for cleaner and shorter code.

---

## **Installation**

### Using npm:
```bash
npm install logify
```

### For Local Development (Testing Locally):
1. Navigate to your package directory and run:
   ```bash
   npm link
   ```

2. In your test project directory, link the package:
   ```bash
   npm link logify
   ```

---

## **Usage**

### Import the Package
```javascript
import write from "logify";
```

### Example
```javascript
write("Hello, World!"); // Prints: Hello, World!
write(12345);           // Prints: 12345
write({ key: "value" }); // Prints: { key: 'value' }
```

### What It Does:
- The `write()` function is a simplified wrapper for `console.log()`.
- It accepts any data type as input and logs it to the console.

---

## **Features**
- Simplifies `console.log` statements.
- Works with all JavaScript data types (strings, numbers, objects, arrays, etc.).

---

## **Project Structure**

```
writelog/
├── index.js        // Main JavaScript file with the write function
├── package.json    // Metadata file for the npm package
├── README.md       // Documentation file
```

---

## **Contributing**

Contributions are welcome! If you have ideas or suggestions, feel free to open an issue or create a pull request.

---

## **License**

This project is licensed under the **ISC License**.

---

## **Author**

**Mohammed Imran**  
Junior Frontend Developer  
GitHub: [@AMOHAMMEDIMRAN](https://github.com/AMOHAMMEDIMRAN)

---

## **Keywords**

`console`, `log`, `utility`, `simplify`, `write`, `console.log`

---

Let me know if you'd like any changes or additions! 😊