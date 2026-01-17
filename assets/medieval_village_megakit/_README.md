# Notes
[Modular Sci-Fi Megakit](https://quaternius.com/packs/modularscifimegakit.html) - September 2024

## License
1. Copy `Sci-Fi Essentials Kit[Source].zip\License_Source.txt`
   to `assets\modular_scifi_megakit\License_Source.txt`

## Import Script
1. Copy `Modular Sci-Fi Megakit[Source].zip\Engine Projects\Godot.zip\Godot\addons\quaternius\quaternius_import_script.gd`
   to `assets\modular_scifi_megakit\quaternius_import_script.gd`
1. Open [assets\modular_scifi_megakit\quaternius_import_script.gd](/assets/modular_scifi_megakit/quaternius_import_script.gd#L11)
   - Find `res://addons/quaternius/materials/`
   Replace `res://assets/modular_scifi_megakit/materials/`

## Materials
1. Copy `Modular Sci-Fi Megakit[Source].zip\Engine Projects\Godot.zip\Godot\addons\quaternius\materials`
   to `assets\modular_scifi_megakit\materials`
1. Delete all `.import` files in `assets\modular_scifi_megakit\materials`
1. Open the `materials` folder using VSCode
   - Find `res://addons/quaternius/materials/`
   Replace `res://assets/modular_scifi_megakit/materials/`

## Models
1. Copy contents of `Modular SciFi MegaKit[Source].zip\glTF (Godot)`
  to `assets\modular_scifi_megakit`
1. Delete all `.png` files in `assets\modular_scifi_megakit` (they are already in `materials`)
1. Open the `modular_scifi_megakit` folder using VSCode
    - Find `"uri":"T_`
    Replace `"uri":"../materials/T_`
1. Open the project in Godot and let it import
1. Select all the `.gltf` files in `assets\modular_scifi_megakit`
1. Select the Import tab, scroll down to "Import Script", and select `res://assets/modular_scifi_megakit/quaternius_import_script.gd`
1. Select the "*Reimport" button
   - Godot 4.5+ will change it to a UID, which should be fine.

## Scenes
1. Copy contents of `Modular SciFi MegaKit[Source].zip\Engine Projects\Godot\modular-sci-fi-megakit\addons\quaternius\modularscifimegakit\L_Example.tscn`
  to ``assets\modular_scifi_megakit\L_Example.tscn``
   - L_Example.tscn
1. Open the Scene in Godot and click "Fix Depenedencies"

## Known Issue(s)
- `Prop_Cable1` not loading in the demo scene
    1. Copy `Modular SciFi MegaKit[Source].zip\Engine Projects\Godot\modular-sci-fi-megakit\addons\quaternius\modularscifimegakit\props\Prop_Cable1.bin` to `assets\modular_scifi_megakit\Props\Prop_Cable1.bin`
    1. Copy `Modular SciFi MegaKit[Source].zip\Engine Projects\Godot\modular-sci-fi-megakit\addons\quaternius\modularscifimegakit\props\Prop_Cable1.gltf` to `assets\modular_scifi_megakit\PropsProp_Cable1.gltf`
    1. Select the Import tab, scroll down to "Import Script", and select `res://assets/modular_scifi_megakit/quaternius_import_script.gd`
