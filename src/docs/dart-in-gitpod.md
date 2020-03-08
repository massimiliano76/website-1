# Dart in Gitpod

## Installing Dart

To install the Dart SDK in Gitpod one must add the following to your [.gitpod.Dockerfile](https://gitpod.io/docs/config-docker)

```Dockerfile
RUN brew tap dart-lang/dart && brew install dart
```

## VSCode Extensions

### Dart

This Extension adds cool syntax highlighting

#### Before

![An image before the syntax highlighting](images/BeforeSyntaxHighlighting.png)

#### After

![An image after adding the syntax highlighting](images/AfterSyntaxHighlighting.png)


It adds [Intellisense](https://code.visualstudio.com/docs/editor/intellisense) support for autocompletion

![Dart intellisense example](images/DartIntellisenseExample.png)

## Try it

Here is a hello world example of a [Gitpodified](https://www.gitpod.io/blog/gitpodify/) project running in the browser, try it!

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/gitpod-io/Gitpod-Dart)
