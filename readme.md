<picture>
  <source media="(prefers-color-scheme: dark)" srcset="/docs/images/TOTEM_logo_dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="/docs/images/TOTEM_logo_bright.svg">
  <img alt="TOTEM logo font" src="/docs/images/TOTEM_logo_bright.svg">
</picture>

# Swedish QMK config for the Totem keyboard
Made to resemble the standard Swedish QWERTY layout. Most symbols and numbers are accessed from layers by holding either space (left thumb) or enter (right thumb), or a combination of both.  
Most symbols are placed in a way that would correspond to the approximate location on a standard sized keyboard Swedish keyboard.  
Gaming (wasd) keybinds can be toggled by pressing sdf simultaneously.  
Å, Ä and Ö are typed by pressing o+p, l+' and .+- respectively.  
Feel free to fork this yourself. I recommend editing the config with https://nickcoutsos.github.io/keymap-editor/.

## Forked from 
https://github.com/GEIGEIGEIST/qmk-config-totem

## How to use
- fork this repo
- `git clone` your repo, to create a local copy on your PC (you can use the [command line](https://www.atlassian.com/git/tutorials) or [github desktop](https://desktop.github.com/))
- adjust the totem.keymap file (find all the keycodes on [the zmk docs pages](https://zmk.dev/docs/codes/))
- `git push` your repo to your fork
- on the GitHub page of your fork navigate to "Actions"
- scroll down and unzip the `firmware.zip` archive that contains the latest firmware
- connect the left half of the TOTEM to your PC, press reset twice
- the keyboard should now appear as a mass storage device
- drag'n'drop the `totem_left-seeeduino_xiao_ble-zmk.uf2` file from the archive onto the storage device
- repeat this process with the right half and the `totem_right-seeeduino_xiao_ble-zmk.uf2` file.
