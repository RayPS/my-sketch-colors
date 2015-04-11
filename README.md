# My Sketch Colors

![screenshot](screenshot.png)

This is my color preset in Sketch app.

You can grab it if you like.

![inspect](inspect.png)


# Installation (Automatically)

Make sure your Sketch App is updated to the newest version. 

Copy and paste the following commands into Terminal and press return to run.

#### If you are using AppStore Version:
```
killall Sketch ; cd ~/Library/Containers/com.bohemiancoding.sketch3/Data/Library/Application\ Support/com.bohemiancoding.sketch3/ && [ -f "assets-v55.sketchpreset" ] && mv assets-v55.sketchpreset assets-v55.sketchpreset.backup && curl -O https://cdn.rawgit.com/RayPS/my-sketch-colors/master/assets-v55.sketchpreset && open /Applications/Sketch.app ; echo 'All Done!!!'
```

#### If you are using Out of AppStore Version:
```
killall Sketch ; cd ~/Library/Application\ Support/com.bohemiancoding.sketch3/ && [ -f "assets-v55.sketchpreset" ] && mv assets-v55.sketchpreset assets-v55.sketchpreset.backup && curl -O https://cdn.rawgit.com/RayPS/my-sketch-colors/master/assets-v55.sketchpreset && open /Applications/Sketch.app ; echo 'All Done!!!'
```


#### If you are using Sketch Beta:
```
killall Sketch\ Beta ; cd ~/Library/Containers/com.bohemiancoding.sketch3.beta/Data/Library/Application\ Support/com.bohemiancoding.sketch3/ && [ -f "assets-v55.sketchpreset" ] && mv assets-v55.sketchpreset assets-v55.sketchpreset.backup && curl -O https://cdn.rawgit.com/RayPS/my-sketch-colors/master/assets-v55.sketchpreset && open /Applications/Sketch\ Beta.app ; echo 'All Done!!!'
```
You can also [restore your colors](https://github.com/RayPS/my-sketch-colors/wiki/Restore-your-colors) if you regret it.

---

# Installation (Manually)

You can install the color preset manually if you feel strange to the commands.


1. Click on the menu `Plugins > Reveal Plugins Folder...` in Sketch
2. Go to the parent folder named `com.bohemiancoding.sketch3` in Finder
3. Quit Sketch App (Must)
4. Download [assets-v55.sketchpreset](https://github.com/RayPS/my-sketch-colors/raw/master/assets-v55.sketchpreset) and put it into this folder
5. No more steps, open Sketch App.



# Contribution

If you got any better ideas,
Just send me a pull request or add an issue.
