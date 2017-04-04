## An option type in C#

If you’ve been programming C# you’ve probably shouted at your screen because of a NullReferenceException at some point in the past. This usually happens because some method returned null when you weren’t expecting it and thus did not handle that possibility in your code. Null is often (ab)used to represent absent or optional values, which makes unexpected exceptions even more likely. But there’s a better way: an option type!

It’s a strongly typed alternative to null values that not only lets you avoid NullReferenceExceptions but also declare your intent and write more focused code.

I’ll give you an overview of this awesome concept and how to use it even though C# does not have a built-in option type.