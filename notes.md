# Win10 build?

I can build autovala projects on msys2, by using:

    $ cmake -G "MSYS Makefiles" ..

 But autovala itself doesn't build.

    removed plugins
    removed man pages

and now I get this, except I even hard code the destination, I still get an error: 

    $ cmake -G "MSYS Makefiles" ..
    -- checking for Vala version of valac-0.30
    -- checking for a minimum Vala version of 0.30
    --   found Vala, version 0.36
    CMake Error at src/autovalaLib/CMakeLists.txt:111 (install):
    install Library TARGETS given no DESTINATION!


    -- checking for Vala version of valac-0.30
    -- checking for a minimum Vala version of 0.30
    --   found Vala, version 0.36
    -- Configuring incomplete, errors occurred!

