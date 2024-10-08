# DKING ANTIBUMP

## DESCRIPTION

### Fix Vehicles Speeds Gain.

## CHANGES

* Removes speed ​​gains when going over bumps, potholes, and the like.
* Removes speed ​​gain when using double clutching.

## PURCHASE

* [TEBEX](https://dking.tebex.io/package/6491407)

## HOW TO INSTALL

* [Download](https://dking.tebex.io/package/6491407) script;
* Place it in the resources folder;
* Add 'ensure dk_antibump' (without quotes) to server.cfg.

## HOW TO USE

### To work, you need to modify the handlings that you want the script to take effect on.

### Modifications

* Remove the 'fDownforceModifier' line if it exists;
* Add CCarHandlingData in the SubHandlingData section, like this:
    ```
    <SubHandlingData>
        <Item type="CCarHandlingData">
        </Item>
        <Item type="NULL" />
        <Item type="NULL" />
    </SubHandlingData>
    ```

## PREVIEW

### Coming soon...

## Discord

### [Dking Warehouse](https://discord.gg/Rw6vjcXspG)

# COPYRIGHT

## BY DKING 2024©
