ProGuard clone with support for exceptions to SourceFile renaming
=================================================================

This is a fork of johnjohndoe/ProGuard with support for adding exceptions
to the renamesourcefileattribute directive to keep the original source
file names.

For example:

-keeporiginalsourcefileattribute com.example.SomeClass