

lib_LTLIBRARIES = libjoy.la
libjoy_la_SOURCES = \
	../src/joy_api.c \
	../src/p2f.c \
	../src/osdetect.c \
	../src/anon.c \
	../src/pkt_proc.c \
	../src/nfv9.c \
	../src/tls.c \
	../src/classify.c \
	../src/radix_trie.c \
	../src/hdr_dsc.c \
	../src/procwatch.c \
	../src/addr_attr.c \
	../src/addr.c \
	../src/wht.c \
	../src/http.c \
	../src/str_match.c \
	../src/acsm.c \
	../src/dns.c \
	../src/example.c \
	../src/ipfix.c \
	../src/ssh.c \
	../src/ike.c \
	../src/salt.c \
	../src/parson.c \
	../src/fingerprint.c \
	../src/ppi.c \
	../src/utils.c \
	../src/dhcp.c \
	../src/payload.c \
	../src/config.c \
	../src/proto_identify.c 


libjoy_la_CFLAGS = -I ../src/include -I $(SSL_CFLAGS) $(AM_CFLAGS) 

libjoy_la_LDFLAGS = -version-info $(JOY_LIBRARY_VERSION) $(SSL_LDFLAGS) -lcrypto

include_HEADERS=../src/include/acsm.h \
		../src/include/addr_attr.h \
		../src/include/addr.h \
		../src/include/anon.h \
		../src/include/classify.h \
		../src/include/config.h \
		../src/include/dhcp.h \
		../src/include/dns.h \
		../src/include/err.h \
		../src/include/example.h \
		../src/include/feature.h \
		../src/include/fingerprint.h \
		../src/include/hdr_dsc.h \
		../src/include/http.h \
		../src/include/ike.h \
		../src/include/ipfix.h \
		../src/include/joy_api.h \
		../src/include/joy_api_private.h \
		../src/include/map.h \
		../src/include/modules.h \
		../src/include/nfv9.h \
		../src/include/osdetect.h \
		../src/include/output.h \
		../src/include/p2f.h \
		../src/include/parson.h \
		../src/include/payload.h \
		../src/include/pkt.h \
		../src/include/pkt_proc.h \
		../src/include/ppi.h \
		../src/include/procwatch.h \
		../src/include/proto_identify.h \
		../src/include/radix_trie.h \
		../src/include/salt.h \
		../src/include/ssh.h \
		../src/include/str_match.h \
		../src/include/tls.h \
		../src/include/updater.h \
		../src/include/utils.h \
		../src/include/wht.h 






#libjoy_la_LIBADD = $(LIBOBJS)