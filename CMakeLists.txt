cmake_minimum_required(VERSION 3.4)
project(drs_5_0_6)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        firmware/CY7C68013A/drs_eval.c
        firmware/CY7C68013A/drs_eval.hex
        firmware/CY7C68013A/drs_eval.iic
        firmware/CY7C68013A/drs_eval.Uv2
        firmware/CY7C68013A/dscr.a51
        firmware/CY7C68013A/EZUSB.LIB
        firmware/CY7C68013A/fw.c
        firmware/CY7C68013A/Fx2.h
        firmware/CY7C68013A/fx2regs.h
        firmware/CY7C68013A/fx2sdly.h
        firmware/CY7C68013A/USBJmpTb.a51
        include/AboutDialog.h
        include/averager.h
        include/ConfigDialog.h
        include/DisplayDialog.h
        include/DOFrame.h
        include/DOScreen.h
        include/DRS.h
        include/DRSOsc.h
        include/DRSOscInc.h
        include/EPThread.h
        include/InfoDialog.h
        include/MeasureDialog.h
        include/Measurement.h
        include/musbstd.h
        include/mxml.h
        include/Osci.h
        include/rb.h
        include/strlcpy.h
        include/TriggerDialog.h
        src/AboutDialog.cpp
        src/averager.cpp
        src/ConfigDialog.cpp
        src/DisplayDialog.cpp
        src/DOFrame.cpp
        src/DOScreen.cpp
        src/DRS.cpp
        src/drs_exam.cpp
        src/drs_exam_multi.cpp
        src/drscl.cpp
        src/DRSOsc.cpp
        src/EPThread.cpp
        src/InfoDialog.cpp
        src/main.cpp
        src/MeasureDialog.cpp
        src/Measurement.cpp
        src/musbstd.c
        src/mxml.c
        src/Osci.cpp
        src/rb.cpp
        src/read_binary.cpp
        src/strlcpy.c
        src/TriggerDialog.cpp
        Makefile)

add_executable(drs_5_0_6 ${SOURCE_FILES})