This application test Java's "Double Brace Initialization" with gson's json serialization.

The "Double Brace Initialization" map will return null during serialization because,
> The 2nd expression will create an instance of an anonymous class which extends SomeClass. It is still anonymous, due to the {...}

https://stackoverflow.com/questions/5848510/how-can-an-anonymous-class-use-extends-or-implements
