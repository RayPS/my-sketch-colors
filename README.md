# My Sketch Colors

![screenshot](screenshot.png)

This is my color preset in Sketch app.

You can grab it if you like.

![inspect](inspect.png)


# Installation (Automatically)

Make sure your Sketch App is updated to the **NEWEST** version.

Copy and paste the following commands into Terminal and press return to run.

#### If you are using AppStore Version:
```
killall Sketch ; cd ~/Library/Containers/com.bohemiancoding.sketch3/Data/Library/Application\ Support/com.bohemiancoding.sketch3/ && [ -f "assets-v60.sketchpreset" ] && mv assets-v60.sketchpreset assets-v60.sketchpreset.backup && curl -O https://cdn.rawgit.com/RayPS/my-sketch-colors/master/assets-v60.sketchpreset && open /Applications/Sketch.app ; echo 'All Done!!!'
```

#### If you are using Out of AppStore Version:
```
killall Sketch ; cd ~/Library/Application\ Support/com.bohemiancoding.sketch3/ && [ -f "assets-v60.sketchpreset" ] && mv assets-v60.sketchpreset assets-v60.sketchpreset.backup && curl -O https://cdn.rawgit.com/RayPS/my-sketch-colors/master/assets-v60.sketchpreset && open /Applications/Sketch.app ; echo 'All Done!!!'
```


#### If you are using Sketch Beta:
```
killall Sketch\ Beta ; cd ~/Library/Containers/com.bohemiancoding.sketch3.beta/Data/Library/Application\ Support/com.bohemiancoding.sketch3/ && [ -f "assets-v60.sketchpreset" ] && mv assets-v60.sketchpreset assets-v60.sketchpreset.backup && curl -O https://cdn.rawgit.com/RayPS/my-sketch-colors/master/assets-v60.sketchpreset && open /Applications/Sketch\ Beta.app ; echo 'All Done!!!'
```
You can also [restore your colors](https://github.com/RayPS/my-sketch-colors/wiki/Restore-your-colors) if you regret it.

---

# Installation (Manually)

You can install the color preset manually if you feel strange to the commands.


1. Click on the menu `Plugins > Manage Plugins... > Click the gear icon > Show Plugins Folder...` in Sketch
2. Go to the parent folder named `com.bohemiancoding.sketch3` in Finder
3. Quit Sketch App (Must)
4. Download [assets-v60.sketchpreset](https://github.com/RayPS/my-sketch-colors/raw/master/assets-v60.sketchpreset) and put it into this folder
5. Open Sketch App.



# Contribution

If you got any better ideas,
Just send me a pull request or add an issue.
