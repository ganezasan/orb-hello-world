# orb-hello-world

This is a sample of CircleCI orb.

## How to use

```
version: 2.1

orbs:
  hello: ganezasan/hello-world@dev:first

workflows:
  build:
    jobs:
      - hello/hello
```
