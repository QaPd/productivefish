# Productive Fish
**A tactile resource-generation and automation mod for Minecraft (NeoForge 26.1.2) by Guestrax Interactive.**

Productive Fish brings kinetic, in-world resource generation to the ocean. Instead of hiding mechanics behind a 2D GUI, players build physical aquariums, automate mechanical feeding systems, and breed custom fish that generate resources directly into the world.

### For Modpack Creators
This mod is built from the ground up to be a tool for modpack developers. It is completely **data-driven via JSON**. You can easily:
*   Register custom fish variants (name, texture/color, preferred temperature).
*   Define specific diet requirements (input items).
*   Map complex breeding trees and mutations.
*   Set specific resource outputs and drop rates.

---

## Developer Installation & Building from Source

If you want to contribute to the code or build the mod from the source, clone this repository and open it in your preferred IDE (Cursor, IntelliJ IDEA, or Eclipse).

**Troubleshooting your Workspace:**
If at any point you are missing libraries in your IDE, or you've run into problems compiling, run the following commands in your terminal to rebuild the environment:
1. `gradlew clean` (resets the build environment without affecting your code)
2. `gradlew --refresh-dependencies` (refreshes the local cache and pulls the latest NeoForge libraries)

### Mapping Names
This project is configured to use the official mapping names from Mojang for methods and fields in the Minecraft codebase (a major feature of NeoForge 26.1+). These names are covered by a specific license. All modders and contributors should be aware of this license. For the latest license text, refer to the reference copy here:
[Mojang Mapping License](https://github.com/NeoForged/NeoForm/blob/main/Mojang.md)

### Additional Resources
*   **NeoForged Community Documentation:** https://docs.neoforged.net/
*   **NeoForged Discord:** https://discord.neoforged.net/