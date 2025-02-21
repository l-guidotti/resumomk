# MARKDOWN

Aqui vou descrever e mostrar algumas estruturas nas quais acredito que sejam fundamentais e usuais no dia a dia.

<!--Comentários-->
## Comentários

Começando pelos **comentários**. A estrutura de comentário do MD (MarkDown) é exatamente igual a do HTML o que facilita para quem já tem familiaridade com esta linguagem de marcação. Se utiliza o **<!---- >** (sem o espaço)

## Títulos e Subtítulos

Essa seção apresenta o que para mim é uma das coisas mais importantes no MD que é a formatação dos Títulos e Subtítulos. Para isso se utiliza o **#**
# H1 - Usa-se:#
## H2 - Usa-se:##
### H3 - Usa-se:###
#### H4 - Usa-se:####
##### H5 - Usa-se:#####
###### H6 - Usa-se:######

## Texto

- Negrito: Se envolve o texto com ** ou __ Exemplo: **Negrito**
- Itálico: Se envolve o texto com * ou _ Exemplo: *Itálico*
- Negrito e Itálico: Combina os dois  
Exemplo: ***Texto em Negrito Itálico***

## Citações

Para criar uma citação basta utilizar somente um > Exemplo:
>Citação de exemplo.

## Tabelas

As tabelas são estruturas importantes e que podem ser amplamente utilizadas, para criá-las basta utilizar | para colunas e - para oi cabeçalho. Exemplo:

| Tabela 1 | Tabela 2 |
|--------|---------|
| Item 1 | Item 2 |
| Item 3 | Item 4 |

## Listas

Chegamos as listas, também muito úteis e simples de utilizar, basta inserir um único * ou - para criar uma lista não ordenada e se quiser criar uma lista ordenada basta utilizar um número seguido de ponto. Exemplos:

- Lista não ordenada
- Lista não ordenada
- Lista não ordenada  

1. Lista ordenada
2. Lista ordenada
3. Lista ordenada

## Checklists (Task Lists)

Ótimas pra gerenciar tarefas e acompanhar o progresso de um projeto.
- [ ] Exemplo 1
- [ ] Exemplo 2
- [x] Exemplo 3

## Links e Imagens
Para criar um link coloca-se um texto dentro de colchetes seguido da URL dentro de parênteses. Exemplo:
[Compass UOL](https://compass.uol/en/home/)

Para adicionar um imagem coloca-se um ponto de exclamação seguido por uma descrição da imagem dentro de colchetes e com a URL da imagem dentro de parênteses 
![Imagem Exemplo](https://compass.uol/content/aircompanycompass/en/home.coreimg.png/structure/jcr%3acontent/root/header_copy/logoImg/1737576379917/logo-desktop.png)


## Tabela de Conteúdos (TOC)

Em documentos mais extensos, é bacana ter uma TOC para facilitar a navegação. Alguns editores e plataformas (como o GitHub) geram automaticamente se você usar os cabeçalhos, mas você também pode criar links manuais para cada seção.
- [Introdução](#introdução)
- [Exemplos de Código](#exemplos-de-código)
- [Conclusão](#conclusão)


## Blocos de Código

- Código inline:  
    Use uma crase: 
    `código`
- Bloco de código:
    Utilize três crases:
    ```
    <h1> Exemplo </h1>
    <p> Exemplo de Código </p>
