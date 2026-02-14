# SPEED GAIN FIX [STANDALONE]

<div align="center">
<img src="https://github.com/user-attachments/assets/9856a559-9a5a-481e-aff9-0ccc52160636" width="500px" />
</div>

## DESCRIPTION

System for removing unrealistic speed gains from vehicles.

## CHANGES

* Removes speed gains when going over bumps, potholes, and the like.
* Removes speed gain when using double clutching.
* Remove tire related bugs, such as the off-road tire increasing grip and preventing the vehicle from being lowered by shooting the wheels/suspension.

## GET NOW

* [DOWNLOAD](https://dking.tebex.io/package/6575212)

## HOW TO INSTALL

* [Download](https://portal.cfx.re/assets/granted-assets) script;
* Place it in the resources folder;
* Add 'ensure dking_speedgainfix' (without quotes) to server.cfg.

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
<img src="https://github.com/user-attachments/assets/fa30b61a-4d57-43a4-bed1-4bdfd54a6e14" width="500px" />
</div>

## PREVIEW

* [YouTube](https://www.youtube.com/watch?v=fsVIcKNVZi0)

## SUPPORT

### [Discord](https://discord.gg/Rw6vjcXspG)

## CHANGELOGS

<details>
  <summary><h2 style="display: inline;">Expand</h2></summary>

  <details>
    <summary style="margin-left: 20px;"><h3 style="display: inline;">1.1</h3></summary>
    <ul style="margin-left: 20px;">
      <li>Changed the method for selecting flags, now each flag has an identifier;</li>
      <li>Added a blacklist to include vehicles that will not be affected by the flags, even if they have 'CCarHandlingData' present in their handling;</li>
      <li>Changed the logic of applying flags.</li>
    </ul>
  </details>

  <details>
    <summary style="margin-left: 20px;"><h3 style="display: inline;">1.2</h3></summary>
    <ul style="margin-left: 20px;">
      <li>Added presets option. Now you can create presets with specific flags and vehicles.</li>
    </ul>
  </details>

  <details>
    <summary style="margin-left: 20px;"><h3 style="display: inline;">1.3</h3></summary>
    <ul style="margin-left: 20px;">
      <li>Improved the way flags are applied.</li>
    </ul>
  </details>

  <details>
    <summary style="margin-left: 20px;"><h3 style="display: inline;">1.4</h3></summary>
    <ul style="margin-left: 20px;">
      <li>Added a alternative to Disable Double Clutch.</li>
    </ul>
  </details>

  <details>
    <summary style="margin-left: 20px;"><h3 style="display: inline;">1.4.2</h3></summary>
    <ul style="margin-left: 20px;">
      <li>Added a blacklist for vehicles that will not be affected by the alternative to Disable Double Clutch.</li>
    </ul>
  </details>

  <details>
    <summary style="margin-left: 20px;"><h3 style="display: inline;">1.4.3</h3></summary>
    <ul style="margin-left: 20px;">
      <li>Improved <code>DisableDoubleClutch</code>.</li>
    </ul>
  </details>

  <details>
    <summary style="margin-left: 20px;"><h3 style="display: inline;">1.4.6</h3></summary>
    <ul style="margin-left: 20px;">
      <li>Added class blacklist to <code>DisableDoubleClutch</code>.</li>
    </ul>
  </details>

  <details>
    <summary style="margin-left: 20px;"><h3 style="display: inline;">1.4.7</h3></summary>
    <ul style="margin-left: 20px;">
      <li>Improvements and optimizations in <code>DisableDoubleClutch</code>.</li>
    </ul>
  </details>
</details>

# COPYRIGHT

## BY [DKING](https://github.com/Dking07) 2026 ©