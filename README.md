# Conway's Game of Life Demonstration

Conway's Game of Life in JavaScript using Test Driven Development.


### Installation

```
npm install
```

### Start Dev Server

```
npm run dev
```

### Build Prod Version

```
npm run build
```

### Test:


As a test runner, I used karma(http://karma-runner.github.io/) and wrote unit tests. You will need Google Chrome browser to run tests because Karma uses Chrome Launcher plugin.

First you need to install karma-cli so you can run 'karma' command on console and then its dependencies.


```
npm install -g karma-cli

npm install karma --save-dev

npm install karma-chrome-launcher --save-dev

```

And then you can start karma using “karma start” and run tests using the “karma run” command.

```
karma start
```

```
karma run
```
(this should be run on a new console)


### Screens

![Conway](https://github.com/vmarinov2013/conway/blob/master/run.png)

![Test](https://github.com/vmarinov2013/conway/blob/master/test1.png)
