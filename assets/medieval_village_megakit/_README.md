# Notes
[Medieval Village MegaKit](https://quaternius.com/packs/medievalvillagemegakit.html) - January 2025

## License
1. Copy `Medieval Village MegaKit[Source].zip\License_Source.txt`
   to `assets\medieval_village_megakit\License_Source.txt`

## Import Script
1. Copy `Medieval Village MegaKit[Source].zip\Engine Projects\Godot.zip\Godot\addons\quaternius\quaternius_import_script.gd`
   to `assets\medieval_village_megakit\quaternius_import_script.gd`
1. Open [assets\medieval_village_megakit\quaternius_import_script.gd](/assets/medieval_village_megakit/quaternius_import_script.gd#L11)
   - Find `res://addons/quaternius/materials/`
   Replace `res://assets/medieval_village_megakit/materials/`

## Materials
1. Copy `Medieval Village MegaKit[Source].zip\Engine Projects\Godot.zip\Godot\addons\quaternius\materials`
   to `assets\medieval_village_megakit\materials`
1. Delete all .import files in `assets\medieval_village_megakit\materials`
1. Open the `materials` folder using VSCode
   - Find `res://addons/quaternius/`
   Replace `res://assets/medieval_village_megakit/`

## Models
1. Copy contents of `Medieval Village MegaKit[Source].zip\glTF (Godot)`
  to `assets\medieval_village_megakit`
1. Open the project in Godot and let it import
1. Select all the `.gltf` files in `assets\medieval_village_megakit`
1. Select the Import tab, scroll down to "Import Script", and select `res://assets/medieval_village_megakit/quaternius_import_script.gd`
   - Godot 4.5+ will change it to a UID, which should be fine.

## Scenes
1. Copy contents of `Medieval Village MegaKit[Source].zip\Engine Projects\Godot.zip\Godot\addons\quaternius\medievalvillagemegakit\L_SampleScene_1.tscn`
  to `assets\medieval_village_megakit\L_SampleScene_1.tscn`
   - L_SampleScene_1.tscn
1. Open the Scene in Godot and click "Fix Depenedencies"
