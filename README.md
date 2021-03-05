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
