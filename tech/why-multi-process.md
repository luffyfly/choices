## Why use the multi-process architecture?

World Engine can seen as a 3d content browser, so we can learn from web browsers like Chrome.

### The philosophy of Chrome
It's nearly impossible to build a rendering engine that never crashes or hangs.
It's also nearly impossible to build a rendering engine that is perfectly secure.
In some ways, the state of web browsers around 2006 was like that of the single-user, co-operatively multi-tasked operating systems of the past. 
As a misbehaving application in such an operating system could take down the entire system, so could a misbehaving web page in a web browser. 
All it took was one rendering engine or plug-in bug to bring down the entire browser and all of the currently running tabs.
Modern operating systems are more robust because they put applications into separate processes that are walled off from one another.
A crash in one application generally does not impair other applications or the integrity of the operating system, and each user's access to other users' data is restricted. 
Chromium's architecture aims for this more robust design. See [https://www.chromium.org/developers/design-documents/multi-process-architecture/](https://www.chromium.org/developers/design-documents/multi-process-architecture/)

