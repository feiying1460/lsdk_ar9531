INCLUDE = -I ../include -I ../../../../drivers/wlan_modules/os/linux/include/

all:
	gcc $(DEBUG) -c dump.c $(INCLUDE) `pkg-config  --libs --cflags gtk+-2.0`
	gcc $(DEBUG) -c err.c $(INCLUDE) `pkg-config  --libs --cflags gtk+-2.0`

clean:
	rm -f *.o
