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

## Datalist

    <datalist>:

        - Lista de valores como sugestão a uma tag <input>
        - Valores sugestivos e não obrigatórios
        - Usuários poderão selecionar um dos valores, ou colocar um valor diferente da sugestão.

        ```html
            <datalist id="fruitsdata">
                <option>apple</option>
                <option>banana</option>
                <option>mango</option>
                <option>orange</option>
                <option>cherry</option>
            </datalist>
        ```
    
## List

    - Recebe como valor o id de um <datalist> residente no mesmo documento.

## Tipos de input suportados

    - text, search, url, tel, email, date, month, week, time, datetime-local, number, range e color.

    * Valores de datalist que não são compatíveis com tipo do <input> não serão apresentados.

## Tipos de input não suportados (conforme especificação)

    - hidden, password, checkbox, radio, file, ou qualquer tipo de button

## User Agent
    
    Verificar a compatibiliadade com o browser https://caniuse.com