# ediabas-sgbd

*Warning: These files are strictly a reference, and are not intended, nor suitable, for creating ECU description files (SGBDs). Any reference, be it explicit, or implied, to BMW is solely a result of the disassembly process.*

SGBD source files derived from BEST object files.

The source files are near equivalent to those used to compile the BEST object files. However, while the instructions should match, the original object files include meta data including compilation date/time, and passwords which will differ.

The source has been sufficiently padded as to match the existing debugging meta data included in the original object files. This allows the source files to be used for debugging in BestView.

![BestView Debugger](debug.png)


File|BEST Object File|BIP Ver.|Rev. Number|Last Mod.
:-----|:-----|:-----|:-----|:-----
`D_0000.B2G`|`D_0000.GRP`|`05.05.00`|`1.25`|`Thu Jun 05 16:48:08 2003`
`D_003B.B2G`|`D_003B.GRP`|`05.05.00`|`1.7`|`Thu Apr 08 09:58:08 2004`
`D_00D0.B2G`|`D_00D0.GRP`|`05.05.00`|`1.51`|`Thu Feb 12 16:47:56 2004`
