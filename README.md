# Installing-shaders-to-mc-bedrock

To use the shaders you need to check your directx version, if you don't have directx here is the link: https://www.microsoft.com/en-us/download/details.aspx?id=35

once you got directx installed make sure it's directx12 by pressing on the search button next to the windows button and typing "dxdiag" this should run the DirectX Diagnostic Tool
![Screenshot (19)](https://user-images.githubusercontent.com/77900806/218931231-e778a5d8-9a22-403f-9b9a-6c4d47f7d183.png)

To check the shadermodel you need the directx caps viewer which can be get here:https://bit.ly/40ik8AN

Open caps viewer, click on your gpu, expanding it by clicking the plus icon and click on Direct3D 12, if your shader model is above 6.3 you are good to go!

![Screenshot (20)](https://user-images.githubusercontent.com/77900806/218932350-18bbdcfb-b52c-4a85-9199-1f10780c3268.png)

Now you will need the mc version launcher from McMrArm also just a warning it does not pirate minecraft! you'll need a account that owns minecraft!
Link:https://github.com/MCMrARM/mc-w10-version-launcher

Once you extract and open the launcher go ahead and download minecraft greater than version 1.19.40, any lower will not work 

Once it's downloaded go to the download directory in the launcher on where minecraft was downloaded, before you do that you will need the custom materials that you can download from here https://cdn.discordapp.com/attachments/1066623642194153582/1071805388065882172/YSS_Special_Edition_beta6.zip this will download the materials for the shaders

You will also need RTX2Deffered https://github.com/ddf8196/RTX2Deferred

Once you got all of those go back to the mc 10 launcher from McMrArm and navigate to the minecraft material directory in \Downloads\MCLauncher\Minecraft-1.19.xx.x\data\renderer\materials

Drag and drop the materials from YSS Special edition and put it in the materials directory of the minecraft folder

Now extract RTX2Deffered and run LaunchMinecraft.bat, this should inject a dll to where it enables ray tracing in the video settings by default

Once that is done you can download any RTX world or resource pack and import it to minecraft bedrock, i'll be using the realsource pack for this example
https://mcpedl.com/realsource-rtx-texture-pack/

Once you import your pack close minecraft, open RTX2Deffered bat and minecraft should launch, open any world you have and make sure the resource pack is enabled

Here is the final result!

![Screenshot (21)](https://user-images.githubusercontent.com/77900806/218938067-9d21f2cc-fb08-4e86-ae29-60fe87aae50f.png)
![Screenshot (23)](https://user-images.githubusercontent.com/77900806/218938624-809dbbce-6733-4abf-973a-8d2255664ac6.png)


