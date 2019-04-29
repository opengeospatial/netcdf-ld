```
$ gem install asciidoctor
$ gem install --pre asciidoctor-pdf

$ asciidoctor -a data_uri standard_template/standard/standard_document.adoc -D build
$ asciidoctor-pdf -d book standard_template/standard/standard_document.adoc -D build
```
