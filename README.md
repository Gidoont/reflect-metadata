
Fork of https://rbuckton.github.io/reflect-metadata which 
works in Firefox. Using reflect-metadata package in 
a Firefox webextension content script will 
cause an error on the 4th line of makeExporter 
"Not allowed to define cross-origin object as property 
on [Object] or [Array] XrayWrapper". The exception is not displayed
by default. You can only see it if you "pause on exceptions" 
in the debugger.

May not work in node environment.
