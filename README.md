# Ark-Nucleus-IntegrationFiles

This repository contains the necessary files for ASA Mods to integrate with Ark-Nucleus. 
Modders for the game Ark Survival Ascended can download the `BaseContent` folder from this repository and drop it into their own mods folder to enable integration with Ark-Nucleus.

## Folder Structure

The `BaseContent` folder contains the following files:

- `MOD_NAME_CCA_Base.uasset`: This(CCA) file provides the central controlling functionality for mod integration with Ark-Nucleus.

- `MOD_NAME_JsonSave_Base.uasset`: This(SaveGameObject) file allows the CCA to save data in json format.

## Integration Instructions

To integrate your mod with Ark-Nucleus using the provided files, follow these steps:

1. Download the `BaseContent` folder from this repository.

2. Locate your mod's folder in the DevKit Plugins.

3. Drop the downloaded `BaseContent` folder into your mod's folder.

4. Launch the game and access the Nucleus provided Configuration UI to configure your mod with a user-friendly interface instead of using INI settings.

Please note that integrating with Ark-Nucleus requires the presence of the `Base Central Controlling Actor` and the `Save Game Object Blueprint with JSON Support` files in your mod's folder.

Happy modding!