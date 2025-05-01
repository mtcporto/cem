# Mapa do Cemitério

## Descrição
Este projeto consiste em um sistema interativo de visualização do mapa de um cemitério, que permite aos usuários localizar e obter informações sobre jazigos. O mapa é representado através de um SVG interativo, onde cada jazigo é clicável e possui informações como identificação, status (ocupado/livre) e nome do proprietário.

## Tecnologias Utilizadas

- **HTML5**: Estruturação da página web
- **CSS3**: Estilização dos elementos, incluindo efeitos de hover e transições
- **JavaScript**: Programação da interatividade do mapa e funcionalidade de busca
- **Bootstrap 5**: Framework CSS para layout responsivo e componentes de UI
- **SVG**: Gráficos vetoriais para representação do mapa do cemitério
- **Bootstrap Icons**: Biblioteca de ícones para elementos da interface

## Funcionalidades

- Visualização completa do mapa do cemitério
- Diferenciação visual entre jazigos ocupados e livres
- Busca por ID do jazigo ou nome do proprietário
- Seleção de jazigos com destaque visual
- Painel de informações com detalhes do jazigo selecionado
- Legenda com código de cores para fácil interpretação

## Como Usar

1. Navegue pelo mapa para visualizar os diferentes jazigos
2. Clique em um jazigo para ver suas informações detalhadas
3. Use a barra de busca para encontrar jazigos por ID ou nome do proprietário
4. Observe a legenda para entender o código de cores (vermelho = ocupado, verde = livre, azul = selecionado)

## Estrutura de Dados

O sistema utiliza um objeto JSON para armazenar as informações dos jazigos, incluindo:
- ID único para cada jazigo
- Coordenadas SVG para desenhar cada jazigo no mapa
- Informações sobre status e proprietário

## Responsividade

O layout foi desenvolvido com Bootstrap 5 para garantir compatibilidade com diferentes tamanhos de tela e dispositivos.