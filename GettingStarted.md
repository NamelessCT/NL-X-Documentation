# NL-X-Documentation
**Official documentation for NL-X by NamelessCT and Xivy**
This is the documentation on how to use NL-X, the first ever Fortnite executor! Join **(discord.gg/namelessct)** for updates!

You first need NL Hybrid Premium to get access to NL-X. In the future, for higher levels, you will be required to purchase an addon for NL-X. It will most likely cost $5 extra.

The NL-X executor utilizes our custom C++ interpreter so it isn't 100% accurate to the base C++ language, especailly just at level 1.

Head over to the "ScriptCreationAndInterpretation" document to understand how to create scripts with NL-X.

Since this is starting at level 1, it won't be **perfect**, but just know we are trying our best.

For proper C++ syntax, I recommend you use an IDE such as Visual Studio/Visual Studio Code

# How To Set Up
- Download the NL Hybrid launcher from **discord.gg/namelessct**
- Purchase premium (NL-X is currently included with NL Hybrid Premium)
- Read and accept the EULA for NL Hybrid Premium, and NL-X
- You can find your NLX script folder in C:\NLHybrid\NLX (Place any scripts created/downloaded in that folder), I have provided example scripts here **FOR EDUCATIONAL PURPOSES ONLY**: [https://github.com/NamelessCT/NL-X-Documentation/tree/main/ExampleScripts](https://github.com/NamelessCT/NL-X-Documentation/tree/main/ExampleScripts)
- Go to the NL-X tab in the NL Hybrid launcher
- Start Fortnite and attach it when you get to lobby

# NL-X uses an interpreter close to C++ 

NL-X offers a variety of pre-defined functions. This at the moment, includes:

- **Spawn(String)** - [https://github.com/NamelessCT/NL-X-Documentation/blob/main/SpawnFunction.md](https://github.com/NamelessCT/NL-X-Documentation/blob/main/Functions/SpawnFunction.md)
- **ClientSpeed(FloatValue)** - [[https://github.com/NamelessCT/NL-X-Documentation/blob/main/Functions/ClientSpeedFunction](https://github.com/NamelessCT/NL-X-Documentation/blob/main/Functions/ClientSpeedFunction)](https://github.com/NamelessCT/NL-X-Documentation/blob/main/Functions/ClientSpeedFunction.md)
- **FOV(FloatValue)** - [https://github.com/NamelessCT/NL-X-Documentation/blob/main/Functions/FOVFunction.md](https://github.com/NamelessCT/NL-X-Documentation/blob/main/Functions/FOVFunction.md)
- **Write(TargetObject, PropertyNameString, BooleanValue)** - [https://github.com/NamelessCT/NL-X-Documentation/blob/main/Functions/WriteFunction](https://github.com/NamelessCT/NL-X-Documentation/blob/main/Functions/WriteFunction)

Float Documentation: https://github.com/NamelessCT/NL-X-Documentation/blob/main/FloatValues.md

**MessageBoxA(0, LPCSTR  lpText, LPCSTR  lpCaption, uType);** (hWnd unsupported, so it needs to be nullptr or 0)

MessageBoxA Documentation: [https://github.com/NamelessCT/NL-X-Documentation/blob/main/MesssageBoxA.md](https://github.com/NamelessCT/NL-X-Documentation/blob/main/Functions/MessageBoxA.md)

# I plan to add more things in the future, such as: support for multiple voids (including a genuine entry point type rather than "void Main", custom function calling (ability to work with offsets as well), sleep, loops, and more!

# Voiding the TOS, using NL-X for mal-intent (cheating, etc), or creating scripts for mal-intent will result in an immediate termination of your NL-X account.
