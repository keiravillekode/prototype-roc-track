# Exercism Roc Track

Exercism Exercises in Roc

## Setup

You'll need [install latest Roc version](https://www.roc-lang.org/install), that's all. You may also want to [install the Exercism CLI](https://exercism.org/cli-walkthrough) if you want to download the exercises and submit your solutions easily.

You can test that Roc is properly installed by executing `roc version` in a terminal. If you also installed the Exercism CLI, then run `exercism version` to ensure that it's properly installed too.

## Exercise Layout

All the exercises live in the `exercises` directory. It has two subdirectories:

- `concept` contains exercises that explain the core concepts of the language.
- `practice` contains all the practice exercises, including the very first `hello-world` exercise.

Each exercise lives in its own subdirectory, such as `hello-world`.

In each exercise directory, you will find:

- a Roc module, such as `HelloWorld.roc`. In Roc, module names use PascalCase (i.e., each word starts with a capital letter).
- a test suite, such as `hello-world-test.roc`. Roc apps and test suites use kebab-case (i.e., just lowercase letters and `-`)
- an example solution, `.meta/Example.roc`

## Solving an exercise

Read the exercise's instructions, and edit the exercise's Roc module to solve the exercise. For example, to solve the `hello-world` exercise you will want to edit `HelloWorld.roc` and ensure that the `hello` function returns `"Hello, World!"`.

## Running the Tests

The Roc language comes with integrated test tools. To run the tests, you just need to open a terminal, go to the exercise's directory, and run the command `roc test <name>-test.roc`. For example, execute `roc test hello-world-test.roc` if you're testing your `hello-world` solution.

We hope you'll enjoy the exercises and fall in love with Roc!
