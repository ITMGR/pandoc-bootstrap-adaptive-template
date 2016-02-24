# pandoc bootstrap adaptive template

Copied from: (Would not be much worth as a fork): 

[https://github.com/tonyblundell/pandoc-bootstrap-template](https://github.com/tonyblundell/pandoc-bootstrap-template)

Includes a sticky adaptive menu and some other nice things:

Example (fetch latest pandoc README and transform to HTML)

    pandoc https://raw.githubusercontent.com/jgm/pandoc/master/README -o index.html -f markdown --template standalone.html --css template.css --toc --toc-depth 2

Start a server in current directory, e.g.: 

    php -S localhost:8080

Point a browser to http://localhost:8080

