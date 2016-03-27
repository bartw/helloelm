# helloelm

```shell
npm install elm -g
elm package install evancz/elm-html
```

Hello.elm

```elm
import Html

main : Html.Html
main =
  Html.text "Hello"
```

```shell
elm reactor
```

browse to http://localhost:8000/