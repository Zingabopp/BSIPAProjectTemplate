# BSIPAProjectTemplate
A Visual Studio template to easily create a new Beat Saber plugin.

This template creates a sample Beat Saber plugin that demonstrates how to use BSIPA's logger and ConfigProvider. It also shows how to use most of Custom UI's functionality.

# How to Use
<u1>
<li>Create a new project in Visual Studio using this template (Use at least .NET Framework 4.6.1)</li>
<li>Navigate to the project folder, inside you should see CreateJunctions.bat</li>
<li>In another explorer window: find your Beat Saber game folder and drag it on top of CreateJunctions.bat (or run CreateJunctions.bat and type in the path to your Beat Saber folder). This will create a References folder inside your project folder that has directory junctions to your "Beat Saber_data\Managed" and "Plugins" folder.</li>
<li>Your project should now be able to build. When you build, a post-build event will automatically copy your plugin's DLL file to Beat Saber's "Plugins" folder.</li>
</u1>

# Credits
<u1>
<li>This template is based on nike4613's you can find here: https://github.com/nike4613/BeatSaberIPAProjectTemplate</li>
<li>The repository for BSIPA can be found here: https://github.com/beat-saber-modding-group/BeatSaber-IPA-Reloaded</li>
<li>BeatSaber-CustomUI by brian91292 can be found here: https://github.com/brian91292/BeatSaber-CustomUI</li>
</u1>
