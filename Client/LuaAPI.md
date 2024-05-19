
## Lua Loader

### Script
| Name | Use             |
| :-------- | :------- |
| `ScriptName` | Lua/Script Name |
| `ScriptAuthor` | The one who created the Lua/Script |
| `ScriptVersion` | Current version of the Lua/Script |
| `ScriptDescription` | Description of a Lua/Script |

### SAMPFuncs
| Name | Called When                |
| :-------- | :------- |
| `OnSAMPPreload` | SA Mobile is preloading |
| `OnSAMPStarted` | When the client fully loaded some functions. |
| `OnSAMPClose` | Called when the Game crash or closed |

| Name | Use               |
| :-------- | :------- |
| `GetLocalPlayerID` | ... |
| `GetSlotState` | ... |
| `GetPlayerName` | ... |
| `SendClientMessage` | Send a message to the client itself |

### NetGame
| Name | Called When                |
| :-------- | :------- |
| `OnConnect` | When the client successfully connected to a server |
| `OnDisconnect` | When the client was disconnected from a server |

### Interface
| Name | Called When                |
| :-------- | :------- |
| `OnInterfaceLoad` | Interface loaded the font and initialized some things |
| `RenderInterface` | Called when the interface is rendering. |

### ImGui
| Name | Use             |
| :-------- | :------- |
| `ImGuiBegin` | ... |
| `ImGuiEnd` | ... |
| `ImGuiText` | ... |
| `ImGuiButton` | ... |
| `ImGuiSetNextWindowSize` | ... |
| `ImGuiTreeNodeEx` | ... |
| `ImGuiCheckbox` | ... |
| `ImGuiAddText` | ... |

### Function
| Name | Use             |
| :-------- | :------- |
| `PrintLog` | Used to write/print a text |

### Memory
| Name | Use             |
| :-------- | :------- |
| `CastAddress` | Cast a function using the address. |
| `WriteMemory` | ... |
| `ReadMemory` | ... |
| `UnProtect` | ... |
| `MakeRET` | ... |
| `MakeNOP` | ... |
| `GetGTAImage` | ... |
| `GetSAMPImage` | ... |

### GTA
| Name | Use             |
| :-------- | :------- |
| `ScriptCommand` | ... |

### BASS
| Name | Use             |
| :-------- | :------- |
| `BASS_StreamCreateFile` | ... |
| `BASS_ChannelPlay` | ... |
| `BASS_ChannelIsActive` | ... |
| `BASS_StreamFree` | ... |
| `BASS_Free` | ... |
