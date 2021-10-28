# java-tips

```
String str1 = "I am a string";
String str2 = new String("I am a string via a constructor");
```
The first method is a better way to create Strings. Creating Strings using constructors wastes memory space a lot as objects do not share storage even for the same content while the first method does share storage for the same content.
