# Movie Fight

**Movie Fight** é uma aplicação web onde os usuários podem comparar dois filmes lado a lado, buscando por eles e exibindo dados como arrecadação de bilheteria, avaliações da crítica, e mais. O aplicativo destaca o filme com melhores estatísticas em verde, tornando a comparação divertida.

## Funcionalidades
- **Buscar Filmes:** Usuários podem buscar filmes nos campos de busca à esquerda e à direita da tela.
- **Autocompletar:** Os campos de busca possuem autocompletar, ajudando os usuários a encontrar filmes, mesmo que só lembrem de parte do título.
- **Comparação de Estatísticas dos Filmes:** Compara filmes com base em estatísticas como bilheteria e avaliações da crítica. Estatísticas superiores são destacadas em verde, enquanto as inferiores aparecem em amarelo.

## Estrutura do Projeto
- **index.html**: Contém o layout principal e a estrutura da aplicação.
- **index.js**: Arquivo principal de JavaScript que lida com a lógica de busca de filmes e a comparação de estatísticas.
- **autocomplete.js**: Gerencia a funcionalidade de autocompletar para as buscas de filmes.
- **utils.js**: Contém funções utilitárias para formatar e exibir os dados.

## Como Funciona
1. **Buscar Filmes:** O usuário digita os títulos dos filmes nos campos de entrada. O autocompletar sugere filmes correspondentes ao texto inserido.
2. **Exibir Resultados:** Quando um filme é selecionado, seu pôster e principais estatísticas são exibidos.
3. **Comparar Filmes:** As estatísticas são comparadas, e o filme com os melhores resultados é destacado em verde.

## Tecnologias Utilizadas
- **Bulma**: Para o design responsivo e limpo da interface.
- **Axios**: Para realizar requisições à API e buscar dados dos filmes.
- **Font Awesome**: Para os ícones usados na interface.

## Executando a Aplicação
1. Clone o repositório.
2. Abra o arquivo `index.html` no navegador.
3. Busque por dois filmes e compare suas estatísticas.

Divirta-se comparando seus filmes favoritos!
