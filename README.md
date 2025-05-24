# ATRSwap

### Automatic Tool Swap on Attack

ATRSwap is a simple client-side Fabric mod that automatically swaps your hotbar slot to a designated "swapping" slot when you attack an entity, then instantly swaps back to your "original" slot after one tick. This is useful for quickly switching to a specific tool (like an axe) to attack a mob (e.g., an Enderman) while keeping your primary weapon (e.g., a sword) in your main hand for general combat.

## ✨ Features

*   **Automatic Hotbar Swap:** Seamlessly switches your selected hotbar slot when you left-click to attack an entity.
*   **Configurable Slots:** Easily set your "original" and "swapping" hotbar slots (1-9) using a dedicated keybinding.
*   **Instant Swap Back:** The mod automatically returns you to your "original" slot after just one game tick, ensuring minimal disruption to gameplay.
*   **Attack-Specific Trigger:** Only activates when you attack an entity, not when breaking blocks or using items.
*   **Client-Side Only:** Works without needing to be installed on the server.

## 🚀 How to Use

1.  **Install:** Place the `atrswap-<version>.jar` file into your Minecraft `mods` folder.
2.  **Open Minecraft:** Launch your game with the Fabric loader.
3.  **Configure Slots:**
    *   **Press the Configure Key:** By default, press **U** (can be changed in Controls options under `ATRSwap`).
    *   **Set Original Slot:** A message will appear in chat asking you to press a number key (1-9) for your "original" slot. This is the slot you'll normally be on, and from which the swap will initiate.
    *   **Set Swapping Slot:** After setting the original slot, another message will appear asking for your "swapping" slot. This is the slot the mod will switch to when you attack.
        *   **Note:** The swapping slot cannot be the same as the original slot.
    *   **Confirmation:** Once both slots are set, you'll receive a confirmation message in chat.
4.  **Enjoy!** Now, when you attack an entity while holding an item in your "original" slot, the mod will momentarily switch to your "swapping" slot, then immediately switch back.

## ⚠️ Important Notes

*   **Entity Attacks Only:** This mod **only** triggers when you perform a left-click attack on an **entity**. It will **not** activate for breaking blocks or using items (right-click actions).
*   **Client-Side Behavior:** As this is a client-side mod, the server is unaware of the rapid hotbar changes. This typically works fine but keep it in mind.
*   **"Fair Play" Disclaimer:** Some servers or players might consider automatic hotbar swapping to be an unfair advantage. Use this mod responsibly and be aware of server rules.

## 🛠️ Compatibility

*   **Minecraft:** 1.21.4 (and possibly other versions but untested)
*   **Loader:** Fabric
---
