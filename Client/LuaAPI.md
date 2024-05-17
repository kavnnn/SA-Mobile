
## Lua Loader

### Script
| Name | Use             |
| :-------- | :------- |
| `ScriptName` | Lua/Script Name |
| `ScriptAuthor` | The one who created the Lua/Script |
| `ScriptVersion` | Current version of the Lua/Script |
| `ScriptDescription` | Description of a Lua/Script |

### SAMP
| Function | Called When                |
| :-------- | :------- |
| `OnSAMPPreload` | SA Mobile is preloading |
| `OnSAMPStarted` | When the client fully loaded some functions. |
| `OnSAMPClose` | Called when the Game crash or closed |
| `OnConnect` | When the client is about to connect to a server |

### Interface
| Function | Called When                |
| :-------- | :------- |
| `OnInterfaceLoad` | Interface loaded the font and initialized some things |
| `RenderInterface` | Called when the interface is rendering. |

### Function
| Name | Use             |
| :-------- | :------- |
| `PrintLog` | Used to write/print a text |
| `SendClientMessage` | Send a message to the client itself |

### Memory
| Name | Use             |
| :-------- | :------- |
| `CastAddress` | Cast a function using the address. |
| `WriteMemory` | ... |
| `ReadMemory` | ... |
| `UnProtect` | ... |
| `MakeRET` | ... |
| `MakeNOP` | ... |
