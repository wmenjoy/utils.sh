# Shell Utils

This repo is intended to extend the shell and contain useful and readable functions
that help developers to maintaine there scripts easier and neatly.

The following packages (which basically functions) are available.
* **Console** : provides formatted printing to the console
* **Date** : provides rich date functionality
* **Import** : provides improved import over source command
* **Random** : provides readable way of using randoms

The next container based packages are also available
* **Aggregate** : provides the aggregate or set functionality
* **Map** : provides functionality over the assosiative type
* **Queue** : provides the queue type functionality
* **Stack** : provides the implementation and functionality of a stack

* **String** : provides string functionality with well-known methods

### How to install

Check out the repository and source the file which you want to use.

### How to use

```sh
source `queue.sh`
# I create a queue called fruits
queue create fruits
# put an element to queue
queue enqueue fruits apple
queue peek fruits
queue destroy fruits
```

### Contribute

1. If you are intended to contribute the project, please take a look at [shell script style guide](https://google.github.io/styleguide/shell.xml)
2. Fork this repository
3. Make your changes
4. Send a RP
