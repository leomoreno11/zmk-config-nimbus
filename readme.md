<div align="center">
    <p><img width="320" alt="Totem Logo" src="https://raw.githubusercontent.com/GEIGEIGEIST/TOTEM/main/docs/images/TOTEM_logo_dark.svg"/></p>
</div>

<div align="center">
    <pre>
    ===================================================================
    ███▄▄▄▄    ▄█    ▄▄▄▄███▄▄▄▄   ▀█████████▄  ███    █▄     ▄████████
    ███▀▀▀██▄ ███  ▄██▀▀▀███▀▀▀██▄   ███    ███ ███    ███   ███    ███
    ███   ███ ███▌ ███   ███   ███   ███    ███ ███    ███   ███    █▀ 
    ███   ███ ███▌ ███   ███   ███  ▄███▄▄▄██▀  ███    ███   ███       
    ███   ███ ███▌ ███   ███   ███ ▀▀███▀▀▀██▄  ███    ███ ▀███████████
    ███   ███ ███  ███   ███   ███   ███    ██▄ ███    ███          ███
    ███   ███ ███  ███   ███   ███   ███    ███ ███    ███    ▄█    ███
     ▀█   █▀  █▀    ▀█   ███   █▀  ▄█████████▀  ████████▀   ▄████████▀ 
    =================== A minimal & stealth Keyboard ==================
    </pre>
</div>

<div align="center">
    <p><img width="800" alt="All Black totem build" src="https://github.com/GEIGEIGEIST/TOTEM/blob/main/docs/images/TOTEM_layout.svg"/></p>
</div>

<img width="350" src="https://github.com/leomoreno11/leomoreno11/blob/main/materials/cybersigilism.jpeg" align="right">

<samp>
nimbus is my personal keyboard project. this keyboard will be modified and upgraded over the years
<br>
<br>
info:
<ul>
  <li> all made in 3d printing
  <li>switches: lowprokb ambient nocturnal 20g linear switches</li>
  <li>keycaps: pseudoky // chocfox</li>
  <li>wireless all the way</li>
  <li>all black!</li>
  <li>it also will have a carrying case</li>
</ul>

HOW TO USE

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
