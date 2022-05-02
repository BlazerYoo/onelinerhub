# Convert hex to string

```lua
string.format("%#x", 0xaf)
```

- `string.format` - formats string with a given set of rules
- `%#x` - treat given variable as hex number
- `0xaf` - hex value to convert to string

group: convert_str

## Example: 
```lua
hex = 0xaf
print(string.format("%#x", hex))
```
```
0xaf

```

link_youtube: https://youtu.be/3Fv-7SSkCr4
