SRC = main.c\
src/e1.c\

INC = -Iinc

PROJECT_NAME = been.out
BUILD = build

$(PROJECT_NAME): $(SRC)
	gcc $(SRC) $(INC) -o $(PROJECT_NAME)

run:$(PROJECT_NAME)
	./${PROJECT_NAME}


clean:
	rm -rf $(PROJECT_NAME) documentation/html
$(BUILD):
mkdir build
