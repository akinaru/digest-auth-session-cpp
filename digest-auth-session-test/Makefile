#############################################################################
# Makefile for building: release/digest-auth-session-test
# Generated by qmake (2.01a) (Qt 4.8.4) on: Fri Sep 4 01:16:45 2015
# Project:  digest-auth-session-test.pro
# Template: app
# Command: /usr/lib/i386-linux-gnu/qt4/bin/qmake -spec /usr/share/qt4/mkspecs/linux-g++ CONFIG+=debug CONFIG+=declarative_debug -o Makefile digest-auth-session-test.pro
#############################################################################

####### Compiler, tools and options

CC            = gcc
CXX           = g++
DEFINES       = -DQT_NETWORK_LIB -DQT_CORE_LIB -DQT_SHARED
CFLAGS        = -pipe -g -Wall -W -D_REENTRANT $(DEFINES)
CXXFLAGS      = -pipe -g -Wall -W -D_REENTRANT $(DEFINES)
INCPATH       = -I/usr/share/qt4/mkspecs/linux-g++ -I. -I/usr/include/qt4/QtCore -I/usr/include/qt4/QtNetwork -I/usr/include/qt4 -I/home/abathur/Bureau/open_source/digest-auth-session-cpp/digest-auth-session-test/libs -I../digest-auth-session-lib/libs -I../digest-auth-session-lib -I.
LINK          = g++
LFLAGS        = 
LIBS          = $(SUBLIBS)  -L/usr/lib/i386-linux-gnu -L/home/abathur/Bureau/open_source/digest-auth-session-cpp/digest-auth-session-test/../digest-auth-session-lib/libs/ -lhttpServer -lhttpdecoder -L/home/abathur/Bureau/open_source/digest-auth-session-cpp/digest-auth-session-test/../digest-auth-session-lib/release/ -ldigestauthsession -lQtNetwork -lQtCore -lpthread 
AR            = ar cqs
RANLIB        = 
QMAKE         = /usr/lib/i386-linux-gnu/qt4/bin/qmake
TAR           = tar -cf
COMPRESS      = gzip -9f
COPY          = cp -f
SED           = sed
COPY_FILE     = $(COPY)
COPY_DIR      = $(COPY) -r
STRIP         = strip
INSTALL_FILE  = install -m 644 -p
INSTALL_DIR   = $(COPY_DIR)
INSTALL_PROGRAM = install -m 755 -p
DEL_FILE      = rm -f
SYMLINK       = ln -f -s
DEL_DIR       = rmdir
MOVE          = mv -f
CHK_DIR_EXISTS= test -d
MKDIR         = mkdir -p

####### Output directory

OBJECTS_DIR   = bin/

####### Files

SOURCES       = main.cpp \
		ClientSocketHandler.cpp \
		SslHandler.cpp \
		utils/fileutils.cpp \
		utils/stringutil.cpp \
		HashDigestListener.cpp 
OBJECTS       = bin/main.o \
		bin/ClientSocketHandler.o \
		bin/SslHandler.o \
		bin/fileutils.o \
		bin/stringutil.o \
		bin/HashDigestListener.o
DIST          = /usr/share/qt4/mkspecs/common/unix.conf \
		/usr/share/qt4/mkspecs/common/linux.conf \
		/usr/share/qt4/mkspecs/common/gcc-base.conf \
		/usr/share/qt4/mkspecs/common/gcc-base-unix.conf \
		/usr/share/qt4/mkspecs/common/g++-base.conf \
		/usr/share/qt4/mkspecs/common/g++-unix.conf \
		/usr/share/qt4/mkspecs/qconfig.pri \
		/usr/share/qt4/mkspecs/modules/qt_phonon.pri \
		/usr/share/qt4/mkspecs/features/qt_functions.prf \
		/usr/share/qt4/mkspecs/features/qt_config.prf \
		/usr/share/qt4/mkspecs/features/exclusive_builds.prf \
		/usr/share/qt4/mkspecs/features/default_pre.prf \
		/usr/share/qt4/mkspecs/features/debug.prf \
		/usr/share/qt4/mkspecs/features/default_post.prf \
		/usr/share/qt4/mkspecs/features/declarative_debug.prf \
		/usr/share/qt4/mkspecs/features/unix/gdb_dwarf_index.prf \
		/usr/share/qt4/mkspecs/features/warn_on.prf \
		/usr/share/qt4/mkspecs/features/qt.prf \
		/usr/share/qt4/mkspecs/features/unix/thread.prf \
		/usr/share/qt4/mkspecs/features/moc.prf \
		/usr/share/qt4/mkspecs/features/resources.prf \
		/usr/share/qt4/mkspecs/features/uic.prf \
		/usr/share/qt4/mkspecs/features/yacc.prf \
		/usr/share/qt4/mkspecs/features/lex.prf \
		/usr/share/qt4/mkspecs/features/include_source_dir.prf \
		digest-auth-session-test.pro
