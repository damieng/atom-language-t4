# atom-language-t4
This grammar adds support for the T4 text-transformation-tool syntax to Atom.

## Limitations

1. Only C# is supported (it should be possible to detect based on the template language attribute)
2. Output code is not normally syntax-highlighted (we'd need to detect output file name and dynamically include output)
3. Output code inside a { is highlighted as C# - this appears to be a limitation of reusing source.cs to highlight the C# code
