# data-internship-test

Esse teste tem como objetivo final a construção de um sistema de recomendações.

Instruções do que o seu programa deve fazer:

1. Gerar dois arquivos csv com dados fake que simulam a interação entre usuarios e itens, através de uma biblioteca de geração de dados fake (EX: [faker](https://pypi.org/project/Faker/) ) , 1 deve conter dados implicitos de interação e o outro dados explicitos.
2. Criar um modelo de recomendações para cada um dos csv's gerados. Voce pode usar um framework como por exemplo o [turicreate](https://github.com/apple/turicreate)
3. Voce podera criar ou uma API que recebe o email do user(um dos que estarão no csv) como parametro e devolve uma lista de itens recomendados. Pode-se usar um framework como o [flask](https://programminghistorian.org/en/lessons/creating-apis-with-python-and-flask) ou uma aplicação que rode no terminal, onde o user podera digitar o email diretamente no terminal, e ver a lista de itens recomendados no terminal.

### Exemplo de dados implicitos

email | item_id
------------ | -------------
teste@teste.com | 480
teste_2@teste.com | 522


### Exemplo de dados explicitos

email | item_id | rating
------------ | ------------- | -------------
teste@teste.com | 480 | 5
teste_2@teste.com | 522 | 2


É importante que o seu teste contenha um arquivo Readme.md explicando como rodar o projeto que voce construiu, e explicando como funciona o seu modelo de recomendaçes. 
