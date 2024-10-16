# DKING SPEED GAIN FIX [STANDALONE]

## DESCRIPTION

### Fix Vehicles Speeds Gain.

## CHANGES

* Removes speed ​​gains when going over bumps, potholes, and the like.
* Removes speed ​​gain when using double clutching.
* Remove tire related bugs, such as the off-road tire increasing grip and preventing the vehicle from being lowered by shooting the wheels/suspension.

## PURCHASE

* [TEBEX](https://dking.tebex.io/package/6491407)

## HOW TO INSTALL

* [Download](https://keymaster.fivem.net/asset-grants) script;
* Place it in the resources folder;
* Add 'ensure dk_antibump' (without quotes) to server.cfg.

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

* ### You can choose which flags will be applied through the configuration file.

## PREVIEW

### Coming soon...

## Discord

### [Dking Warehouse](https://discord.gg/Rw6vjcXspG)

# COPYRIGHT

## BY [DKING](https://github.com/Dking07) 2024 ©
