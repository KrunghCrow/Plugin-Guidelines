**Example of a Basic setup for you `RUST Plugin`**

**Plugin Name** : ☑️ `"Test Plugin"` ❎ `"TestPlugin"` ❎ `"test plugin"`   
For consistancy use spacing in the plugin name , avoid `MakingOneLargeName` and try using short names that explains what a
plugin is ment to do.    

**Author** :  ☑️ `"Krungh Crow"` ❎  `"Made by krung(maintained by exampledev)"`    
Make the authors name as short as possible you can always mention collabs as notes.

**Version** :  ☑️ `"1.0.0"` ❎ `"1.0.0.0"`  ❎ `"1.0.0.0b"` ❎ `"1.0.0b"`  
* Using the Major.Minor.Patch format is clean and all you need , no need to have more or use lettering.
* A test version should start as `"0.0.1"`
* A released version should start with `"1.0.0"`

**Description** : ☑️ `"Example plugin for testing"` ❎ `"This is an awsome plugin with allot of text (not) hahaha"`    
Keep it short and simple without making it lengthy.

**Main class** : The `TestPlugin.cs` and `main class` need to be formatted the same to compile.

```cs
using Oxide.Core;

namespace Oxide.Plugins
{
    [Info("Test Plugin", "Krungh Crow", "1.0.0")]
    [Description("Example plugin for testing")]

    class TestPlugin : RustPlugin
    {
        Init()
        {
            Puts("Init trigger works");
        }
    }
}
```
