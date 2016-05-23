# base64

A minimal base64 library for and in zepto.

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
