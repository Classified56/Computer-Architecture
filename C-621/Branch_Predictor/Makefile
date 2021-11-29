SOURCE	:= Main.c Trace.c Branch_Predictor.c Branch_Predictor.h
CC	:= gcc
TARGET	:= Main
LINK	:= -lm

all: $(TARGET)

$(TARGET): $(SOURCE)
	$(CC) -o $(TARGET) $(SOURCE) $(LINK)

clean:
	rm -f $(TARGET)
