# Projeto 6: Projeto da TripleTen Art Gallery - Layout Responsivo e Avançado

**▶️ Visualizar Projeto Online**(<COLE AQUI O LINK ATUALIZADO DO SEU GITHUB PAGES>)

Este é o sexto projeto da Trilha de Desenvolvimento Web da TripleTen, focado na implementação de um layout responsivo e robusto para a "TripleTen Art Gallery".

## Visão Geral do Projeto

Este projeto implementa um layout responsivo completo para a 'TripleTen Art Gallery', garantindo uma experiência de usuário otimizada em desktop (1280px), tablet (768px) e mobile (320px). O desenvolvimento focou em **soluções avançadas de CSS Grid** para replicar fielmente o design em todas as resoluções especificadas, incluindo o desafio da ordem dos elementos e o posicionamento complexo da seção 'Places'.

## Funcionalidades e Características

- **Layout Responsivo Abrangente:** A página se adapta perfeitamente a diversos breakpoints, desde desktops grandes (1280px) até dispositivos móveis (320px), sem rolagem horizontal indesejada.
- **Design Fiel:** Todos os elementos visuais, espaçamentos, tipografia e cores foram implementados de acordo com os designs fornecidos, com foco na precisão "pixel-perfect".
- **CSS Grid para Layouts Complexos:** Utilização estratégica do **CSS Grid** para construir layouts complexos e dinâmicos, especialmente na seção 'Places', permitindo controle total sobre a posição e fluxo dos elementos em diferentes resoluções.
- **Flexbox:** Aplicação do Flexbox em outras seções para alinhamento e distribuição eficiente de itens.
- **Metodologia BEM:** As classes CSS seguem a metodologia BEM (Bloco Elemento Modificador) para garantir um código organizado, escalável e manutenível.
- **Estrutura Semântica:** O HTML é estruturado semanticamente, utilizando as tags apropriadas para cada tipo de conteúdo, promovendo acessibilidade e manutenibilidade.
- **Otimização de Imagens:** Uso de `object-fit: cover` para garantir que as imagens se adaptem visualmente aos seus contêineres mantendo a proporção.

## Tecnologias Utilizadas

- **HTML5:** Para a estrutura e conteúdo semântico da página.
- **CSS3:** Para a estilização e responsividade, com ênfase em:
  - **CSS Grid**
  - **Flexbox**
  - Media Queries
  - Unidades Relativas (px, em, %)
  - `object-fit`
- **Normalize.css:** Utilizado para garantir a consistência de renderização entre diferentes navegadores.
- **Fonte Inter:** Utilizada para a tipografia do projeto, com arquivos hospedados localmente na pasta `vendor/fonts/` e fontes do sistema como alternativa.

## Estrutura de Arquivos

O projeto segue a metodologia BEM Flat para a organização dos arquivos e pastas:

/
├── .gitignore
├── .editorconfig
├── index.html
├── README.md
├── blocks/
│ ├── header.css
│ ├── cover.css
│ ├── intro.css
│ ├── photo-grid.css
│ ├── places.css
│ ├── footer.css
│ └── base.css
├── images/
│ ├── (todas as imagens do projeto, ex: intro-image.jpg, photo-grid1.png)
│ ├── favicon.png
│ ├── desktop-view.png
│ ├── tablet-view.png
│ └── mobile-view.png
├── pages/
│ └── index.css
└── vendor/
├── normalize.css
└── fonts/
└── (arquivos das fontes utilizadas, ex: Inter-Regular.woff)

### Visualização do Projeto

Para uma melhor compreensão dos recursos, aqui estão algumas capturas de tela do projeto em diferentes seções:

**Visualização em Desktop (1280px):**
![Captura de tela Desktop](./images/desktop-view.png)

**Visualização em Tablet (768px):**
![Captura de tela Tablet](./images/tablet-view.png)

**Visualização em Mobile (320px):**
![Captura de tela Mobile](./images/mobile-view.png)

---

## Planos de Melhoria

Para futuras iterações e aprimoramento do projeto, planejo explorar:

1.  **Animações Suaves:** Adicionar transições e animações CSS sutis para melhorar a experiência visual sem comprometer a performance.
2.  **Componentes Reutilizáveis:** Refatorar o código para identificar e criar componentes CSS mais reutilizáveis, facilitando a manutenção e futuras expansões.

---

### **Principais Mudanças e Por Quê:**

1.  **Título do Projeto:** Atualizado para "Projeto 6" e com um nome mais descritivo como "Layout Responsivo e Avançado" para refletir o nível de complexidade e as soluções aplicadas.
2.  **Visão Geral do Projeto:** A descrição foi aprimorada para mencionar explicitamente o **CSS Grid** como uma técnica fundamental para resolver os desafios de layout, além de Flexbox, e a resolução de problemas de ordem de elementos.
3.  **Funcionalidades e Características:**
    - O ponto sobre "Layout Responsivo" foi expandido.
    - Foi adicionado um ponto específico para **"CSS Grid para Layouts Complexos"**, destacando seu uso crucial na seção 'Places'.
4.  **Tecnologias Utilizadas:** **CSS Grid** foi adicionado como a primeira e mais importante técnica de CSS, refletindo seu papel central no projeto.
