
# 🗓️ Parte 2: Roteiro de Execução e Atividades Específicas por Sprint

O desenvolvimento do portal da TechNova será realizado em **2 Sprints**. Todas as especificações técnicas do que você deve construir estão detalhadas nas tarefas de cada Sprint abaixo:

---


## 🎨 SPRINT 2: Otimização Gráfica (WebP/SVG), Estilização CSS3 & Entrega Final via GitHub
**Foco da Sprint:** Otimizar todas as mídias para alta performance web, incorporar vetores SVG inline, desenvolver a folha de estilos `css/style.css` completa e realizar a auditoria W3C + entrega oficial via **GitHub e GitHub Pages**.

### 📌 Atividades Específicas da Sprint 2:

#### [ ] Tarefa 2.1 – Otimização de Imagens (WebP) e Gráficos Vetoriais (SVG Inline)
- **Conversão para WebP:** Utilizar ferramentas gráficas/compressores (como *Squoosh*, *TinyPNG* ou editor gráfico) para converter e comprimir todas as fotografias do site (Hero, Equipe e Blog) para o formato **`.webp`**, salvando-as na pasta `img/` e garantindo que todas possuam `alt` descritivo, `width` e `height`.
- **Incorporação de SVG Inline:** Inserir códigos vetoriais `<svg>` diretamente no HTML para o logotipo da TechNova, os ícones dos 3 cards de Serviços e os ícones de redes sociais no Rodapé.

#### [ ] Tarefa 2.2 – Criação do `style.css`, Seletores e Modelagem do Box Model
- Criar o arquivo `css/style.css` e vinculá-lo no `<head>` do `index.html`.
- Aplicar o seletor universal (`*`) para reset de `margin: 0`, `padding: 0` e `box-sizing: border-box`, além de `scroll-behavior: smooth` no `html`.
- Definir a paleta de cores corporativa da TechNova e a tipografia, utilizando seletores de **tag**, **classe (`.`)** e **identificador (`#`)** de forma organizada.
- Modelar todas as seções, cartões e botões aplicando com precisão as propriedades do **Box Model** (`width`, `margin`, `padding`, `border`, `border-radius` e `box-shadow`) e enquadramento de imagens sem distorção (`object-fit: cover`).

#### [ ] Tarefa 2.3 – Diagramação, Posicionamento (`sticky`, `relative`, `absolute`) e `z-index`
- **Menu Superior Fixo:** Aplicar `position: sticky` (ou `fixed`), `top: 0` e `z-index: 1000` no `<header>` para que a barra de navegação acompanhe a rolagem da tela sem ficar por baixo de outros elementos.
- **Badges Sobrepostas no Blog:** Aplicar `position: relative` no container da imagem do artigo do blog e `position: absolute` na etiqueta de categoria para que ela flutue sobre o canto da foto.
- **Carrossel / Galeria Hero:** Estilizar a galeria da Hero Section com rolagem fluida (*CSS Scroll Snap* com `scroll-snap-type: x mandatory` ou animação `@keyframes`).

#### [ ] Tarefa 2.4 – Estilização da Tabela Zebrada, Formulário e SVGs com Pseudo-classes
- **Tabela Comparativa:** Aplicar `border-collapse: collapse`, estilizar cabeçalhos e implementar o **efeito zebrado** nas linhas do `<tbody>` utilizando a pseudo-classe `:nth-child(even)`, além de destaque ao passar o mouse (`tr:hover`).
- **Formulário de Contato:** Estilizar os inputs, `<select>` e `<textarea>`, aplicando feedback visual claro quando o usuário clica no campo através da pseudo-classe `:focus` (`outline` / `border-color`).
- **Estilização de SVG via CSS:** Customizar as cores de preenchimento (`fill`) e contorno (`stroke`) dos ícones `<svg>` inline pelo CSS, alterando sua cor ou escala no estado `:hover`.

#### [ ] Tarefa 2.5 – Efeitos Visuais, Gradientes, Transições e Transformações
- Aplicar `linear-gradient` nos elementos de destaque (como o botão CTA da Hero Section).
- Implementar **microinterações suaves** em todos os botões, links do menu e cartões de equipe/serviços/blog combinando `transition` com `transform` (`translateY`, `scale` ou `rotate`) e `opacity` no `:hover`.

#### [ ] Tarefa 2.6 – Depuração DevTools, Validação W3C via GitHub e Entrega Oficial
- Inspecionar a página utilizando o **DevTools (`F12`)** do navegador para testar a responsividade, o alinhamento das caixas e o funcionamento de todas as âncoras do menu e do botão *"Voltar ao Topo"*.
- Atualizar o repositório no GitHub (`git push` ou upload) com a versão final da Sprint 2.
- **Auditoria W3C via URL do GitHub Pages:** Validar o link público `https://seu-usuario.github.io/technova-solutions/` no **W3C Markup Validator (HTML)** e no **W3C CSS Validator**, garantindo **0 erros (Zero Errors)** (consulte o *Guia Orientador de Entrega e Validação W3C via GitHub*).
- Incluir os selos/prints de validação no arquivo `README.md` do repositório e enviar os links ao professor!
