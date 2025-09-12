# SPEED GAIN FIX [STANDALONE]

<div align="center">
<img src="https://github.com/Dking07/fivem-speed-gain-fix/blob/main/thumb.png" width="500px" />
</div>

## DESCRIPTION

### Fix Vehicles Speed Gain.

## CHANGES

* Removes speed gains when going over bumps, potholes, and the like.
* Removes speed gain when using double clutching.
* Remove tire related bugs, such as the off-road tire increasing grip and preventing the vehicle from being lowered by shooting the wheels/suspension.

## GET NOW

* [DOWNLOAD](https://dking.tebex.io/package/6575212)

## HOW TO INSTALL

* [Download](https://keymaster.fivem.net/asset-grants) script;
* Place it in the resources folder;
* Add 'ensure dking_speed_gain_fix' (without quotes) to server.cfg.

## HOW TO USE

### To work, you need to modify the handlings that you want the script to take effect on.

### Modifications

* Remove the 'fDownforceModifier' line if it exists; (It's not necessary, but I recommend it)
* Add CCarHandlingData in the SubHandlingData section, like this:
    ```xml
    <SubHandlingData>
        <Item type="CCarHandlingData">
        </Item>
        <Item type="NULL" />
        <Item type="NULL" />
    </SubHandlingData>
    ```

## CONFIG

* ### You can choose which effects will be applied through the configuration file.
<div align="left">
<img src="https://github.com/Dking07/fivem-speed-gain-fix/blob/main/config.png" width="500px" />
</div>

## PREVIEW

* [YouTube](https://www.youtube.com/watch?v=fsVIcKNVZi0)

## SUPPORT

### [Discord](https://discord.gg/Rw6vjcXspG)

## CHANGELOGS

### 1.1

* Changed the method for selecting flags, now each flag has an identifier;
* Added a blacklist to include vehicles that will not be affected by the flags, even if they have 'CCarHandlingData' present in their handling;
* Changed the logic of applying flags.

### 1.2

* Added presets option. Now you can create presets with specific flags and vehicles.

### 1.3

* Improved the way flags are applied.

### 1.4

* Added a alternative to Disable Double Clutch.

### 1.4.2

* Added a blacklist for vehicles that will not be affected by the alternative to Disable Double Clutch.

### 1.4.3

* Improved `DisableDoubleClutch`.

# COPYRIGHT

## BY [DKING](https://github.com/Dking07) 2025 ©