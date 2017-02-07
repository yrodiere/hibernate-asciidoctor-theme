# The Asciidoctor theme used for the documentations of the Hibernate projects

## Content

The theme contains:

 * CSS and resources used to customize the HTML output
 * a complete PDF theme, including specific fonts
 * some docinfo files shared by several projects

## Test

A test document is included to be able to test the output of the themes.

You can generate the test output in `target/asciidoctor` by running the following command:

```
mvn clean test
```

## License

The source code is licensed under the Apache License version 2.0.

This repository also contains external resources:

 * a copy of the default Asciidoctor PDF theme as a reference - MIT license
 * the Overpass font - SIL OPEN FONT LICENSE Version 1.1
 * several of the M+ fonts - see the included license file
