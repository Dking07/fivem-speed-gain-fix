# SPEED GAIN FIX [STANDALONE]

![](https://cdn.discordapp.com/attachments/1295245827039563866/1297647826863521802/SPEED_GAIN_FIX.png?ex=6723df37&is=67228db7&hm=d2ef2a11644fd2b9a47a68bdede0b414f279c0a48f86d4f232e8c4a12ea72d33&)

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
![](https://cdn.discordapp.com/attachments/1295245827039563866/1301351286008057906/SPEED_GAIN_FIX_config.png?ex=67242954&is=6722d7d4&hm=03d141c01886724ef1b3b580d665e3111b57e486f7cc85e3e6a4b435ce5c4b44&)

## PREVIEW

* [YouTube](https://www.youtube.com/watch?v=fsVIcKNVZi0)

## Discord

### [Dking Warehouse](https://discord.gg/Rw6vjcXspG)

# COPYRIGHT

## BY [DKING](https://github.com/Dking07) 2024 ©
