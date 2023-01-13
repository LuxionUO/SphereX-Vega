# SphereX-Vega by Luxion
## An Internal Game Master Assistant for Sphere X
:radioactive: **WARNING:** This is a **pre-release**, the code is not stable yet. Please keep in mind that if you decide to install it in a live shard you will take your own risk for data corruption. You **MUST** use it only on a Test Shard until a Stable Version is released.

## Preview
![image](https://user-images.githubusercontent.com/51728381/212334845-4adcce61-d872-4939-8656-f163e0e66b5a.png)
![image](https://user-images.githubusercontent.com/51728381/212335133-8ee71584-079b-4b2d-8396-3b1016ca0027.png)

![image](https://user-images.githubusercontent.com/51728381/212335068-a25f33d3-82bb-44c8-9d5e-0713d3d7ce71.png)

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
+ 6 January 2023
! by Jhobean
Added: Supermove dialog for item and mapping some button
Added: 6 Customs button can be easy mapped with custom function.
! by Luxion
Added: Account Creation form

+ 5 January 2023
! by Jhobean
Added: Buttons functions for MainDialog
Changed: Code optimization with "elif" instead of endif -> if
Added: Advanced section on main page
! by Luxion
Added: Vega now supports DamAdjusted.Lo and DamAdjusted.Hi to get lowest and highest DamAdjusted.
Added: Console reading in a dialog
Changed: improve search engine on account

+ 4 January 2023
! by Luxion
Added: FastSwitch for vCharInfo to see Owner vInfo
Added: FastSwitch for vPlayerInfo to see Mount vInfo
Added: 12 more slots on MainDialog
Changed: MainDialog headers
Fixed: <Uid.<Ref2.Owner.Name>> returns error, changed with <Ref2.Owner.Name>, Ref2 is already the right pointer.
Fixed: IsVendor has been moved after IsItem to avoid console errors.
Added: Stats & Skills on vInfo panel
! by Jhobean
Added: vInfo_Char General Panel

+ 3 January 2023
! by Luxion
Added: support for shard customisation
Added: support for .v command
```
