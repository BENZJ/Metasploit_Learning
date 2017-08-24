# Wedit Makefile for project bofserver
SRCDIR="c:\documents and settings\benz\×ÀÃæ"
CFLAGS=-I"C:\lcc\include"  -g2 
CC=$(LCCROOT)\bin\lcc.exe
LINKER=$(LCCROOT)\bin\lcclnk.exe
OBJS=\
	bofserver.obj

LIBS=
EXE="bofserver.exe"

$(EXE):	$(OBJS) Makefile
	$(LINKER)  -subsystem console -o $(SRCDIR)\"lcc\bofserver.exe" $(OBJS) $(LIBS)

# Build bofserver.c
BOFSERVER_C=\
	c:\lcc\include\_syslist.h\
	c:\lcc\include\_syslist.h\
	c:\lcc\include\safelib.h\
	c:\lcc\include\safelib.h\
	c:\lcc\include\stdarg.h\
	c:\lcc\include\ctype.h\
	c:\lcc\include\basetsd.h\

bofserver.obj: $(BOFSERVER_C) $(SRCDIR)\"bofserver.c"
	$(CC) -c $(CFLAGS) $(SRCDIR)\"bofserver.c"

link:
	$(LINKER)  -subsystem console -o $(SRCDIR)\"lcc\bofserver.exe" $(OBJS) $(LIBS)

clean:
	del $(OBJS) bofserver.exe
