<div align="center">

# Sorteador de Números

Aplicação web para sortear números aleatórios sem repetição dentro de um intervalo definido pelo usuário, com validação de entradas e animação de transição no resultado.

![Tecnologias utilizadas](https://skillicons.dev/icons?i=html,css,js)

[![Ver demonstração](https://img.shields.io/badge/Ver_demonstra%C3%A7%C3%A3o-2EA44F?style=for-the-badge)](https://otavio-2507.github.io/Sorteador-numeros/)

</div>

## Visão geral

O usuário define o intervalo (de/até) e a quantidade de números desejada; a aplicação valida as entradas (intervalo coerente e quantidade possível dentro do intervalo), sorteia números únicos e exibe o resultado com transição animada. Um botão de reinício restaura o formulário para um novo sorteio.

## Funcionalidades

- Sorteio de números únicos, sem repetição, dentro do intervalo definido
- Validação das entradas: intervalo válido e quantidade compatível
- Exibição animada do resultado do sorteio
- Botão de reinício para configurar um novo sorteio
- Interface responsiva com tipografia temática

## Tecnologias

| Tecnologia | Aplicação no projeto |
| --- | --- |
| JavaScript (ES6+) | Sorteio sem repetição, validação e manipulação de DOM |
| HTML5 | Estrutura do formulário e do resultado |
| CSS3 | Estilização, responsividade e transições |
| Google Fonts | Tipografia (Chakra Petch, Inter) |

## Como executar

```bash
git clone https://github.com/OTAVIO-2507/Sorteador-numeros.git
cd Sorteador-numeros
```

Abra o arquivo `index.html` no navegador. A aplicação é totalmente client-side.

## Estrutura do projeto

```
Sorteador-numeros/
├── index.html          Interface do sorteador
├── app.js              Lógica de sorteio e validação
├── style.css           Estilos da página
└── img/                Imagens de fundo e ilustração
```

