# anilewie-scriptlet
An old scriptlet from the 90's converted to modern day JavaScript

It plays with layering to animage a picture of me with eyes moving around, and the mouth opening and closing using the z-index and picking a random coordinate from a pre-defined list to move the eyes.

| Eyes | Face | Mouth | Demo |
| --- | --- | --- | --- |
| ![Eyes](E.GIF) | ![Face](F.GIF) | ![Mouth](T.GIF) | ![Demo](demo.gif) |

Originally I wrote this little experiment on February 1, 1999 when I was getting comfortable with Scriptlets. The scriptlet is [ANILEWIE.SCT](ANILEWIE.SCT) and is just an HTML file with vbScript. Scriptlets were powerful in that although they were in an isolated sandbox that prevented communication with the parent container, you could expose properties and events so that there were ways to communicate safely, similar to how embedded Active X controls behaved.

In the late 90's, vbScript was popular with Government contracts since it was guarenteed that everyone was using Microsoft Internet Explorer, and many programmers were comming from a Visual Basic or BASIC background. Even the default scripting language for Classic ASP was vbScript, and Visual Basic for Applications (VBA) was prevelant for automating complex office tasks with Microsoft Outlook, Excel, and Access.

Jump ahead 26 years and I'm browsing a few of the old files I still have in my archives. I had fond memeries of my experiments, and decided to bring this little script back to life. This did not make use of any communications such as events and properties talking between the container and the scriptlet iself, so it can run within an IFrame or Frame as a simple HTML file. VBScript may be gone, but oddly enough, Microsoft now rules over TypeScript, which is a layer above JavaScript.

Now you too can enjoy the awesomenes of stairing into my eyes from decades past!
