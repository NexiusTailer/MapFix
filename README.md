# MapFix
**Texture bug fixes of the GTA San Andreas map**

This script fixes most of the texture bugs on the GTA SA map, such as passing through some walls, windows, floors etc.
In other words, it "adds" a collision to objects which didn't have it.

## List of fixed places

See the original thread for the list with all fixed places.

> `You can disable a fix of any of the places at the beginning of the filterscript or before the include.`  
> `For example, type following:`
```pawn
#define DISABLE_MAPFIX_PLACE_1 // So it will disable the fix №1
```

## How to install

Simply install to your project:
```bash
sampctl package install sampctl/mapfix
```

Include in your code and begin using the library:
```pawn
#include <mapfix>
```

> `Since v1.1.1 it supports Streamer Plugin by Incognito. Now objects can be created via CreateDynamicObject. To do this, just include streamer before mapfix`

## Testing

To test, simply run the package:
```bash
sampctl package run
```

And connect to `localhost:7777`.

## Credits
* Lordzy - Transparent/Invisible Objects tutorial  
* Pottus - advices and suggestions  
* Daniel_Cortez - tips, texture bug №146  
* ziggi - tips, texture bug №81 (mapping), 140  
* WoasryXxL - texture bug №2 (supplement), 42, 45, 49, 50, 52, 53  
* Romzes - texture bug №24, 30, 38, 41, 47 (supplement), 69, 70, 71, 101 (mapping), 117 (mapping), 127, 128 (mapping), 132 (mapping), 133  
* \_leon_lacartez_ - texture bug №142, 143 (mapping), 144 (mapping), 145 (mapping)  
* KrutoyKrosch - texture bug №4 (supplement), 96  
* KinG7 - texture bug №91, 92, 93, 94, 95  
* Jimmi - texture bug №40, 72 (mapping)  
* Kar - texture bug №2, 27 (supplement), 72, 137, 138  
* $continue$ - texture bug №102 (mapping), 129  
* reAL_ - texture bug №130 (mapping)  
* \[CM]Rider - texture bug №18  
* Vadyanga - texture bug №22  
* Admigo - texture bug №25  
* Crayder - texture bug №31  
* SoNik)) - texture bug №51  
* Vitalik_Gonsor - texture bug №54  
* brokens - texture bug №73  
* Sonic X - texture bug №131 (mapping), 134, 135, 136  
* Apec - texture bug №74 (mapping)  
* Nuttz - texture bug №139  
* xRadical3 - texture bug №141  
* Hare - texture bug №42 (supplement), 84 (supplement), 147  
* Southclaws - hosted this GitHub repo for years  
* m1n1vv - MapFix logo design

If you know about some places with texture bugs that haven't been fixed yet - please report them in the issues section.
