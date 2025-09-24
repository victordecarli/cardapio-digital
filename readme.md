# Estrutura de Pastas - Documentação de Uso

Esta seção descreve como utilizar a estrutura de pastas do projeto para organizar arquivos e facilitar o desenvolvimento e manutenção.

## Organização Recomendada
  - **pages/**: Páginas htmls da aplicação.
  - **styles/**: Estilos css de cada pagina e componente.
  - **assets/**: Imagens, fontes e outros recursos estáticos.

## Como Utilizar

1. **Adicionar novos arquivos**: Sempre crie arquivos nas pastas correspondentes ao seu propósito.
2. **Manter a separação de responsabilidades**: Evite misturar lógicas diferentes em uma mesma pasta.
3. **Facilitar a navegação**: Nomeie pastas e arquivos de forma clara e objetiva.
4. **Atualizar a documentação**: Sempre que alterar a estrutura, atualize esta documentação.
5. **Utilize os estilo global.css**: Para pegar valores da paleta de cor e estilos globais como de botao e outros.
6. **Importe o estilo global.css em cada page HTML**: Em vez de importa os styles nomedapagina.css importe diretamente o global.css (pois ele ja esta importando todos os estilos por pagina).

## Exemplo

- pages/nomedapagina.html
- styles/nomedapagina.css
