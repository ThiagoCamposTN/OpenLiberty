# Put your copy of GTA 3 here for debugging

When launched from Godot's editor, this project uses this directory for GTA 3 assets to make testing easier.

On Linux, instead of copying all GTA files, you can use a symbolic link from your GTA folder. For example, considering you are inside the `res://gta` folder and your GTA was installed in the default path via Steam, you can use the following command to make a pointer to the original game files (avoiding duplication of files):

```bash
ln -s $HOME/.local/share/Steam/steamapps/common/Grand\ Theft\ Auto\ 3/* .
```

---

When you build this project as standalone, you should put its executable and `.pck` files into your copy of GTA 3 and launch it from there.