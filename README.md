# Web-Types for Lit
Web-Types is a framework-agnostic format aimed at providing IDEs and other tools with the metadata 
information about the contents of a component library. Its powerful name patterns allow encoding 
information about web framework syntax or customizing code completion suggestions for large icon 
libraries in the IDEs that support Web-Types.

See [web-types](https://github.com/JetBrains/web-types) project

## Working with lit-web-types
`lit-web-types` project contains basic lit language definitions. To use it add dependency to your project.
```bash
npm i lit-web-types -D
```

If using IntelliJ or WebStorm, IDE restart might be needed after install to enable autocomplete.

## Web-Types generation
`lit-web-types` is designed to work with [`web-component-analyzer-webtypes`](https://github.com/jpradelle/web-component-analyzer/)
which can generate web-types definitions of your webcomponents by parsing your source files, needed to
enable completion of your components tags, attributes, properties, events and css properties.

See [web-component-analyzer-webtypes](https://github.com/jpradelle/web-component-analyzer/) and
[wca web-types dedicated page](https://github.com/jpradelle/web-component-analyzer/blob/HEAD/doc/web-types.md)
