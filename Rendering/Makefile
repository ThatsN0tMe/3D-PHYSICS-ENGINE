CC := gcc
CPPFLAGS := -Wall -Wextra
EXE := Renderer
OBJS := main.o
LIBS :=

all: $(EXE)

$(EXE): $(OBJS)
	${CC} ${CPPFLAGS} $^ -o $@ ${LIBS}


.PHONY: clean
clean:
	$(RM) $(OBJ) $(EXE)
