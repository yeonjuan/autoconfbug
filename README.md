# autoconfbug

```
git clone https://github.com/yeonjuan/autoconfbug.git

eslint --init

? How would you like to use ESLint? To check syntax, find problems, and enforce code style
? What type of modules does your project use? JavaScript modules (import/export)
? Which framework does your project use? React
? Does your project use TypeScript? Yes
? Where does your code run? Browser, Node
? How would you like to define a style for your project? Inspect your JavaScript file(s)
? Which file(s), path(s), or glob(s) should be examined? ./src/**.{ts,tsx}
? What format do you want your config file to be in? JavaScript
```


## result
```
config.extends.push is not a function
TypeError: config.extends.push is not a function
    at processAnswers (/MY_PROJ/node_modules/eslint/lib/init/config-initializer.js:331:24)
    at /MY_PROJ/node_modules/eslint/lib/init/config-initializer.js:615:28
    at processTicksAndRejections (internal/process/task_queues.js:93:5)

```
