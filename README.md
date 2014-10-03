StackWalker
===========

The Stack Walker, walks a callstack for any thread (own, other and remote). It has an abstraction layer, so the calling app does not need to know the internals.

	- This is a Visual Studio project

To compile it with biicode execute this command:

    bii cpp:configure -G "Visual Studio 10"
    
The command documentation can be found here: [Biicode Docs](http://docs.biicode.com/c++/cpp-commands.html#bii-cpp-configure-configure-your-project)

To include it with biicode write:

    #include "mariadeanton/stackwalker/StackWalker.h"
    
For more information check:

[StackWalker Original Library](http://stackwalker.codeplex.com/)

[An explanation article @ codeproject](http://www.codeproject.com/Articles/11132/Walking-the-callstack)
