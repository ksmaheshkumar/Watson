CFLAGS=-O2 -g -pipe -Wall -Wp,-D_FORTIFY_SOURCE=2 -fexceptions -fstack-protector --param=ssp-buffer-size=4 -m64 -mtune=generic -Werror 


watson: watson.c watson.h
	gcc ${CFLAGS} -o watson watson.c

clean: watson
	rm watson
