## This is an add-in for [Fody](https://github.com/Fody/Fody/) 

![Icon](https://raw.github.com/ndamjan/Mutable.Fody/master/Icons/package_icon.png)

An addin for Fody for use with F# - it removes the need for CliMutableAttribute for record types and adds the "equivalent" functionality to union types (adds property setters where necessary). This is useful for deserialization of these types (e.g. when using ServiceStack.Text) and XAML binding.


