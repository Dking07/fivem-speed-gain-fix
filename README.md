# SPEED GAIN FIX [STANDALONE]

![](https://cdn.discordapp.com/attachments/1295245827039563866/1312264755586662430/SPEED_GAIN_FIX_2.png?ex=674bdd4a&is=674a8bca&hm=ca9ee97d00404b059a6605ec12b3761e1850a2bdae78f52f32225743bfe41207&)

## DESCRIPTION

### Fix Vehicles Speeds Gain.

## CHANGES

* Removes speed gains when going over bumps, potholes, and the like.
* Removes speed gain when using double clutching.
* Remove tire related bugs, such as the off-road tire increasing grip and preventing the vehicle from being lowered by shooting the wheels/suspension.

## DOWNLOAD

* [TEBEX](https://dking.tebex.io/package/6562200)

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
![](https://cdn.discordapp.com/attachments/1295245827039563866/1311196211927191593/config.png?ex=674b45e1&is=6749f461&hm=4aefcefbdcbf404b6a8f10376a2f345d78e9e57b1290602e1abdf0e2c6c22489&)

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
