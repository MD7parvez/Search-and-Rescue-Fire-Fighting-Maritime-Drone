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

![Search & Rescue and Firefighting Maritime Drone prototype](https://drive.google.com/uc?export=view&id=1yOxwG1xEKaKG5t8dVIzGnl28BYlWiQ7u)

[Open the original photo on Google Drive](https://drive.google.com/file/d/1yOxwG1xEKaKG5t8dVIzGnl28BYlWiQ7u/view?usp=drivesdk)

The image is embedded from Google Drive; it has not yet been uploaded as a file inside this repository.

## Note on code

The original code was lost when I reused the parts and replaced my computer's drives.