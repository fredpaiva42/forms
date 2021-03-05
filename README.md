# Formulários

## Para que serve?

    - Capturar dados de entrada (input)
    - Interação
    - Controle

## Pré requisitos

    - Básico HTML

## Dominar

    - Estilização
    - Validação
    - Controles customizados
    - Javascript

 ## Tag form

    - Elemento que definirá um formulário
    - É um container estilo `<section> <footer>`

    Atributos básicos
    - action (para onde o form será enviado)
    - method (GET (é o padrão) e POST (os dados não aparecem na url, como no Get))

    * IMPORTANTE - Nunca criar um form dentro de outro form.

## Fieldset

    <fieldset>:
        - agrupamento de campos
        - mesmo propósito
        - semântico
        - acessibilidade
    
    Atributos especiais:
        - disabled
            * desabilita todos os elementos internos
            * não serão enviados ao submeter o formulário
        - form
            * o id de um formulário ao qual esse fieldset pertence
            * não precisa estar dentro do formulário
        - name
            * nome do grupo

## Legend

    <legend>:
        - nome do agrupamento
        - primeiro elemento dentro do fieldset

## Label

    <label>:
        - associar e identificar uma (ou mais) tag de entrada de dados
        - acessibilidade
        - você poderá clicar para mudar o foco da entrada de dados

    Atributos:
        - for
            * para fazer a conexão entre este label e a tag de entrada de dados
            * é feita via id do input
            * só funciona com elementos específicos
                - button, input (not hidden), meter, output,
                progress, select, textarea
            
## Button

    <button>:
        - Representa um botão
        - Usado para enviar formulários
        - É estilizado pelo user agent (navegador)

    Atributos comuns
    - Type
        - submit
        - reset
        - button
    - autofocus
    - disabled
    - name
    - value
    - form
