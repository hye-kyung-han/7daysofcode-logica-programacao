# Desafio 7 Days of Code de Lógica em Programação do curso Alura
## Dia 1:

- Reescrever o código de  maneira que ele imprima as informações de maneira correta, que faça sentido e sem erros;
- Utilizar operadores de comparação do JavaScript no código para imprimir o resultado correto no console;

Resultado dado no console:
```
As variáveis numeroUm e stringUm tem o mesmo valor, mas tipos diferentes

As variáveis numeroTrinta e stringTrinta não tem o mesmo tipo

As variáveis numeroDez e stringDez tem o mesmo valor, mas tipos diferentes
```

## Dia 2:

- Desenvolver um programa que exibe as perguntas com as informações que precisamos do usuário;
- Receba essas informações e imprima de volta para o usuário na mensagem personalizada;

Resultado: 

O programa abre um prompt e faz as seguintes perguntas para o usuário:

- Qual o seu nome?
- Quantos anos você tem?
- Qual linguagem de programação você está estudando?

E o programa imprime a seguinte mensagem:
```
Olá [usuario], você tem [idade] anos e já está aprendendo [linguagemProgramacao]!
```

-**Exercício opcional**-

- Você gosta de estudar **linguagemProgramação**? Responda com o número 1 se SIM ou 2 para NÃO.

Se **SIM**, o programa imprime isso:
```
Muito bom! Continue estudando e você terá muito sucesso.
```

Se **NÃO**, o programa imprime isso:
```
Ahh que pena... Já tentou aprender outras linguagens?
```

## Dia 3:

- Desenvolver um programa que cria perguntas/respostas diferentes dependendo da resposta do usuário;
- Adicionar uma pergunta que repete de acordo com a quantidade de respostas que o usuário quiser informar;

Perguntas que o programa faz:
```
1. Se quer seguir para área de Front-End ou seguir para a área de Back-End.

2. Caso esteja na área de Front-End, se quer aprender React ou aprender Vue. Caso esteja na área de Back-End, poderá aprender C# ou aprender Java.

3. Depois, independente das escolhas anteriores, o usuário poderá escolher entre seguir se especializando na área escolhida ou seguir se desenvolvendo para se tornar Fullstack. Você deve exibir na tela uma mensagem específica para cada escolha.

4. Por fim, pergunte quais são as tecnologias nas quais a pessoa gostaria de se especializar ou de conhecer. Aqui, a pessoa pode responder N tecnologias, uma de cada vez. Então, enquanto ela continuar respondendo ok para a pergunta: “Tem mais alguma tecnologia que você gostaria de aprender?”, continue apresentando para ela o Prompt, para que ela complete o nome da tecnologia em questão. E, logo depois, apresente uma mensagem comentando algo sobre a linguagem inserida.
```

## Dia 4:

- Desenvolver um programa de adivinha com interação do usuário;
- o programa deve escolher um número aleatoriamente de 1 a 10;

Perguntas e respostas que o programa faz:
```
[Pergunta inicial]
"Adivinhe de 1 a 10 em qual número estou pensando..."

[Quando o usuário acerta]
"Parabéns! Você acertou. Aperte a tecla F5 para jogar novamente :)"

[Quando acabam as 3 tentativas]
"Ihh! Acabou as tentativas."

[Se você errar todas as tentativas]
"Você usou todas as tentativas, aperte a tecla F5 para jogar novamente."
```

## Dia 5:

- Desenvolver um programa em que o usuário possa adicionar items da lista de compras;
- A cada item adicionado, o programa deve perguntar para o usuário qual das categorias existentes ele se encaixa para organizar a lista;
- No final o programa imprime a lista de compras organizadas pela categoria;

O programa deverá imprimir a seguinte mensagem, por exemplo:
```
Imprimimos a sua lista de compras abaixo

Lista de compras:

Frutas: banana,abacaxi,maça
Laticínios: yogurte
Congelados: frango,carne
Doces: chocolate,doce de leite
```

## Dia 6:

- Adicionar ferramenta nova de remover itens que foram adicionadas na lista;
- A mensagem de remover deve aparecer apenas quando houver algum item já adicionado na lista e não aparecer quando estiver vazia;
- Notificar o usuário quando o item que ele deseja remover não existe na lista;

Quando o item é removido, é imprimido em loop a seguinte mensagem enquanto continuar sendo respondido com "sim" pelo usuário:
```
Item removido com sucesso! Segue a lista atual: [listaVarCategorias]. Deseja remover outro item da lista? Digite SIM ou NÃO."
```

E quando o usuário digita um item não existente, o programa avisa com a seguinte mensagem:
```
Não existe esse item na lista!
```