# ScreenShare
Screen sharing project!!

----

# Modules
## Screen Capture (Host)
Captures an image (of the screen) on the host.

## Image Streaming Protocol (Host-Client)
Sends the image from the *Screen Capture* to the client.

Decide here whether to compress the image or use IFrames and deltas.

Here we can support both peer-to-peer and server-based configuration by implementing
the protocol in a way that allows us to us to add the server as a "man-in-the-middle".

We can also implement either side in any laguage and try out different methods.
This will also allow us to support cross-platform if we ever choose to do so.
Code is like *LEGO*!

## Viewer (Client)
Displays the image.

# Possible Technologies
## C#
1. OpenGL
2. .NET

TBD...

# POC
> ```C#
> using System;
>
> class Program
> {
>    static void main(string[] args)
>    {
>        Console.WriteLine("Hello World!");
>    }
> }
> ```
