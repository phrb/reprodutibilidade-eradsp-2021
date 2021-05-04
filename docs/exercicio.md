

# Exercício


## Dependências

-   Distribuição Linux
-   Bash ou outro emulador de terminal
-   Conta no GitHub, Gitlab
-   [Git](https://git-scm.com/downloads)
-   [Docker](https://docs.docker.com/get-docker/)


## Inicialização do Exercício

-   Clone o repositório do curso:

``` bash
git clone https://github.com/phrb/reprodutibilidade-eradsp-2021.git
```

-   Construa a imagem do **Docker**:

``` bash
cd reprodutibilidade-eradsp-2021/exercicio_pratico && ./build.sh -b
```

-   Inicie o servidor **Jupyter**:

``` bash
./build.sh -r
```

-   Pelo seu *browser*, acesse o servidor **Jupyter** usando o *token* gerado:

![img](assets/docker_run.png)

-   Na pasta *work*, abra o notebook do exercício:

![img](assets/load_notebook.png)

-   Todos os pacotes *R* e *datasets* já estão instalados no *notebook*. O exercício
    continua no *Jupyter*
