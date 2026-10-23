# Inventory Totem (Fabric, Minecraft 1.21.11)
Moves a Totem of Undying into your offhand only while your inventory screen is open.
Settings: `/autototem` or the "Totem Settings" button in the inventory. Config file: `config/inventorytotem.json`.

## Building with GitHub
1. Create a new GitHub repo and upload everything in this folder (including the hidden `.github` folder).
2. Open the **Actions** tab. The "Build" workflow runs on every push (or click "Run workflow").
3. When it finishes, open the run and download **inventorytotem-jar** under Artifacts.
4. Unzip it and put the jar in your `mods` folder, along with Fabric API.

No Gradle wrapper is needed; the workflow installs Gradle itself.
