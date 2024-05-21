# This was a MESS
No preamble. The file you wanna change is in Actions\LaunchExecutionAction.cs
Sorry for the GPT Comments I was having a ROUGH time. Can't be bothered to clean up.

## AdditionalExecutablePath
Change the path in quotes to whatever path your game exe is located.

## Usage
Try to launch the game with the Custom Path turned OFF **BEFORE** you run it with Custom Path turned ON. This is especially important when you change your mods because the mod *apply* stage doesn't work with the Custom Path. Just the Launch part.

## Build
Worst part. If you don't develop on C# or C++ you'll need to grab .NET Desktop Dev & Desktop Dev with C++ from the Visual Studio Installer. You'll also need a Windows SDK, I think it's 10.0.22621.0. If you're missing anything, trust me, the build log will tell you. If the build log at any point says "Missing FrostySDK.DLL from bin/debug/whatever" just grab the fully compiled release, and click and drag those dlls where the builder is complaining. 

## Build Pt. 2
Just download the WHOLE Frosty [Toolsuite](https://github.com/CadeEvs/FrostyToolsuite/tree/1.0.6.3) ZIP. Open it's sln file in VS Community. Add my plugin as an Existing Project. File > Add > Add Existing
When building, do so by right-clicking my plugin and clicking build. Do not build the whole project. Do not RE-BUILD. Both options have done horrible, terrible things to me.

## Don't @ Me
Don't Pull Request Me. Found a way to make it better? Good for you. Found a way to path it without the exact path? Good for you. Found a way to remove these dependancies? Good for you. I'm not gonna troubleshoot or teach you how to build. I'm sorry bro I just wanna play the game with mods this was absurd and took way too long I'm sticking with React never doing anything having to do with Visual Studio again in my life idc how much you pay me.
