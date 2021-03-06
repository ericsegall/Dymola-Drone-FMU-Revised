# Dymola-Drone-FMU-Revised
Final Proof of Concept for the Arch ILE Project

This is a showcase of how a Dymola generated FMU can interact with Unity. Simply download these files and open it with the LTS 2020 Unity edition to see how it works. 

If you are interested in learning how to install Unity, please follow this guide:  https://www.notion.so/alsetlab/Unity-3D-Setup-9963c3b10e6e47db938fb8d5d3977958

If you are interested in learning how to integrate an FMI into your project, please follow this guide: https://www.notion.so/alsetlab/CATIA-Systems-Unity-FMI-Addon-Integration-Procedure-19a2113876ba417ca9a382a51a2ae445

To see active input work both a gamepad and a keyboard works. The left analog stick of the gamepad controls movement in the XY plane and the right analog stick controls movement in the Z. The keyboard is bound with O/P referring to positive and negative in the Z, and WASD for X/Y. If you want to make adjustments to input processing, please refer to the Input System Package guide by Unity:  https://docs.unity3d.com/Packages/com.unity.inputsystem@1.0/manual/QuickStartGuide.html 

In general, this is a basic proof of concepts, but in the future, we hope to get Dymola’s collision library working with the Drone movement script. There are a lot of improvements to be made, but this is a good example of how to develop basic consistent time synchronization of an FMI with a game engine. Also, there is currently an error with Unity 2020 where sometimes the project will not “play” due to a String conversion error hopefully this will be fixed in the future on Unity’s end but for the meantime just clear the error in the console, attempt to launch the project again and it should go through. 
