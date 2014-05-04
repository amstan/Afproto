test: test.out
	./test.out

test.out: afproto.c crc16.c
	gcc -Wall -g -DAFPROTO_TEST afproto.c crc16.c -o test.out

clean: 
	-rm test.out

.phony: clean test