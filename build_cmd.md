# 编译命令
ps: cd 到src 目录下执行：

```shell
g++ .\gl_triangle.cpp -o ../out/triangle -lopengl32 -lglew32 -lfreeglut -lglu32
```

```shell
g++ .\color_triangle.cpp -o ../out/color_triangle -lopengl32 ..\libs\libglfw3dll.a
```
