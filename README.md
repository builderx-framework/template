## About @builderx-framework/template

> **Note:** This repository contains example app built using the Builderx framework.

# Installation

```shell
$ npx @builderx-framework/create-builderx-app todo-app

OR

$ npm init @builderx-framework/builderx-app todo-app
```

# Commands

## bx Command

```shell
$ node bx
Usage: bx [options] [command]

BuilderX core

Options:
  -V, --version   output the version number
  -h, --help      display help for command

Commands:
  hello-world     Prints Hello world!
  help [command]  display help for command
```

## hello-world command

```shell
$ node bx hello-world

Hello world!
```

## list app-services command

```shell
$ node bx add:service:app-service

┌─────────┬──────────────────────────────────────────┐
│ (index) │                  Values                  │
├─────────┼──────────────────────────────────────────┤
│   web   │ '@builderx-framework/bx-app-service-web' │
└─────────┴──────────────────────────────────────────┘
```

## add web app-service command

```shell
$ node bx add:service:app-service --service-name web --directory admin
```
