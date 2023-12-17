# YinYout

YinYout (YAML in YAML out) is a UNIX tool that reads YAML as programs from stdin and writes interpretations as YAML to stdout.

## Features
* The same input always produces the same output
* Diagrams
* Highly composable in process pipelines
* Reactive processing
* Works with any YAML file

A diagram is a graphical representation of the YAML file as a program and its interpretation. Working with pictures intuitively leads to writing readable code.

Streams are defined as part of the YAML spec and leveraged in streamed processing. A document stream is split by `---`. Each document is combined with its left and right, reacting when a new document arrives.
