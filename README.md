# Vcdparse

Takes a VCD file and returns the final value of each variable in a pickled python dictionary.

## Usage

Use -i to specify an input file, vcdparse will output the dictionary in the same directory as the input file.
```bash
python 'filepath of vcdparse' -i 'filepath of vcd file'
```

You can specify an output file with -o.
```bash
python 'filepath of vcdparse' -i 'filepath of vcd file' -o 'filepath for output'
```

If you want to view the output in a readable format, use -v.
A text file will be created in the same directory as the input file.
```bash
python 'filepath of vcdparse' -i 'filepath of vcd file' -o 'filepath for output' -v
```
Here is how to read the text file after using -v:
```python
['signal_name', ['value', 'size']] 'module_scope'
```
