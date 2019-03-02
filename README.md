# SpouseStuff - A Stardew Valley mod
As the title suggests, this mod adds interactions to your spouse's stuff in the farmhouse of Stardew Valley. If you're married, of course.

## How to get it
For now, to install the mod you need to install and set up SMAPI for developers with Visual Studio 2017 and clone this repository and build it through VS. Once the 1.0 milestone has been reached a finished build will be available.

## How to work with it
ModEntry.cs contains a Dictionary with each spouse name and a corresponding ISpouseRoom object, as well as a button press event listener. To modify/add interactions for a specific spouse, edit their corresponding class in the Spouses folder. You can get the tileX, tileY and faceDirection values from the SMAPI console whenever you're in the farmhouse and use the action button somewhere.

## Supported spouses
So far, the following marriagable characters are supported in the mod:

 * Abigail
 * Alex
 * Harvey
 * Maru
 * Leah

The goal is to have all 12 possible spouses supported for the 1.0 release.