
### Arquivos

- `index.html`: Contém a estrutura HTML da aplicação.
- `script.js`: Contém a lógica JavaScript para tocar os sons e compor sequências.
- `style.css`: Contém os estilos CSS para a aparência da aplicação.
- `sounds/`: Pasta que contém os arquivos de áudio para cada tecla.

## Como Usar

1. Abra o arquivo `index.html` em um navegador web.
2. Pressione as teclas `Q`, `W`, `E`, `A`, `S`, `D`, `Z`, `X`, `C` no teclado para tocar os sons correspondentes.
3. Clique nos botões na tela para tocar os sons.
4. Para compor uma sequência de sons:
   - Digite a sequência de teclas no campo de texto (por exemplo, `qweasdzxc`).
   - Clique no botão "Tocar" para reproduzir a sequência.

## Estrutura do Código

### HTML (`index.html`)

- Contém a estrutura básica da página, incluindo os botões para cada tecla e os elementos de áudio.
- Inclui um campo de texto e um botão para compor e tocar sequências de sons.

### CSS (`style.css`)

- Define o estilo da página, incluindo a aparência dos botões, do campo de texto e do botão de tocar.
- Estiliza o layout da página para centralizar os elementos e definir cores e fontes.

### JavaScript (`script.js`)

- Adiciona eventos para tocar sons ao pressionar teclas ou clicar nos botões.
- Função `playSound(sound)`: Toca o som correspondente à tecla pressionada e adiciona uma classe de estilo ao botão.
- Função `playComposition(songArray)`: Reproduz uma sequência de sons com base na entrada do usuário.

## Exemplo de Uso

1. Pressione a tecla `Q` no teclado ou clique no botão `Q` na tela para tocar o som correspondente.
2. Digite `qweasdzxc` no campo de texto e clique no botão "Tocar" para reproduzir a sequência de sons.

## Autor

Criado por Bruno Sousa.

