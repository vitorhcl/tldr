# iconv

> Converts text from one encoding to another.
> More information: <https://manned.org/iconv>.

- Convert a file [f]rom an encoding [t]o a specific encoding, and print to `stdout`:

`iconv -f {{from_encoding}} -t {{to_encoding}} {{path/to/input_file}}`

- Convert file to the current locale's encoding, and output to a file:

`iconv -f {{from_encoding}} {{path/to/input_file}} > {{path/to/output_file}}`

- [s]upress message errors about invalid characters:

`iconv -s -f {{from_encoding}} -t {{to_encoding}} {{path/to/input_file}}`

- Omit any characters that are invalid in the [c]odeset of the input file from the output:

`iconv -c -f {{from_encoding}} -t {{to_encoding}} {{path/to/input_file}}`

- [l]ist supported encodings:

`iconv -l`
