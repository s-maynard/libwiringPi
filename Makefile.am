lib_LTLIBRARIES=libwiringPi.la
libwiringPi_la_CPPFLAGS= -DCLIENT_LIB_VERSION=0x$(shell cd ~/libwiringPi;git log -1 --pretty=format:%h)
libwiringPi_la_LDFLAGS=-lpthread
libwiringPi_la_SOURCES= \
    drcSerial.c \
    max31855.c \
    max5322.c \
    mcp23008.c \
    mcp23016.c \
    mcp23017.c \
    mcp23s08.c \
    mcp23s17.c \
    mcp3002.c \
    mcp3004.c \
    mcp3422.c \
    mcp4802.c \
    pcf8574.c \
    pcf8591.c \
    piHiPri.c \
    piThread.c \
    sn3218.c \
    softPwm.c \
    softTone.c \
    sr595.c \
    wiringPi.c \
    wiringPiI2C.c \
    wiringPiSPI.c \
    wiringSerial.c \
    wiringShift.c \
    wpiExtensions.c
libwiringPi_la_DEPENDENCIES=

libwiringPi_la_includedir= \
	$(includedir)
libwiringPi_la_include_HEADERS= \
    wiringPi.h \
    wiringPiI2C.h \
    wiringPiSPI.h \
    wiringSerial.h

libwiringPi_la_LIBADD=
