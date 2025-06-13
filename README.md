# NeuroNetwork 🔬🧠

[![NPM version](https://img.shields.io/npm/v/neuronetwork.svg)](https://www.npmjs.com/package/neuronetwork)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Build](https://img.shields.io/badge/build-passing-brightgreen)](#)
[![Node.js](https://img.shields.io/badge/node-%3E%3D14.0.0-brightgreen)](https://nodejs.org)
[![ESM Support](https://img.shields.io/badge/ESM-Supported-blue)](#)
[![CJS Support](https://img.shields.io/badge/CJS-Supported-orange)](#)

[![Bundle Size](https://img.shields.io/bundlephobia/minzip/neuronetwork)](https://bundlephobia.com/package/neuronetwork)
[![Dependencies](https://img.shields.io/librariesio/release/npm/neuronetwork)](https://libraries.io/npm/neuronetwork)
[![Lines of Code](https://img.shields.io/tokei/lines/github/QuickDigiCompany/neuronetwork)](https://github.com/QuickDigiCompany/neuronetwork)

[![Math](https://img.shields.io/badge/math-core-lightgrey)](#)
[![Neural Functions](https://img.shields.io/badge/Neural%20Network-Built--in-purple)](#)
[![Optimizers](https://img.shields.io/badge/Optimizers-SGD%20%7C%20Adam-blueviolet)](#)
[![Activation](https://img.shields.io/badge/Activation%20Funcs-ReLU%20%7C%20Sigmoid%20%7C%20Tanh-teal)](#)

[![Open in VSCode](https://img.shields.io/badge/Open%20in-VSCode-007ACC?logo=visual-studio-code)](https://open.vscode.dev/)
[![Watch Mode](https://img.shields.io/badge/dev--mode-watch-yellow)](#)
[![Made with JS](https://img.shields.io/badge/Made%20with-JavaScript-yellowgreen)](#)


> A powerful hybrid mathematical and neural-network computation library built with modern JavaScript and WebAssembly, inspired by C++ numeric performance.

---

## 📦 Installation

```bash
npm install neuronetwork
```

---

# 🚀 Usage (ES Modules Only)

```js
// ES Module
import NeuroNetwork from "neuronetwork";

const result = await NeuroNetwork.NextMath.add(2, 3);
console.log(result); // 5
```

> Note: This package only supports ESM. For usage in CommonJS environments or browsers, you will need a bundler like Vite, Webpack, or Rollup.

---

# 🧠 Features

- ✅ Classic Math Functions (add, sqrt, mod, etc.)

- ✅ Prime, Factorial, GCD, Fibonacci

- ✅ Activation Functions: ReLU, Sigmoid, Tanh, etc.

- ✅ Loss Functions: MSE, MAE, BCE, CCE

- ✅ Layers: Dense, Dropout, Conv2D, etc.

- ✅ Optimizers: Adam, SGD

# 📁 Project Structure

```txt
│
├── functions/
│   ├── NextMath.js
│   └── NeuroMath.js
│
└── index.js
```

---

## 📄 `LICENSE`

MIT — Made with ❤️ by [QuickDigiLLC](https://github.com/QuickDigi)

```txt
MIT License

Copyright (c) 2025 QuickDigi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
