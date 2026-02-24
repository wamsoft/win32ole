include(../tp_stub/krkrz.cmake)

krkrz_plugin(win32ole
    NCBIND
    SOURCES
        CArchive.cpp
        IDispatchWrapper.cpp
        main.cpp
)
