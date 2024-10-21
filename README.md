# Wonder-RSTB-Upgrader
A tool to upgrade your Super Mario Bros. v0 (v1.0.0) RSTB files to v65536 (v1.1.1) RSTB files.

# Tutorial
First at all, you need to export your Super Mario Bros. Wonder NSP/XCI to the RomFS filesystem with its v65536 (v1.0.1) files.

Then you need to download the program “[TotkRSTB](https://github.com/VelouriasMoon/TotkRSTB)”, which allows you to export RSizeTables to YAML, and backwards.

Move the program files to the folder of this program. Now Drag and Drop “ResourceSizeTable.Product.100.rsizetable.zs” and “ResourceSizeTable.Product.101.rsizetable.zs” to “TotkRSTB.exe”.

It allows to create “ResourceSizeTable.Product.100.rsizetable.yaml” and “ResourceSizeTable.Product.101.rsizetable.yaml” for one. Now you have to place both YAML files into the “Vanilla” folder of this program.

Afterwards, you have to place your modded “ResourceSizeTable.Product.100.rsizetable.zs” in the same folder, where is “RSTB-Upgrader.py” located.

It will apply the changes from the modded RSizeTable to the Vanilla “ResourceSizeTable.Product.101.rsizetable.yaml” file, and export it as a “ResourceSizeTable.Product.101.rsizetable.zs” file.

After this process is done, you are ready to use the file for your mods.

# Credits
This tool was created by ChatGPT. chico88959 (@chico88959 on Discord) made the prompts for creating this progam by ChatGPT.
