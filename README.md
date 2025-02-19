# Lua Roblox Client for the MarcSync API

## Overview
The Lua Roblox Client for the MarcSync API allows you to interact with the MarcSync API using Lua within Roblox. It provides convenient functions and utilities for seamless integration with the MarcSync service.

## Installation
1. Clone or download the Lua Roblox Client repository.
2. Import the Lua Roblox Client module into your Roblox project.
3. Require the module in your Roblox scripts to start using the MarcSync API functionalities.

## Usage
```lua
-- Example code snippet for using the MarcSync API with the Lua Roblox Client

local MarcSyncClient = require("MarcSyncClient")

-- Initialize the MarcSync client
local client = MarcSyncClient.new("a.b.c")

-- Make API requests
local data = client:getCollection("testCollection"):getEntries({
  ["name"] = "marcii"
})[1]
print(data)

-- Update data
client:updateValues("example-key", "new-value")
```

## Documentation
For detailed information on how to use the Lua Roblox Client for the MarcSync API, please refer to the [documentation](https://docs.marcsync.dev).

## Contribution
Contributions are welcome! If you find any issues or have any suggestions, feel free to open an [issue](https://github.com/MarciiTheDev/marcsync-rbx-client/issues) or submit a [pull request](https://github.com/MarciiTheDev/marcsync-rbx-client/pulls).

## License
This project is licensed under the [MIT License](https://github.com/MarciiTheDev/marcsync-rbx-client/blob/main/LICENSE).
