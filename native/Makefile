JDK_HOME = /etc/java-config-2/current-system-vm
CFLAGS   = -I $(JDK_HOME)/include -I $(JDK_HOME)/include/linux
JNI_NAME = pty
PROGNAME=libpty.so

SRCS = pty.c


CFLAGS= -Wall

all:
	gcc $(CFLAGS) -o $(PROGNAME) -fPIC -shared $(SRCS) -lc
#	gcc $(CFLAGS) -o $(PROGNAME) -fPIC -shared $(SRCS) -Wl,soname,lib$(JNI_NAME) -lc

clean:
	rm -f lib$(JNI_NAME).so
