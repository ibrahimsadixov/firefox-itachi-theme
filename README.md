# My Firefox Theme
This is a custom Firefox theme made with `userchrome.css` and `usercontext.css`.

## How to install:
1. Navigate to your Firefox profile folder. (To find it, go to `about:profiles` and look for "Profile Folder").
2. Click on "Open Directory" in the "Root Directory".
3. Open the folder.
4. Create a folder called `chrome` if it doesn't already exist.
5. Place `userchrome.css`, `usercontext.css`, and any required `image` files (such as icons and background images) in the `chrome` folder.
   - **Note:** If your theme includes custom images (like icons, backgrounds, or other graphical elements), make sure to place them in the `chrome` folder and reference them correctly in the `userchrome.css` or `usercontext.css` files.
6. Open Firefox and go to `about:config`.
7. Search for `toolkit.legacyUserProfileCustomizations.stylesheets`.
8. Double-click it to set it to `true`.
9. Restart Firefox, and your custom theme will be applied.

## Notes:
- This theme is designed for Firefox's user interface customizations.
- Make sure that `toolkit.legacyUserProfileCustomizations.stylesheets` is set to `true` in `about:config` for the theme to work.
