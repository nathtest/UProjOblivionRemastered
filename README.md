## UProjOblivionRemastered

This is a working Unreal Engine project created from the UE4SS dump.
It allows blueprint modder to directly use native game class either from cpp or blueprint.

This only contains the cpp class from which all blueprint classes inherit. You still need to use Fmodel to create dummies of the assets you want to use.

# How to to use

- Build Unreal Engine 5.3.2 from source (check Unreal Engine doc)
- Download the project file
- Right click on the OblivionRemastered.uproject file and generate "Visual Studio project files"
- Open the project in Visual studio -> compile it
- Open the editor
- Create mod and Enjoy

Warning : This project was created for fun. If you want help with Unreal Modding join the various discord servers that exist.

If you found some error in the project setup, you can create a pull request. I'm also open if people want to contribute and/or maintain the project.

You can find example of basic Unreal assets recreated with the help of Fmodel (a mod loader, basic dummies for the player, npc, ui, how to spawn an npc, ect) in the branch [example](https://github.com/nathtest/UProjOblivionRemastered/tree/example).

# Unreal 5.3.2 source fix:

You will need to change the class UInputDeviceTriggerResistanceProperty in the file InputDeviceProperties.h by adding ENGINE_API to the definition.

![Image](https://i.ibb.co/fGdZXhRM/unreal-source-fix.png)


# Mod Loader

To load your blueprint mod, you will need a mod loader and for that you can use Simple Photo Mode that comes with a mod loader as a separate download.

# Credits

Credits to the UE4SS team for their incredible tool.
