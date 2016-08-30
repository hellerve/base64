# base64

A minimal base64 library for and in zepto.

Documentation can be found under `docs/index.html`
or generated with zeps' `docgen` command.

## Usage

You can encode and decode strings with this library (UTF-8 is supported).

```clojure
(load "base64/base64")
(import-all "base64")

(base64:encode "l€l") ; => "bOKCrGw="
(base64:decode (base64:encode "l€l")) ; => "l€l"
```

<hr/>

Have fun!
