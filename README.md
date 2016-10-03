# Linux

## Instalação

```sudo apt-get install texlive-full```

## Compilando

Para compilar o texto através da linha de comando digite:

  ```sh
	  make clean
	  make
  ```

## Estrutura do template

* **Pasta fixos**: Arquivos de configuração, não necessário e nem aconselhável mexer caso não tenha conhecimento.

* **Pasta Figuras**: Onde será inserido as figuras do tipo **.eps**

* **Pasta Editaveis**: Onde será inserido todo o conteúdo do documento.

* **Arquivo Makefile**: Cada arquivo.tex da pasta editaveis terá que ser inserido no makefile na área chamada EDITAVEIS_SOURCES para que seja compilado

* **Arquivo main.tex**: Onde será organizado o corpo do documento, cada arquivo.tex criado na pasta editaveis deve ser
inserido na ordem que irá aparecer no documento através do comando ```\input{editaveis/NomeDoArquivo.tex}```

## Outras informações

Licenciado em Creative Commons Atribuição 3.0: http://creativecommons.org/licenses/by/3.0/

Desenvolvido e adaptado pelo professor Edson Alves edsomjr@gmail.com.

