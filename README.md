# TeleprompterApp
__Description__: Recieves files and reverses them for teleprompter use. 

## Considerations: 
* Need to be able to receive different kinds of files(.pdf, .txt)
* Need to be able to auto scroll and control pace
* Cross-platform? Or just Ipad? 
* Flutter or Swift
* Needs to work for different languages(not limited to English)

## Current Methods: 
* Take snapshots line by line, then load images reversed. 
    * Possibly slow loading times.
* Utilize a dictionary: each 'character' maps to its reverse.
    * Might not work as well for other languages(Chinese)