QMAKE_TARGET  = digest-auth-session-test
DESTDIR       = release/
TARGET        = release/digest-auth-session-test

first: all
####### Implicit rules

.SUFFIXES: .o .c .cpp .cc .cxx .C

.cpp.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cc.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cxx.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.C.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.c.o:
	$(CC) -c $(CFLAGS) $(INCPATH) -o "$@" "$<"

####### Build rules

all: Makefile $(TARGET)

$(TARGET):  $(OBJECTS)  
	@$(CHK_DIR_EXISTS) release/ || $(MKDIR) release/ 
	$(LINK) $(LFLAGS) -o $(TARGET) $(OBJECTS) $(OBJCOMP) $(LIBS)
	{ test -n "$(DESTDIR)" && DESTDIR="$(DESTDIR)" || DESTDIR=.; } && test $$(gdb --version | sed -e 's,[^0-9]\+\([0-9]\)\.\([0-9]\).*,\1\2,;q') -gt 72 && gdb --nx --batch --quiet -ex 'set confirm off' -ex "save gdb-index $$DESTDIR" -ex quit '$(TARGET)' && test -f $(TARGET).gdb-index && objcopy --add-section '.gdb_index=$(TARGET).gdb-index' --set-section-flags '.gdb_index=readonly' '$(TARGET)' '$(TARGET)' && rm -f $(TARGET).gdb-index || true 
	rsync -avm --include=*/ --include=*.h --exclude=* /home/abathur/Bureau/open_source/digest-auth-session-cpp/digest-auth-session-test// /home/abathur/Bureau/open_source/digest-auth-session-cpp/digest-auth-session-test/release

Makefile: digest-auth-session-test.pro  /usr/share/qt4/mkspecs/linux-g++/qmake.conf /usr/share/qt4/mkspecs/common/unix.conf \
		/usr/share/qt4/mkspecs/common/linux.conf \
		/usr/share/qt4/mkspecs/common/gcc-base.conf \
		/usr/share/qt4/mkspecs/common/gcc-base-unix.conf \
		/usr/share/qt4/mkspecs/common/g++-base.conf \
		/usr/share/qt4/mkspecs/common/g++-unix.conf \
		/usr/share/qt4/mkspecs/qconfig.pri \
		/usr/share/qt4/mkspecs/modules/qt_phonon.pri \
		/usr/share/qt4/mkspecs/features/qt_functions.prf \
		/usr/share/qt4/mkspecs/features/qt_config.prf \
		/usr/share/qt4/mkspecs/features/exclusive_builds.prf \
		/usr/share/qt4/mkspecs/features/default_pre.prf \
		/usr/share/qt4/mkspecs/features/debug.prf \
		/usr/share/qt4/mkspecs/features/default_post.prf \
		/usr/share/qt4/mkspecs/features/declarative_debug.prf \
		/usr/share/qt4/mkspecs/features/unix/gdb_dwarf_index.prf \
		/usr/share/qt4/mkspecs/features/warn_on.prf \
		/usr/share/qt4/mkspecs/features/qt.prf \
		/usr/share/qt4/mkspecs/features/unix/thread.prf \
		/usr/share/qt4/mkspecs/features/moc.prf \
		/usr/share/qt4/mkspecs/features/resources.prf \
		/usr/share/qt4/mkspecs/features/uic.prf \
		/usr/share/qt4/mkspecs/features/yacc.prf \
		/usr/share/qt4/mkspecs/features/lex.prf \
		/usr/share/qt4/mkspecs/features/include_source_dir.prf \
		/usr/lib/i386-linux-gnu/libQtNetwork.prl \
		/usr/lib/i386-linux-gnu/libQtCore.prl
	$(QMAKE) -spec /usr/share/qt4/mkspecs/linux-g++ CONFIG+=debug CONFIG+=declarative_debug -o Makefile digest-auth-session-test.pro
