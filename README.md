# Neon White - Archipelago Manual

An **[Archipelago](https://github.com/ArchipelagoMW/Archipelago)** Manual implementation for Neon White, the speedrunning FPS.

All of the Python code comes from the base **[Manual For Archipelago](https://github.com/ManualForArchipelago/Manual)** repository. Without that project this implementation would not exist.

## How To Play

1. Go to the Releases page and download the most recent `.apworld` and `.yaml` files.
2. Place the `.apworld` file in the `worlds` folder of your Archipelago installation.
    - Default Windows Location: `C:\ProgramData\Archipelago\lib\worlds\`
3. Open the `.yaml` file in any text editor and modify the options to your liking.
    - All of the unique options available in this implementation are annotated. For additional options, refer to the **[official Archiepalgo guides](https://archipelago.gg/tutorial/#Archipelago)** on the main website.
4. Place the modified `.yaml` file in the `Players` folder.
    - Default Windows Location: `C:\ProgramData\Arhcipelago\Players\`
5. Generate a multiworld, either via running `ArchipelagoGenerate.exe` or via the Archipelago user interface.
    - Default Windows Location: `C:\ProgramData\Archipelago\output\`
7. Upload the generated ZIP file to the Archipelago website or host the multiworld from your own machine.
8. Within the Archipelago user intreface, press the "Manual Client" button underneath the "Clients" header.
9. From within the Manual Client, enter the server information and replace `Manual_{"game" from game.json}_{"player" from game.json}` with `Manual_NeonWhite_AHJV8N`.
10. Press the "Connect" button and enter your slot name and password.
11. Click on the "Manual" tab and you're all set!

## How To Create The APWorld File from Source

1. Archive the "manual_NeonWhite_AHJV8N" folder from the root of the project using the ZIP format.
    - Yes, you need to ZIP the parent folder. That is how Manual APWorld implementations are created.
2. Rename the ZIP archive from `manual_NeonWhite_AHJV8N.zip` to `manual_NeonWhite_AHJV8N.apworld`
