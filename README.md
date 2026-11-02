# CatChat
Hello! This is the source code for my linux app, (and more if your reading this later!) you will need a folder to install it but you prob can! how to make it a runnable flatpak? run these codes once you have both files (catchat folder): flatpak-builder --user --install --force-clean builddir org.cat.CatChat.json
flatpak run --env=DISPLAY=$DISPLAY org.cat.CatChat (can only talk to people on local network)
