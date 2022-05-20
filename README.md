# BEASTscripts

A place to store some scripts that might be useful

`manySimSeqXML` takes a `template.XML` and a `sequence-generator.xml` and creates N replications of `template.XML` with sequences generated from `sequence-generator.xml`

## Arguments

- `-g` specify `sequence-generator.xml`

- `-t` template XML (1 or more)

- `n` number of replications

- `f` force continue (default is to interactively check options)

- `i`  interactive mode (prompts for inputs)


## Example

`$ manySimSeqXML -g gen.xml -t rep0_160x1000_25.xml -t rep0_160x1000_test.xml  -n 3 -f`