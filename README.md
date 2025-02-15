# SPEED GAIN FIX [STANDALONE]

<div align="center">
<img src="https://github.com/Dking07/fivem-backup/blob/main/SPEED%20GAIN%20FIX.png" width="500px" />
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
* Add 'ensure dk_speed_gain_fix' (without quotes) to server.cfg.

## HOW TO USE

### To work, you need to modify the handlings that you want the script to take effect on.

### Modifications

* Remove the 'fDownforceModifier' line if it exists; (It's not necessary, but I recommend it)
* Add CCarHandlingData in the SubHandlingData section, like this:
    ```
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
<img src="https://cdn.discordapp.com/attachments/1295245827039563866/1315403103490805801/config_512.png?ex=67a7b39a&is=67a6621a&hm=415c764cc7af0923ca13b7d405d38296293b01d8eb6d5594a0cb10b27fed9553&" width="500px" />
</div>

## PREVIEW

* [YouTube](https://www.youtube.com/watch?v=fsVIcKNVZi0)

## Discord

### [Dking Warehouse](https://discord.gg/Rw6vjcXspG)

## CHANGELOGS

### 1.1

* Changed the method for selecting flags, now each flag has an identifier;
* Added a blacklist to include vehicles that will not be affected by the flags, even if they have 'CCarHandlingData' present in their handling;
* Changed the logic of applying flags.

### 1.2

* Added presets option. Now you can create presets with specific flags and vehicles.

# COPYRIGHT

## BY [DKING](https://github.com/Dking07) 2025 ©