/usr/share/qt4/mkspecs/common/unix.conf:
/usr/share/qt4/mkspecs/common/linux.conf:
/usr/share/qt4/mkspecs/common/gcc-base.conf:
/usr/share/qt4/mkspecs/common/gcc-base-unix.conf:
/usr/share/qt4/mkspecs/common/g++-base.conf:
/usr/share/qt4/mkspecs/common/g++-unix.conf:
/usr/share/qt4/mkspecs/qconfig.pri:
/usr/share/qt4/mkspecs/modules/qt_phonon.pri:
/usr/share/qt4/mkspecs/features/qt_functions.prf:
/usr/share/qt4/mkspecs/features/qt_config.prf:
/usr/share/qt4/mkspecs/features/exclusive_builds.prf:
/usr/share/qt4/mkspecs/features/default_pre.prf:
/usr/share/qt4/mkspecs/features/debug.prf:
/usr/share/qt4/mkspecs/features/default_post.prf:
/usr/share/qt4/mkspecs/features/declarative_debug.prf:
/usr/share/qt4/mkspecs/features/unix/gdb_dwarf_index.prf:
/usr/share/qt4/mkspecs/features/warn_on.prf:
/usr/share/qt4/mkspecs/features/qt.prf:
/usr/share/qt4/mkspecs/features/unix/thread.prf:
/usr/share/qt4/mkspecs/features/moc.prf:
/usr/share/qt4/mkspecs/features/resources.prf:
/usr/share/qt4/mkspecs/features/uic.prf:
/usr/share/qt4/mkspecs/features/yacc.prf:
/usr/share/qt4/mkspecs/features/lex.prf:
/usr/share/qt4/mkspecs/features/include_source_dir.prf:
/usr/lib/i386-linux-gnu/libQtNetwork.prl:
/usr/lib/i386-linux-gnu/libQtCore.prl:
qmake:  FORCE
	@$(QMAKE) -spec /usr/share/qt4/mkspecs/linux-g++ CONFIG+=debug CONFIG+=declarative_debug -o Makefile digest-auth-session-test.pro

dist: 
	@$(CHK_DIR_EXISTS) bin/digest-auth-session-test1.0.0 || $(MKDIR) bin/digest-auth-session-test1.0.0 
	$(COPY_FILE) --parents $(SOURCES) $(DIST) bin/digest-auth-session-test1.0.0/ && $(COPY_FILE) --parents SslHandler.h ClientSocketHandler.h utils/fileutils.h utils/stringutil.h HashDigestListener.h bin/digest-auth-session-test1.0.0/ && $(COPY_FILE) --parents main.cpp ClientSocketHandler.cpp SslHandler.cpp utils/fileutils.cpp utils/stringutil.cpp HashDigestListener.cpp bin/digest-auth-session-test1.0.0/ && (cd `dirname bin/digest-auth-session-test1.0.0` && $(TAR) digest-auth-session-test1.0.0.tar digest-auth-session-test1.0.0 && $(COMPRESS) digest-auth-session-test1.0.0.tar) && $(MOVE) `dirname bin/digest-auth-session-test1.0.0`/digest-auth-session-test1.0.0.tar.gz . && $(DEL_FILE) -r bin/digest-auth-session-test1.0.0


clean:compiler_clean 
	-$(DEL_FILE) $(OBJECTS)
	-$(DEL_FILE) -r /home/abathur/Bureau/open_source/digest-auth-session-cpp/digest-auth-session-test/release
	-$(DEL_FILE) *~ core *.core


####### Sub-libraries

distclean: clean
	-$(DEL_FILE) $(TARGET) 
	-$(DEL_FILE) Makefile


check: first

mocclean: compiler_moc_header_clean compiler_moc_source_clean

mocables: compiler_moc_header_make_all compiler_moc_source_make_all

compiler_moc_header_make_all:
compiler_moc_header_clean:
compiler_rcc_make_all:
compiler_rcc_clean:
compiler_image_collection_make_all: qmake_image_collection.cpp
compiler_image_collection_clean:
	-$(DEL_FILE) qmake_image_collection.cpp
compiler_moc_source_make_all:
compiler_moc_source_clean:
compiler_uic_make_all:
compiler_uic_clean:
compiler_yacc_decl_make_all:
compiler_yacc_decl_clean:
compiler_yacc_impl_make_all:
compiler_yacc_impl_clean:
compiler_lex_make_all:
compiler_lex_clean:
compiler_clean: 

####### Compile

bin/main.o: main.cpp SslHandler.h \
		ClientSocketHandler.h \
		HashDigestListener.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o bin/main.o main.cpp

bin/ClientSocketHandler.o: ClientSocketHandler.cpp ClientSocketHandler.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o bin/ClientSocketHandler.o ClientSocketHandler.cpp

bin/SslHandler.o: SslHandler.cpp SslHandler.h \
		utils/fileutils.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o bin/SslHandler.o SslHandler.cpp

bin/fileutils.o: utils/fileutils.cpp utils/fileutils.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o bin/fileutils.o utils/fileutils.cpp

bin/stringutil.o: utils/stringutil.cpp utils/stringutil.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o bin/stringutil.o utils/stringutil.cpp

bin/HashDigestListener.o: HashDigestListener.cpp HashDigestListener.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o bin/HashDigestListener.o HashDigestListener.cpp

####### Install

install:   FORCE

uninstall:   FORCE

FORCE:

