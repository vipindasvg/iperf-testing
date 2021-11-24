noinst_PROGRAMS		= client server		# Build, but don't install

AM_CPPFLAGS		= ../iperf/src

client_SOURCES		= client.c
client_CFLAGS		= -g
client_LDADD		= ../iperf/src/libiperf.la
client_LDFLAGS		= -g

server_SOURCES		= server.c
server_CFLAGS		= -g
server_LDADD		= ../iperf/src/libiperf.la
server_LDFLAGS		= -g