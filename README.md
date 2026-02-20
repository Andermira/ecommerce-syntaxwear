# SyntaxWear E-commerce

Este é o repositório para o site de e-commerce da SyntaxWear, uma loja online especializada em tênis e sneakers. O projeto foi desenvolvido utilizando HTML e CSS puros, com foco em uma estrutura organizada e um design moderno.

## 🚀 Visão Geral

O site da SyntaxWear é uma landing page estática que apresenta a marca, suas categorias de produtos e destaques. O layout é responsivo e foi construído com uma abordagem de componentes para o CSS, facilitando a manutenção e a escalabilidade.

## ✨ Funcionalidades

- **Header:** Navegação principal com links para categorias (Masculino, Feminino, Outlet), páginas institucionais (Nossas Lojas, Sobre) e ícones de acesso rápido (Conta, Ajuda, Carrinho).
- **Seção Hero:** Uma grande imagem de banner com um slogan e botões de chamada para ação (CTA) para "Ver Modelos" e "Comprar".
- **Categorias de Produto:** Seção visual que destaca as principais categorias de tênis: Casual, Esporte, Moderno e Futurista.
- **Grid de Produtos:** Uma grade de layout que exibe produtos e modelos em destaque.
- **Footer:** Contém um formulário de inscrição para newsletter, links para redes sociais e um mapa de navegação do site.

## 📁 Estrutura do Projeto

O projeto está organizado da seguinte forma:

```
ecommerce-syntaxwear/
├── index.html                # Arquivo principal da página
├── README.md                 # Este arquivo
├── css/
│   ├── base.css              # Estilos base (cores, fontes, etc.)
│   ├── reset.css             # Reset de estilos do navegador
│   ├── variables.css         # Variáveis CSS globais
│   └── components/           # Estilos para componentes específicos
│       ├── footer.css
│       ├── header.css
│       ├── hero.css
│       ├── product-category.css
│       └── product-grid.css
└── images/
    ├── banners/              # Imagens para a seção hero
    ├── favicons/             # Favicons do site
    ├── icons/                # Ícones de UI e redes sociais
    ├── logo/                 # Logo da SyntaxWear
    └── products/             # Imagens de produtos e modelos
```

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Para a estrutura semântica do conteúdo.
- **CSS3:** Para a estilização, utilizando uma arquitetura baseada em componentes e variáveis CSS para um código mais modular.

## 🎨 Design e Estilo

- **Reset:** Utiliza um arquivo `reset.css` para garantir uma base de estilos consistente entre diferentes navegadores.
- **Variáveis CSS:** Centraliza a definição de cores, fontes e outras propriedades em `variables.css` para facilitar a customização do tema.
- **Componentização:** Os estilos são divididos em arquivos por componente (`header.css`, `footer.css`, etc.), tornando o CSS mais organizado e reutilizável.

## 🏁 Como Executar

Por ser um projeto puramente front-end com arquivos estáticos, basta abrir o arquivo `index.html` em seu navegador de preferência.

1. Clone este repositório:
   ```sh
   git clone <https://github.com/Andermira/ecommerce-syntaxwear.git>
   ```
2. Navegue até o diretório do projeto:
   ```sh
   cd ecommerce-syntaxwear
   ```
3. Abra o `index.html` no seu navegador.

---

Este README foi gerado para documentar a estrutura e o propósito do projeto SyntaxWear.
