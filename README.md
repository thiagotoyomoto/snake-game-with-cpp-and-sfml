# Jogo da Cobra com C++ e SFML

## Tecnologias utilizadas

| Tecnologias                       | Versões |
|-----------------------------------|---------|
| C++                               | 17      |
| [Meson](https://mesonbuild.com/)  | 1.8.2   |
| [Ninja](https://ninja-build.org/) | 1.8.2   |
| [SFML](https://www.sfml-dev.org/) | 2.5.1   |

## Compilação

Primeiro, você deve gerar os arquivos de *build* do Meson:

```
meson build
```

Depois deste processo, execute o Ninja:

```
ninja -C build
```

O binário/executável estará na pasta *build*