# Search & Rescue and Firefighting Maritime Drone

Built solo in one day, mostly from parts salvaged from my anti-submarine maritime drone.

## How it worked

- **NodeMCU** — Wi-Fi control, navigation and servo control
- **Arduino Nano** — used for the firefighting system
- The Nano and NodeMCU communicated over serial TX/RX.
- A voltage-regulator circuit was used between the boards to account for their different logic-voltage levels (NodeMCU at 3.3 V and Arduino Nano at 5 V).
- The water pump was activated by a user command; automatic fire detection is not claimed here.
- The drone was controlled over Wi-Fi.

## Photos

Photos have not yet been added to this repository.

## Note on code

The original code was lost when I reused the parts and replaced my computer's drives.