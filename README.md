# FFXIV Launcher + Linux + OptiScaler + ReShade 
## How I installed FFXIV Launcher, OptiScaler (DLSS/FSR) & ReShade (Shaders) on Linux (I use CachyOS)

Most of the info and steps come from the [XIVLauncher & Dalamud Discord](https://discord.gg/3NMcUV5) with some info coming from having to do it like 5 times.

1. [Install FFXIV Launcher](https://github.com/goatcorp/FFXIVQuickLauncher)

2. Using [this script install ReShade](https://github.com/kevinlekiller/reshade-steam-proton) <sub>(Might need to copy d3dcompiler_47.dll to the xivlauncher's wine directory(~/.xlcore/wineprefix/drive_c/windows/system32)</sub>
   * **USE THE COMMAND** `RESHADE_ADDON_SUPPORT=1 ./reshade-linux.sh` TO RUN THE SCRIPT.
      * Do not follow steps to adjust your `WINEDLLOVERRIDES`

3. Download and install [OptiScaler](https://github.com/optiscaler/OptiScaler/wiki/Automated-Installation) via the automated installer.

4. Check to see everything is installed and works properly. **[INS]** is the menu key for OptiScaler and **[HOME]** is the menu key for ReShade.

### Optional Steps

5. Install [ipsuShade](https://github.com/ipsusu/ipsuShade#standalone-ipsushade-installation-steps--)
   * For better results also install [ReShadeEffectShaderToggler](https://github.com/4lex4nder/ReshadeEffectShaderToggler-FFXIV/blob/main/ReshadeEffectShaderToggler.ini) 
      * You will need to find the `.addon64` file for EffectShaderToggler **AND** *all the shaders ipsuShade says to install*, I have yet to find either other then copying from old installs. I have yet to check out [LeShade](https://github.com/Ishidawg/LeShade) which looks promising. 
