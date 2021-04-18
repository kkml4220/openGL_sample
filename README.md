# OpenGL sample

OpenGLのサンプルです.

![image](./images/pot.png)

## installation

### Command Line Tools

次のコマンドでxcode command line toolsをインストール.

```bash
sudo xcodebuild -license
```

## 実行

### コンパイル

次のコマンドでコンパイル.

```bash
g++ -framework GLUT -framework OpenGL main.cpp
```


### 実行

コンパイルが正常に終了すると.`a.out`とういう実行ファイルができる.
そこで次のコマンドで実行.

```bash
./a.out
```
