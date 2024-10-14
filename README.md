# DKING ANTIBUMP

## DESCRIPTION

### Fix Vehicles Speeds Gain.

## CHANGES

* Removes speed ​​gains when going over bumps, potholes, and the like.
* Removes speed ​​gain when using double clutching.

## PURCHASE

* [TEBEX](https://stfly.me/antibumptebex)

## HOW TO INSTALL

* [Download](https://stfly.me/keymasterassets) script;
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

## PREVIEW

### Coming soon...

## Discord

### [Dking Warehouse](https://stfly.me/dkingwarehouse)

# COPYRIGHT

## BY [DKING](https://stfly.me/githubdking) 2024 © 
