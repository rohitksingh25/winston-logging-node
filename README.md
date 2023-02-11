# Node Logging with winston

This tutorial demonstrates how to use the [winston logging library](https://github.com/winstonjs/winston) to create custom loggers in your Node.js application.

It also demonstrates how to customize transports and what you need to pay attention to when you **prepare your application for production use**.

# How to run this application

Run

```
npm install
```

to install all dependencies

To see the output of the development logger run

```
npm run dev
```

The `dev` script automatically sets the `NODE_ENV` environment variable to `development`.

If the `NODE_ENV` environment variable is set to a different value than `development` (or not set at all), the production logger will be used.

To see the output of the production logger, just run

```
node index.js
```
