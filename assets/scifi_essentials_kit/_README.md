# Notes
[Sci-Fi Essentials Kit](https://quaternius.com/packs/scifiessentialskit.html) - November 2024

## License
1. Copy `Sci-Fi Essentials Kit[Source].zip\License_Source.txt`
   to `assets\scifi_essentials_kit\License_Source.txt`

## Import Script
1. Copy `Sci-Fi Essentials Kit[Source].zip\Engine Projects\Godot.zip\Godot\addons\quaternius\quaternius_import_script.gd`
   to `assets\scifi_essentials_kit\quaternius_import_script.gd`
1. Open [assets\scifi_essentials_kit\quaternius_import_script.gd](/assets/scifi_essentials_kit/quaternius_import_script.gd#L11)
   - Find `res://addons/quaternius/materials/`
   Replace `res://assets/scifi_essentials_kit/materials/`

## Materials
1. Copy `Modular Sci-Fi Megakit[Source].zip\Engine Projects\Godot.zip\Godot\addons\quaternius\materials`
   to `assets\modular_scifi_megakit\materials`
1. Delete all .import files in `assets\modular_scifi_megakit\materials`
1. Open the `materials` folder using VSCode
   - Find `res://addons/quaternius/materials/`
   Replace `res://assets/scifi_essentials_kit/materials/`

## Models
1. Copy contents of `Modular Sci-Fi Megakit[Source].zip\glTF`
  to `assets\scifi_essentials_kit`
1. Open the project in Godot and let it import
1. Select all the `.gltf` files in `assets\scifi_essentials_kit`
1. Select the Import tab, scroll down to "Import Script", and select `res://assets/scifi_essentials_kit/quaternius_import_script.gd`
   - Godot 4.5+ will change it to a UID, which should be fine.

## Scenes
1. Copy `Sci-Fi Essentials Kit[Source].zip\Engine Projects\Godot\sci-fi-essentials\addons\quaternius\Sci-FiEssentials\L_Overview.tscn`
  to `assets\medieval_village_megakit\L_Overview.tscn`
   - L_Overview.tscn
1. Open the Scene in Godot and click "Fix Depenedencies"

## Known Issues
- The items are glowing orange
    1. Open `materials\M_Base.tres`
        - Find `uniform float Emissive_Intensity = 6;` replace `uniform float Emissive_Intensity = 0;`
    1. In VSCode Find `shader_parameter/Emissive_Intensity = 6.0` and replace `shader_parameter/Emissive_Intensity = 6.0`
