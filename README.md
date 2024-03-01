# so_long ✅105/100
Small 2D game

- ![so_long subject](fr.so_long.subject.pdf)

Check also my itch.io profile :
- [itch.io](https://dailywind.itch.io/)


I used the MLX 42 for this project as it was authorized in my campus :
- [Link to the MLX42 github](https://github.com/codam-coding-college/MLX42)
- 
The MLX 42 naturally have leaks, you can suppress them with the following command when using valgrind
```shell
valgrind --suppressions="mlx42.supp" ./so_long <MAP PATH>
```


The program is divided in 3 parts :
- Map checking (*.ber)
- Map making
- Commands & Events

  ![](project_structure.PNG)

  To use the program, you must do these commands :
```shell
cd so_long
make

# Program :
./so_long <MAP PATH>
```

You also have these commands for cleaning the push_swap directory :
```shell
# Clean all object files (*.o)
make clean

# Clean static library & object files
make fclean

# Clean everything and recompile the static library
make re
```
