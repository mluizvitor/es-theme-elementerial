# About Custom Backgrounds

To use custom background you need to load your own images inside `customBackground` folder located on Elementerial root directory. Your images need to be named after the desired videogame system. The name must the same used by your Operational System. Elementerial was made for AmberELEC (but is compatible with other systems running EmulationStation) and use the same names from tag `<theme></theme>` found in [es_system.cfg](https://github.com/AmberELEC/AmberELEC/blob/dev/packages/ui/emulationstation/config/es_systems.cfg).

For example: If you want to add a custom background for **Sega Genesis**, the image need to be renamed as `genesis.png`, for **Final Burn Neo**, `fbn.png`. If you want only one background for the whole theme, name your image as `general.png`. Elementerial accept images in `PNG` (.png), `JPEG` (.jpeg .jpg) and `WEBP` (.webp) formats.

Please, use the images inside [assets/systems/](assets/systems/) as a reference.

After placing your images inside `customBackground`, enable custom backgrounds in your device settings.
On AmberELEC, press `Start` to open system menu > Navigate to `UI Settings` > Change `Theme Set` to **es-theme-elementerial** > `Theme Configuration` > Change `Theme Background` to `Custom`. Exit to apply changes.

## Alternatives

If you prefer using a tool for that, you can use [Albedo Wallpaper Cropper](https://albedo-wallpaper-cropper.vercel.app/). AWC is a simple tool and easy to use. You can access its [README](https://github.com/mluizvitor/albedo-wallpaper-cropper/blob/master/README.md) to learn step by step how to prepare images and load them to the theme folder.

If you're concerned about privacy, this web app will never collect or send any information anywhere. The images loaded are saved locally on the browser database so you won't lose your progress. As an web app, it can be used offline after the first load.
