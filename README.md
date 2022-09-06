# minecrafthelpers

Some stuff to make being the father of a minecrafter a bit easier.


Applies to Minecraft Bedrock

Navigate to the app data folder 
```
%homepath%\AppData\Local\Packages
```
And then to the folder 
Microsoft.MinecraftUWP*

LocalState\games\com.mojang

Go to behavior packs to add stuff that can be added to any world

Once it is in there go to the world and behavior packs to do editing

You need to run the 

/reload command to see the changes.


Create a new folder in the behavior packs folder
Add a manifest.json with two unique uuids and names 

and add a folder called functions 

Add files called 

[functionname].mcfunction




Sample Manifest File 

```json 
{
  "header" : {
    "version" : [
      0,
      0,
      1
    ],
    "name" : "",
    "description" : "",
    "uuid" : ""
  },
  "modules" : [
    {
      "version" : [
        0,
        0,
        1
      ],
      "type" : "data",
      "description" : "",
      "uuid" : ""
    }
  ],
  "format_version" : 1
}
```