<h1 align="center">Ola Mundo em Cobol <img src="https://user-images.githubusercontent.com/40872405/202004195-6f50155f-146e-4794-beb5-39aba1b697cd.png" width="100" height="100">
</h1>


<h1 align="center">
    <a href="https://www.cadcobol.com.br/enterprise_cobol_for_z_os_documentation_library.htm">🔗 Cobol</a>
</h1>
<p align="center">Um simples Hello World para eu tentar me familiarizar com a language</p>

## Eu queria testar algo rapido então baixei o cobol para ubuntu segue os commandos 

```bash
# Primeiro instale o cobc compiler
$ sudo apt-get install open-cobol

# Depois clone esse repositorio
$ git clone https://github.com/carlinhoshk/Ola-mundo-em-Cobol.git

# Abra a pasta do projeto
$ cd OlaMundo-Cobol

# rode o arquivo já compilado
$ ./OlaMundo
```

## Como o projeto já está Compilado você só precisa executar o ./OlaMundo na sua maquina
### Mas caso queira editar e fazer ao seu gosto vou deixar em baixo como compilar novamente o codigo após feitas mudança em codigo

```bash
# Após fazer suas edições no arquivo OlaMundo.cbl salve e feche-o e rode o compilador coboc
$ cobc -x OlaMundo.cbl
# O parametro -x é para criar um programa executavel 
# Depois execute na sua maquina no meu caso ubuntu, lembrando não precisa dar permissão chmod nem nada já virou um executavel
$ ./OlaMundo
```


##### segue um gif do processo de compilação e execução. 

![ezgif com-gif-maker1](https://user-images.githubusercontent.com/40872405/202006927-ce8b9064-9e47-49e1-ab47-7407888cc6d5.gif)

