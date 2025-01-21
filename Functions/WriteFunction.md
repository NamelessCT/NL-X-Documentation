# Write | Currently allows you to write integers, floats, and booleans to a property of an object

This function is the most **advanced** function to call, and it goes as follows: **Write(TargetObject, PropertyNameString, Value)**

You can currently write to properties with these objects: 
- **Pawn (PlayerPawn)| Write(Pawn, PropertyNameString, Value)**
- **Controller (PlayerController) | Write(Controller, PropertyNameString, Value)**
- **World | Write(World, PropertyNameString, Value)**
- **Weapon | Write(Weapon, PropertyNameString, Value)**
- **Vehicle | Write(Vehicle, PropertyNameString, Value)**

The type of values you can use at the moment are:
- **Booleans (At the moment only true, until you die/respawn/the game resets the value itself) | Write(TargetObject, PropertyNameString, true)**
- **Integers (Numeric value) | Write(TargetObject, PropertyNameString, 1)** <- **Example**
- **Float (Numeric value with decimal points) | Write(TargetObject, PropertyNameString, 1.0f)** <- **Example**

# Property Names

You can find property names on Dumpspace: https://dumpspace.spuckwaffel.com/Games/?hash=6b77eceb

If you look around somewhere, you are told if the thing you are looking at is an integer, float, or boolean.

Here is an example (The object is Pawn): https://dumpspace.spuckwaffel.com/Games/?hash=6b77eceb&type=classes&idx=AFortPlayerPawn&member=bHasStartedFloating

If I wanted to set this to true, it would be called like: Write(Pawn, "bHasStartedFloating", true)

                                                               (Object, PropertyNameString, Value)
#
**The logic provided allows you to replicate this function with any property that is a integer, boolean, or float value**
