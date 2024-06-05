## Front-end DT-money

[![React](https://img.shields.io/badge/-ReactJs-61DAFB?logo=react&logoColor=white&style=for-the-badge)](https://react.dev/)
[![Vite](https://img.shields.io/badge/-Vite-purple?logo=vite&logoColor=white&style=for-the-badge)](https://vitejs.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=TypeScript&logoColor=white&style=for-the-badge)](https://www.typescriptlang.org/)
[![Radix](https://img.shields.io/badge/radix-1D1817?logo=radix&logoColor=white&style=for-the-badge)](https://www.radix-ui.com)
[![Zod](https://img.shields.io/badge/zod-0E2E58?logo=zod&logoColor=white&style=for-the-badge)](https://zod.dev)
[![JSON-SERVER](https://img.shields.io/badge/jsonserver-2C6410?logo=jsonserver&logoColor=white&style=for-the-badge)](https://github.com/typicode/json-server/tree/v0)
[![CSS](https://img.shields.io/badge/-css-3192d6?logo=CSS&logoColor=white&style=for-the-badge)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)


## 1. Introduction

### 1.1 Challenge Overview

<img align="right" src="https://raw.githubusercontent.com/fabiobatoni/DT-money/af8a710ce6c673f37ea9003bd0ca8e3a82ecc80f/src/assets/logo.svg" width="400"/>


Complete front-end web application, connecting to an API and we will see how to perform applications with React, understanding how the library's internal algorithms and the entire component rendering flow work.



### 1.2 Why does a component render?
 
  - Hooks changed (changed state, context, reducer);
  - Props changed (changed properties);
  - Parent rerendered (parent component rendered);
 
  What is the rendering flow?
  1. React recreates the HTML of that component's interface.
  2. Compares the recreated HTML version with the previous version.
  3. IF anything changed, it rewrites the HTML on the screen.
 
### Memo:
  0. Hooks changed, Props changed (deep comparison).
  0.1 Compare with the previous version of hooks and props.
  0.2 IF something changed, it will allow re-rendering.
 

## 2. Getting Started for Developers

To set up a local copy of this repository:

- For SSH (recommended for secure, key-based authentication), use:

  ```bash
  git@github.com:fabiobatoni/DT-money.git
  ```

- For HTTPS (simpler setup, ideal for quick trials), use:

  ```bash
  https://github.com/fabiobatoni/DT-money.git
  ```

### 2.1 Installation

Follow these steps to set up the DT-money environment on your local
machine:

1. **Clone the Repository and Change Directory**

```bash
cd DT-money
```

2. **Install Project Dependencies**

In the project directory, run:

```bash
npm install
```

### 2.2 Local Development

**Prerequisite**

- Before you begin, check the version of `node` by running the command `node
--version`. According to "Minimum Runtime Requirements", **TypeScript** requires
`node` version 18.17.1 or later.

To start the DT-money, follow these steps:

1. **Run the Application**

Use the commands to run:

- Development environment

```bash
npm run dev
```

1.1. **Run server (API)**

```bash
npm run dev:server
```

2. **Access the Application**

Once the server is running, open your preferred web browser and navigate to:

- [http://localhost:5173](http://localhost:5173)
