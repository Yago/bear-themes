# 🐻 Bear themes

This is a playground to edit how Bear app looks like.

## Edit 

Based on the fonts/colors themes located on `/Applications/Bear.app/Contents/Resources/`, copy and/or edit it under the `./themes` directory.

For icons, you can update the `AppIcon.icns` and the `Assets.car` (using [ThemeEngine](https://github.com/alexzielenski/ThemeEngine))

## Deploy

Simply execute the following command (custom alias recommended) and voilà :

```bash
$ sudo cp -r /your/projet/path/themes/* /Applications/Bear.app/Contents/Resources/
```

**You must re-run the command after new Bear app updates*