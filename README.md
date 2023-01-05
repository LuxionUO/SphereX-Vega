# SphereX-Vega by Luxion
## An Internal Game Master Assistant for Sphere X
:radioactive: **WARNING:** This is a **pre-release**, the code is not stable yet. Please keep in mind that if you decide to install it in a live shard you will take your own risk for data corruption. You **MUST** use it only on a Test Shard until a Stable Version is released.

## Preview
![Vega](https://i.gyazo.com/567c88b30146eb16e2551ad8dea8e47e.png)

## Installation
In order to use correctly Vega you need to install the folder inside your SphereX `scripts` folder.

1. Download the `SphereX-Vega` archive and extract it;
2. `Copy` and `Paste` the `Vega` folder inside your `scripts/` folder;
3. `Copy` and `Paste` the `Vega_ShardCustom.scp` file in your `scripts/` folder;
4. Add the following code to `scripts/spheretables.scp`;
```csharp
// Vega Plugin
Vega/Config/
Vega/Core/
Vega/Dialogs/
Vega/Functions/
Vega/Lang/
Vega_ShardCustom.scp
```
5. Restart your Sphere Server.

To open the assistant digit `.vega` or `.v` in game.

## Changelogs

```diff
+ 5 January 2023
! 4:12am by Jhobean
Added: Buttons functions for MainDialog
Changed: Code optimization with "elif" instead of endif -> if
+ 4 January 2023
! 4:07pm by Luxion
Added: FastSwitch for vCharInfo to see Owner vInfo
Added: FastSwitch for vPlayerInfo to see Mount vInfo
! 3:43pm by Luxion
Added: 12 more slots on MainDialog
Changed: MainDialog headers
! 3:13am by Luxion
Fixed: <Uid.<Ref2.Owner.Name>> returns error, changed with <Ref2.Owner.Name>, Ref2 is already the right pointer.
Fixed: IsVendor has been moved after IsItem to avoid console errors.
! 3:07am by Jhobean
Added: vInfo_Char General Panel
! 2:07am by Luxion
Added: Stats & Skills on vInfo panel

+ 3 January 2023
! 23:58pm by Luxion
Added: support for shard customisation
Added: support for .v command
```
