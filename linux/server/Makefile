TARGET := namestackserver

CFLAGS := -g -I../../../kernel/include

C_SRCS := \
          main.c

OBJECTS := $(patsubst %.c,%.o,$(C_SRCS))

$(TARGET): $(OBJECTS)
	$(CC) $(OBJECTS) $(LFLAGS) -o $@

.PHONY: clean
clean:
	-rm $(TARGET) $(OBJECTS)
