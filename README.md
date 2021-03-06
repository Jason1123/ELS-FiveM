# DISCLAIMER  
This project is in early development stages. You should expect bugs and/or issues. To effectively combat these issues we ask that you submit issues to the Issues board in this repository. See: https://github.com/FiveM-Scripts/ELS-FiveM/issues to submit an issue. It is important that if you test ELS for FiveM that you submit issues so that we may work to resolve these. Here's some things to consider:

- ELS vehicles are not yet supported.
- Lights are not yet supported.
- Custom cars will require VCF files to be created by following the [How to add custom Vehicles](docs/Add%20Cutom%20Vehicles.md) section.

# ELS FiveM

### Default Controls

|Action Key|Default Key|Default Binding
|---|---|---|
|Team Text Chat | Y key | Horn control|
|Select Unarmed Weapon | 1 Key | Manual tone 1
|Select Melee Weapon | 2 Key | Manual tone 2|
|Select Shotgun Weapon | 3 Key | Manual tone 3|
|Select Heavy Weapon | 4 Key | Manual tone 4|
|Select Special Weapon | 5 Key | Toggles Dual Siren Mode|
|Chat All| T Key|Goes to next tone or plays tone 1|
|Throw Grenade| G Key|Toggles main siren|
|Vehicle Horn | E Key | Toggles vehicle's emergency lights|

### How to install
1. Copy the `ELS-FiveM` folder to `cfx-server\resources\`
2. Add `ELS-FiveM` near the top of `AutoStartResources`

#### Important Notes

- When running the rcon command `restart ELS-FiveM` or `start ELS-FiveM`.  
Make sure you restart any resources that have ELS vehicles.
- Make sure ELS-FiveM is located above all ELS enabled vehicle stream resources in the `AutoStartResources` section in the `citmp-server.yml` file.

## Contribute
if you are a developer and  would like to contribute any help is welcome!   
The contribution guide can be found [here](CONTRIBUTING.md).

### How to Build and Test

1. `git clone https://github.com/FiveM-Scripts/ELS-FiveM.git`

2. Open `ELS-FiveM\src\ELS-for-FiveM.sln` in Visual Studio

3. Select `Release` and `Any CPU`  next to the Start button

4. In the menu bar under Build click on `Build Solution`

5. Copy all the files from `ELS-FiveM\src\bin\Release` to `cfx-server\resources\ELS-FiveM`

6. Add `ELS-FiveM` to `AutoStartResources` in `cfx-server\citmp-server.yml`
