# Sistema de Perguntas e Respostas

Este é um sistema simples de perguntas e respostas onde o usuário responde a questões e o sistema verifica se as respostas estão corretas. Ao final, o sistema informa quantas perguntas o usuário acertou.

## Funcionalidades

- O sistema apresenta perguntas com várias opções de resposta.
- O usuário escolhe uma opção digitando o número correspondente.
- O sistema verifica se a resposta está correta e informa se o usuário acertou ou errou.
- Ao final, o sistema exibe o número de acertos do usuário.

## Estrutura do Projeto

O código é composto por um conjunto de perguntas e respostas definidas em um formato de lista de dicionários. Cada dicionário contém:
- **'Pergunta'**: A questão a ser respondida.
- **'Opções'**: Uma lista de alternativas para a resposta.
- **'Resposta'**: A alternativa correta.

O código também conta com um contador de acertos (`qtd_acertos`) que é incrementado toda vez que o usuário responde corretamente a uma pergunta.

## Como Funciona

1. O sistema percorre a lista de perguntas.
2. Para cada pergunta, ele exibe as opções numeradas para o usuário escolher.
3. O usuário deve digitar o número da opção que acha correta.
4. O sistema verifica se a resposta está correta e exibe um feedback (Acertou ou Errou).
5. Ao final, o sistema exibe o total de acertos do usuário.

## Exemplo de Execução

### Entrada:
```
Quanto é 2+2?
1) 1
2) 3
3) 4
4) 5
Escolha uma opção: 3
Acertou 👍

Quanto é 5*5?
1) 25
2) 55
3) 10
4) 51
Escolha uma opção: 1
Acertou 👍

Quanto é 10/2?
1) 4
2) 5
3) 2
4) 1
Escolha uma opção: 2
Acertou 👍
```

### Saída:
```
Você acertou 3
de 3 perguntas
```

## Como Usar

1. Copie o código para um arquivo Python `.py`.
2. Execute o arquivo no seu terminal ou editor de código Python preferido.
3. O programa exibirá as perguntas e opções. O usuário deve digitar o número da opção desejada.
4. Ao final, o programa exibirá o número de acertos.

## Requisitos

- Python 3.x

## Contribuindo

Se você deseja contribuir com este projeto, fique à vontade para abrir **issues** ou **pull requests**. Algumas melhorias que podem ser feitas incluem:
- Adicionar mais perguntas.
- Melhorar a interface de usuário.
- Adicionar mais funcionalidades, como armazenar o histórico de acertos.

## Licença

Este projeto é de código aberto e pode ser modificado ou compartilhado conforme necessário.

---

Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato! 😄
