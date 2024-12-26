# There is a line limit on scripts at the moment to prevent scripts that are unstable from being made

Although NL-X uses an interpreter close to C++, it still is a custom interpreter so things aren't as accurate to the base C++ language. 

For example, a custom function in NL-X is "CallBIC" which can be used to call built in functions (what level 1 will be). 

Here is an example:

```
CallBIC(builtinfunction());
```
As you know, all code needs an entry point, in NL-X it will be a void, specifically Main for level 1.

```
void Main()
{

}
```
An example of a complete script would be:
```
void Main()
{
  CallBIC(fov 120());
}
```
