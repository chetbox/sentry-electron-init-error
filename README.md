# Sentry `Object(...) is not a function` error

First, set a valid Sentry DSN in `src/index.tsx`.

Then run:

```shell
yarn
yarn start
```

You will see the following error:

```
App threw an error during load
TypeError: Object(...) is not a function

...

A JavaScript error occurred in the main process
Uncaught Exception:
TypeError: Object(...) is not a function
```
