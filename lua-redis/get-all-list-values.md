# Get all list values

```lua
local redis = (require 'redis').connect('127.0.0.1', 6379)
local list = redis:lrange('list_key', 0, -1)
```

- `require 'redis'` - load [lib:Redis](https://onelinerhub.com/lua-redis/how-to-install-lua-redis-module) module for Lua
- `connect` - connect to Redis server
- `'127.0.0.1', 6379` - Redis host and port to connect to
- `:lrange` - gets values of specified list
- `list_key` - key name of the Redis list to get
- `0, -1` - returns all list values

group: list

## Example: 
```lua
local redis = (require 'redis').connect('127.0.0.1', 6379)
local list = redis:lrange('list4', 0, -1)
print(table.concat(list, ', '))
```
```
d, c

```

link_youtube: https://youtu.be/QV8Q4tDlpmU
