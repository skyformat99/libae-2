# Is there a way that I don't have to repeat libae0 a million times?
lib_LTLIBRARIES = libae0.la

libae0_la_LDFLAGS = \
	-no-undefined \
	-version $(LIBAE_MAJOR):$(LIBAE_MINOR):$(LIBAE_AGE) 

libae0_la_CPPFLAGS = \
	-I ../include/

libae0_la_SOURCES = \
	ae.c \
	event.c \
	io.c \
	log.c \
	misc.c \
	mux.c \
	opt.c \
	pool.c \
	ptrarray.c \
	res.c \
	server.c \
	str.c \
	threadpool.c \
	time.c \
	timer.c 


headerdir = $(prefix)/include/ae
header_DATA = \
	../include/ae/ae.h \
	../include/ae/event.h \
	../include/ae/io.h \
	../include/ae/log.h \
	../include/ae/misc.h \
	../include/ae/mux.h \
	../include/ae/opt.h \
	../include/ae/pool.h \
	../include/ae/ptrarray.h \
	../include/ae/res.h \
	../include/ae/server.h \
	../include/ae/str.h \
	../include/ae/time.h \
	../include/ae/timer.h \
	../include/ae/try.h \
	../include/ae/types.h 
