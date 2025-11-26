# UE TCP Socket Plugin
Based on [CodeSpartan UE4TcpSocketPlugin](https://github.com/CodeSpartan/UE4TcpSocketPlugin).
Tcp Socket Plugin for Unreal Engine facilitates communication with a TCP server purely in blueprints. Client-only functionality.
Works on UE4 and UE5 

# List of Features
- Multiple connections
- Uses instance subsystem
- Multi-threading: each connection runs on its own thread
- Detects disconnects as soon as they happen
- Event dispatchers: OnConnected, OnDisconnected (also triggers when connection fails), OnMessageReceived
- Serialize and deserialize basic types: UInt8, Int32, Int64, Float, String
- Free and open source under MIT license

# Usage in Blueprints
Create a blueprint and use these nodes:
![Alt text](/functionality.png?raw=true "Functionality")


# Platforms
Intended for all platforms that support sockets and multithreading, which is most of them, except HTML5. <br />
Tested on platforms: Windows
