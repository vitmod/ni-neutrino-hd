AM_CPPFLAGS = \
	-I$(top_builddir) \
	-I$(top_srcdir) \
	-I$(top_srcdir)/src \
	-I$(top_srcdir)/src/zapit/include \
	@AVFORMAT_CFLAGS@ \
	@SIGC_CFLAGS@ \
	@HWLIB_CFLAGS@

AM_CPPFLAGS += -fno-rtti -fno-exceptions

noinst_LIBRARIES = libdvbsub.a

libdvbsub_a_SOURCES = dvbsub.cpp dvbsubtitle.cpp \
	tools.cpp PacketQueue.cpp helpers.cpp Debug.cpp
