CC = gcc

OBJS = $(wildcard *.c)

TARGET = libhello.so

COMM_FILE_LIST= \
    G711.c

all:
　　$(CC) $(OBJS) -fPIC -shared -o $(TARGET)
　　sudo mv ./$(TARGET) /lib

clean:
　　rm $(SRCS) $(headfile)