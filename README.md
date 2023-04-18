# OGXbox-OperatingSYS
A OG Xbox Reverse Engineering Operating System with a complete set of tools to help with decompilations. 
![Image of the OPSys](https://i.ibb.co/0Jmb7Xm/xbox-Operating-System.png)


# What can you do with this Operating System?
    
    
    You can debug any xbox game remotely from your pc to your xbox via local area network.
    You can edit hex code remotely
    You can see the files the xbox game loads and see what files inside those files that are loaded.
    You can then dump those files from a pause sequence remotely over the local network. 
    The archive plus all the data inside those archive inside other archives.
    You can dump x86 ASM code from the xbe with mroe accurate readable asm.
    You can pause the game state locate a function used and see how it is done. 
    aka decompilation sequence better than ghidra more readable output.
    You can edit Texture data remotely.
    You can edit Model data remotely.
    You can edit Script data if any remotely.
    You can dump sound data remotely.
    You can Patch hole xbe exec code remotely.
    
    Plus more a lot more.
    
    
# Programs that come with this Operating system:

    1. Hex Editor
    2. Remote Xbox Game-Debugger
    3. Xbox Script-Editor
    4. Xbox Model-Editor
    5. Xbox Sound-Editor
    6. Xbox Texture-Editor
    7. Xbox Text-Editor
    8. Xbox ASM-Editor
    9. Xbox Code-Editor
    0. Xbox File Resource-Exploror
    1. Xbox Game Data-Dumper
    2. Xbox Game Remote-Patcher
    3. Xbox Game String-Viewer
    4. Xbox Game Function-Viewer
    5. Much more A lot more.
    
# How to use this:
    
    You need a usb drive connected to your pc with the zip file unzipped from
    the releases section on this repo.
    Then boot from usb create a partition and launch the operating system.
    
# Next you need to have a working og xbox connected to a networking card in your pc.
# Recommend you get a Networking adapter for internal use in pc:

    Once you are connected launch the server software on your pc that came with this repo.
    Then choose to connect your xbox through local area network.
    After this it will show up after you launch your game up and xbox.
    
# Once this is done go back to your pc where you launched your xbox operating system

    Launch the xbox debug tool:
    After game is running on xbox:
    Then use the command -d -xbox -loadgui -default.xbe
    This will bring up a gui interface to show you the xbox game debugged from here you can pause 
    dump memory addresses etc...
    
# This is what I use for reverse engineering xbox games the time 
    is cut in half with good set of tools.

# I was motivated to create this due to no tools good enough to use
    for my decompilations..
