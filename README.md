# SPEED GAIN FIX [STANDALONE]

![](https://cdn.discordapp.com/attachments/1295245827039563866/1297647826863521802/SPEED_GAIN_FIX.png?ex=674777b7&is=67462637&hm=ced0d669e6f5d05da6e9df3746f5010c06552a85075d25043442abc7e0206b90&)

## DESCRIPTION

### Fix Vehicles Speeds Gain.

## CHANGES

* Removes speed gains when going over bumps, potholes, and the like.
* Removes speed gain when using double clutching.
* Remove tire related bugs, such as the off-road tire increasing grip and preventing the vehicle from being lowered by shooting the wheels/suspension.

## DOWNLOAD

* [TEBEX](https://dking.tebex.io/package/6511460)

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
![](https://cdn.discordapp.com/attachments/1295245827039563866/1311196211927191593/config.png?ex=6747fa21&is=6746a8a1&hm=de423a148144be9b9b22126e9047d801b6da4cd94355b805f3da61ba8119fa27&)

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

## BY [DKING](https://github.com/Dking07) 2024 ©
