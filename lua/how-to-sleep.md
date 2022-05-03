# How to sleep

```lua
os.execute("sleep 10")
```

- `os.execute` - execute system comman
- `sleep` - will sleep for specified amount of seconds
- `10` - we're going to sleep for 10 seconds

## Example: 
```lua
print(os.date("*t").sec)
os.execute("sleep 2")
print(os.date("*t").sec)
```
```
35
37

```

## Additional keywords
- wait

link_youtube: https://youtu.be/5TaW_yWuQH0
