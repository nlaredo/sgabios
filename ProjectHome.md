The Google Serial Graphics Adapter BIOS or SGABIOS provides a means for legacy [x86](http://en.wikipedia.org/wiki/X86) software to communicate with an attached serial console as if a [video card](http://en.wikipedia.org/wiki/Video_Card) were attached.

SGABIOS is designed to be inserted into a BIOS as an [option rom](http://en.wikipedia.org/wiki/Option_ROM) to provide over a serial port the display and input capabilities normally handled by a [VGA adapter](http://en.wikipedia.org/wiki/VGA) and a keyboard, and additionally provide hooks for logging displayed characters for later collection after an operating system boots.

It is designed to handle all text mode output sent to the legacy [video bios](http://en.wikipedia.org/wiki/Video_BIOS) int 10h service routine.  Int 10h is the most common method for displaying characters in 16-bit legacy x86 code.

Detailed design information can be found in the source file [design.txt](http://code.google.com/p/sgabios/source/browse/trunk/design.txt).