# DKING SPEED GAIN FIX [STANDALONE]

![](https://cdn.discordapp.com/attachments/1295245827039563866/1297647826863521802/SPEED_GAIN_FIX.png?ex=672c70f7&is=672b1f77&hm=b6a7d3e1124859f91b75ceed17227018e25a8f882d2165ff32fee3a6b5047cd0&)

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
![](https://cdn.discordapp.com/attachments/1295245827039563866/1301351286008057906/SPEED_GAIN_FIX_config.png?ex=672c1254&is=672ac0d4&hm=68758b2479afbce7f75b0efbdf2f0247e9ca39671f415f953c2106b824558cfb&)

## PREVIEW

* [YouTube](https://www.youtube.com/watch?v=fsVIcKNVZi0)

## Discord

### [Dking Warehouse](https://discord.gg/Rw6vjcXspG)

# COPYRIGHT

## BY [DKING](https://github.com/Dking07) 2024 ©
