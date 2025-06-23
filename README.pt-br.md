# sherlockramos.blog

Este repositório contém o código-fonte do blog **sherlockramos.blog**, desenvolvido com [Jekyll](https://jekyllrb.com/) e inspirado no design do x.com.

O site é dividido em quatro seções principais: Home, Blog, Ferramentas e Redes Sociais. Todo o layout segue boas práticas de UX e UI.

## Como publicar

Você pode fazer deploy do seu próprio projeto Jekyll na Vercel.

[![Deploy com Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/vercel/vercel/tree/main/examples/jekyll&template=jekyll)

_Exemplo ao vivo: https://jekyll-template.vercel.app_

### Como Criamos Este Exemplo

Para começar a usar Jekyll com implantação na Vercel, utilize o [Jekyll CLI](https://jekyllrb.com/docs/usage/) para inicializar o projeto:

```shell
$ jekyll new meu-blog
```

## Como rodar localmente

Para visualizar o blog no seu computador antes de publicar:

1.  **Instale as dependências:**
    ```shell
    bundle install
    ```
2.  **Inicie o servidor Jekyll:**
    ```shell
    bundle exec jekyll serve
    ```
    Abra seu navegador em `http://localhost:4000`. O site será atualizado automaticamente sempre que você modificar um arquivo.

## Como criar um novo post

1.  Crie um novo arquivo no diretório `_posts`.
2.  Nomeie o arquivo seguindo o formato: `AAAA-MM-DD-titulo-do-post.md`. (Ex: `2024-07-25-meu-novo-artigo.md`)
3.  Adicione o seguinte cabeçalho (Front Matter) no início do arquivo, ajustando os valores conforme necessário:
    ```markdown
    ---
    layout: post
    title: "Título do Seu Post"
    date: AAAA-MM-DD HH:MM:SS +/-ZZZZ # Ex: 2024-07-25 10:00:00 -0300
    categories: categoria1 categoria2 # Opcional
    ---

    Escreva o conteúdo do seu post aqui usando Markdown...
    ```
4.  Salve o arquivo. Se o servidor Jekyll estiver rodando (`bundle exec jekyll serve`), o post já estará visível no seu ambiente local.
