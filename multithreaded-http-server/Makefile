CC = gcc
CFLAGS = -Wall -Wextra -pthread
TARGET = server
SRC = src/server.c

.PHONY: all clean

all: $(TARGET)

$(TARGET): $(SRC)
	$(CC) $(CFLAGS) -o $@ $<

clean:
	rm -f $(TARGET)
