# Halo-Halo Hacienda

`HaloHaloHacienda.rbxlx` is a compact, playable Roblox place for the Filipino cozy-cooperative farm game concept.

## Included

- Normal-sized barangay map with a central plaza, river, walkable ancestral home, kusina, shrine, and six evenly spaced player plots.
- Script-built models for buildings, mango trees, crop plants, and karabao replace the former placeholder blocks.
- Farming interaction: plant and harvest nine crop beds per plot.
- Karabao pet interaction for bonus Ngiti.
- Kusina cooking and spirit order interactions.
- Server-wide Bayanihan event every 15 seconds, with a 35-second community task and a three-helper success target.
- Automatic plot assignment for up to six active players.
- Client HUD for plot assignment, Ngiti, spirit orders, toasts, and the Bayanihan progress bar.

## Open and publish

1. Open `HaloHaloHacienda.rbxlx` in Roblox Studio.
2. In **Build** mode, the serialized Hacienda folder under Workspace contains the editable preview map. Select parts or models and use the Move, Scale, and Rotate tools to customize it manually.
3. Press **Play** to test the farm loop. Use **Start** with multiple players to test Bayanihan.
4. Set the experience name, thumbnail, and permissions in **Game Settings**.
5. Use **File > Publish to Roblox** to create or update the live experience.

The place keeps an editor-visible serialized map for manual building. The server script rebuilds its gameplay version when Play starts so prompts, crops, animals, and player state are initialized consistently. Roblox Studio is still required for the final account-specific publish step.