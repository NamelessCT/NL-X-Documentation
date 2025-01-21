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
- You can find your NLX script folder in C:\NLHybrid\NLX (Place any scripts created/downloaded in that folder).

# NL-X uses an interpreter close to C++ 

NL-X offers a variety of pre-defined functions. This at the moment, includes:

**Spawn(String) 
**ClientSpeed(FloatValue)**
**FOV(FloatValue)**
**Write(TargetObject, PropertyNameString, BooleanValue)**

Float Documentation: https://github.com/NamelessCT/NL-X-Documentation/blob/main/FloatValues.md

**MessageBoxA(0, LPCSTR  lpText, LPCSTR  lpCaption, uType);** (hWnd unsupported, so it needs to be nullptr or 0)

MessageBoxA Documentation: https://github.com/NamelessCT/NL-X-Documentation/blob/main/MesssageBoxA.md
