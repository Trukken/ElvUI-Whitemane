# ElvUI - Wrath of the Lich King (3.3.5a) - Whitemane Frostmourne

ElvUI backport for Whitemane Frostmourne realm.

Any bug/issue can be reported in the [issues](https://github.com/Trukken/ElvUI-Whitemane/issues) tab.

#### All credit goes to the original author: https://github.com/ElvUI-WotLK/ElvUI

---

## Screenshots:

<a href="https://user-images.githubusercontent.com/590348/77227057-4d9ec400-6b8e-11ea-8672-29789434b9fe.jpg">
<img src="https://user-images.githubusercontent.com/590348/77227055-4bd50080-6b8e-11ea-975e-a68784d34327.jpg" align="right" width="48.5%">
</a>
<a href="https://user-images.githubusercontent.com/590348/77227304-65774780-6b90-11ea-9f64-432786d2a597.jpg">
<img src="https://user-images.githubusercontent.com/590348/77227077-98b8d700-6b8e-11ea-9822-f30103eca56b.jpg" width="48.5%">
</a>

<a href="https://user-images.githubusercontent.com/590348/77227091-bc7c1d00-6b8e-11ea-8c4f-29029a0b750a.jpg">
<img src="https://user-images.githubusercontent.com/590348/77227094-bdad4a00-6b8e-11ea-91a6-d134d7f01d8d.jpg" align="right" width="48.5%">
</a>
<a href="https://user-images.githubusercontent.com/590348/77227309-74f69080-6b90-11ea-9aa1-95c760340e9d.jpg">
<img src="https://user-images.githubusercontent.com/590348/77227311-76c05400-6b90-11ea-8704-dfb0cfd1dd3c.jpg" width="48.5%">
</a>

<a href="https://user-images.githubusercontent.com/590348/77227322-9192c880-6b90-11ea-9944-b9ae42e19431.jpg">
<img src="https://user-images.githubusercontent.com/590348/77227324-935c8c00-6b90-11ea-88ad-96f05a23b3f6.jpg" align="right" width="48.5%">
</a>
<a href="https://user-images.githubusercontent.com/590348/77227328-a53e2f00-6b90-11ea-8dd4-a8d7287185e8.jpg">
<img src="https://user-images.githubusercontent.com/590348/77227329-a707f280-6b90-11ea-9395-3bbc665a3593.jpg" width="48.5%">
</a>


## Installation:

1. Download **[Latest Version](https://github.com/Trukken/ElvUI-Whitemane/releases/latest)**
2. Unpack the Zip file
3. Open the folder "ElvUI-(#.##)"
4. Copy (or drag and drop) **ElvUI** and **ElvUI_OptionsUI** into your Wow-Directory\Interface\AddOns
5. Restart WoW

## Plugins:
[ElvUI_Enhanced](https://github.com/ElvUI-WotLK/ElvUI_Enhanced)
<br />
[ElvUI_AddOnSkins](https://github.com/ElvUI-WotLK/ElvUI_AddOnSkins)
<br />
[ElvUI_AuraBarsMovers](https://github.com/ElvUI-WotLK/ElvUI_AuraBarsMovers)
<br />
[ElvUI_BagControl](https://github.com/ElvUI-WotLK/ElvUI_BagControl)
<br />
[ElvUI_CastBarOverlay](https://github.com/ElvUI-WotLK/ElvUI_CastBarOverlay)
<br />
[ElvUI_CustomTags](https://github.com/ElvUI-WotLK/ElvUI_CustomTags)
<br />
[ElvUI_CustomTweaks](https://github.com/ElvUI-WotLK/ElvUI_CustomTweaks)
<br />
[ElvUI_DTBars2](https://github.com/ElvUI-WotLK/ElvUI_DTBars2)
<br />
[ElvUI_DataTextColors](https://github.com/ElvUI-WotLK/ElvUI_DataTextColors)
<br />
[ElvUI_EnhancedFriendsList](https://github.com/ElvUI-WotLK/ElvUI_EnhancedFriendsList)
<br />
[ElvUI_ExtraActionBars](https://github.com/ElvUI-WotLK/ElvUI_ExtraActionBars)
<br />
[ElvUI_LocPlus](https://github.com/ElvUI-WotLK/ElvUI_LocPlus)
<br />
[ElvUI_MicrobarEnhancement](https://github.com/ElvUI-WotLK/ElvUI_MicrobarEnhancement)
<br />
[ElvUI_RaidMarkers](https://github.com/ElvUI-WotLK/ElvUI_RaidMarkers)
<br />
[ElvUI_SwingBar](https://github.com/ElvUI-WotLK/ElvUI_SwingBar)
<br />
[ElvUI_VisualProcs](https://github.com/ElvUI-WotLK/ElvUI_VisualProcs)
<br />

-- Please Note: These plugins were not tested against Whitemane Frostmourne realm.

## Commands:

    /ec or /elvui     Toggle the configuration GUI.
    /rl or /reloadui  Reload the whole UI.
    /moveui           Open the movable frames options.
    /bgstats          Toggles Battleground datatexts to display info when inside a battleground.
    /hellokitty       Enables the Hello Kitty theme (can be reverted by repeating the command).
    /hellokittyfix    Fixes any colors or borders to default after using /hellokitty. Optional Use.
    /harlemshake      Enables Harlem Shake april fools joke. (DO THE HARLEM SHAKE!)
    /egrid            Toggles visibility of the grid for helping placement of thirdparty addons.
    /farmmode         Toggles the Minimap Farmmode.
    /in               The input of how many seconds you want a command to fire.
                          usage: /in <seconds> <command>
                          example: /in 1.5 /say hi
    /enable           Enable an Addon.
                          usage: /enable <addon>
                          example: /enable AtlasLoot
    /disable          Disable an Addon.
                          usage: /disable <addon>
                          example: /disable AtlasLoot

    ---------------------------------------------------------------------------------------------------------------
    -- Development ------------------------------------------------------------------------------------------------
    ---------------------------------------------------------------------------------------------------------------
    /etrace           Toggles events window.
    /luaerror on      Enable luaerrors and disable all AddOns except ElvUI.
    /luaerror off     Disable luaerrors and re-enable all AddOns disabled within that session.
    /cpuimpact        Toggles calculations of CPU Impact. Type /cpuimpact to get results when you are ready.
    /cpuusage         Calculates and dumps CPU usage differences (module: all, showall: false, minCalls: 15, delay: 5).
    /frame            Command to grab frame information when mouseing over a frame or when inputting the name.
                          usage: /frame (when mousing over frame) or /frame <name>
                          example: /frame WorldFrame
    /framelist        Dumps frame level information with children and parents. Also places info into copy box.
    /framestack       Toggles dynamic mouseover frame displaying frame name and level information.
    /resetui          If no argument is provided it will reset all frames to their default positions.
                      If an argument is provided it will reset only that frame.
                          example: /resetui uf (resets all unitframes)


## Languages:

ElvUI supports and contains language specific code for the following gameclients:
* English (enUS)
* Korean (koKR)
* French (frFR)
* German (deDE)
* Chinese (zhCN)
* Spanish (esES)
* Russian (ruRU)