all: v

v: v.c
	cc -std=gnu11 -w -o v v.c
	./v -o v .

v.c:
	wget https://raw.githubusercontent.com/vlang/vc/master/v.c

test:
	find .. -name '*_test.v' | xargs v {}

clean:
	-rm vc v.c
