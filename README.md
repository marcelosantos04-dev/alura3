# 🏊 NATAÇÃO PRO - Website Interface

Interface moderna e responsiva de um website sobre natação, com informações sobre artigos, equipamentos e mergulho.

## 📋 Características

✅ **Design Moderno**: Layout limpo e profissional com gradientes e sombras  
✅ **Totalmente Responsivo**: Funciona perfeitamente em desktop, tablet e mobile  
✅ **Menu de Navegação**: Menu sticky com links suaves para cada seção  
✅ **Informações Completas**: Detalhes sobre 8 equipamentos de mergulho diferentes  
✅ **Grid Layout**: Uso de CSS Grid para melhor responsividade  
✅ **Otimizado para VSCode**: Código bem estruturado e comentado  
✅ **Modo Escuro**: Suporte para preferência de modo escuro do sistema  

## 📁 Estrutura de Arquivos

```
alura3/
├── index.html       # Arquivo HTML principal
├── styles.css       # Estilos CSS completos
└── README.md        # Este arquivo
```

## 🚀 Como Usar

### Opção 1: Live Server (Recomendado)
1. **Abra em VSCode**: `code .`
2. **Instale a extensão Live Server** (se não tiver)
3. **Clique com botão direito** no `index.html`
4. **Selecione**: "Open with Live Server"

### Opção 2: Abrir no Navegador
1. **Clique com botão direito** no `index.html`
2. **Selecione**: "Open with" → Seu navegador preferido

### Opção 3: Terminal
```bash
# Copie o caminho do arquivo e abra no navegador
# Exemplo: file:///C:/caminho/para/alura3/index.html
```

## 🎨 Seções do Website

### 1. **Header (Cabeçalho)**
- Logo "NATAÇÃO PRO" em caixa alta
- Menu de navegação com 5 items principais
- Design sticky que fica na parte superior durante rolagem

### 2. **Hero Section**
- Imagem de fundo gradiente
- Título chamativo: "BEM-VINDO AO MUNDO DA NATAÇÃO"
- Botão de ação com efeito hover

### 3. **Artigos Destacados**
- 3 cards com artigos sobre natação
- Ícones emoji para visual agradável
- Efeito hover com transformação

### 4. **Equipamentos Essenciais**
- 4 cards com equipamentos básicos:
  - Óculos de Natação 🕶️
  - Boias e Flutuadores 🏐
  - Nadadeiras 🧤
  - Maiô/Sunga Performance 👕

### 5. **Equipamentos de Mergulho** ⭐
- 8 cards detalhados com:
  - Nome e ícone
  - Descrição técnica
  - Capacidade/Especificações
  - Informações de profundidade e material

**Equipamentos descritos:**
1. 🤿 **Cilindro de Ar** - Fornece oxigênio até 40 metros
2. 🥽 **Máscara de Mergulho** - Visão de 180 graus
3. 💨 **Snorkel** - Respiração na superfície
4. 🦶 **Nadadeiras** - Propulsão eficiente
5. 🧥 **Wetsuit** - Proteção térmica (3-7mm)
6. ⌚ **Computador de Mergulho** - Monitor em tempo real
7. 🎒 **BCD** - Compensador de flutuabilidade (15-25L)
8. ⚖️ **Peso de Mergulho** - Flutuabilidade neutra (2-10kg)

### 6. **Footer**
- Informações da empresa
- Links rápidos
- Dados de contato

## 🛠️ Variáveis CSS Utilizadas

O arquivo CSS utiliza variáveis CSS (Custom Properties) para facilitar manutenção:

```css
--cor-primaria: #0077be         /* Azul principal */
--cor-secundaria: #00d4ff       /* Ciano/Azul claro */
--cor-escura: #003d66           /* Azul escuro */
--cor-fundo: #f0f8ff            /* Fundo claro */
--cor-texto: #333333            /* Texto escuro */
--cor-branco: #ffffff           /* Branco */
--cor-destaque: #ff6b6b         /* Vermelho destaque */
```

## 📱 Responsividade

- **Desktop** (1200px+): Grid com 3 colunas
- **Tablet** (768px - 1199px): Grid com 2 colunas
- **Mobile** (até 480px): Grid com 1 coluna

## ⚡ Otimizações Implementadas

- ✨ **Variáveis CSS**: Facilita manutenção e mudanças rápidas
- 📦 **Nomenclatura BEM**: Classes bem estruturadas
- 🎯 **Semantic HTML**: Uso correto de tags HTML5
- 🎨 **Gradientes**: Uso de gradientes em vez de imagens
- ⚙️ **Flexbox e Grid**: Layouts modernos e flexíveis
- 📝 **Comentários**: Código bem documentado
- 🔄 **Smooth Scroll**: Navegação suave entre seções
- 🌙 **Dark Mode**: Suporte a preferência do sistema
- 🚀 **Performance**: CSS minimalista e eficiente
- 📐 **Units relativos**: Uso de rem, em e % para melhor escalabilidade

## 🎓 Conceitos Utilizados

- ✅ HTML5 Semântico
- ✅ CSS3 Avançado (Grid, Flexbox, Gradientes)
- ✅ Variáveis CSS (Custom Properties)
- ✅ Media Queries
- ✅ Mobile-First Design
- ✅ Acessibilidade
- ✅ Performance Web
- ✅ Nomenclatura BEM

## 🎯 Como Personalizar

### Mudar Cores
Edite as variáveis no topo do `styles.css`:

```css
:root {
    --cor-primaria: #0077be;      /* Mude para sua cor */
    --cor-secundaria: #00d4ff;    /* Mude para sua cor */
    /* ... */
}
```

### Adicionar Novo Equipamento
No `index.html`, dentro da seção `#mergulho`, adicione:

```html
<div class="mergulho-card">
    <h3>🆕 Nome do Equipamento</h3>
    <p><strong>Descrição:</strong> Sua descrição aqui.</p>
    <p><strong>Especificação:</strong> Detalhe técnico</p>
    <p><strong>Material:</strong> Material utilizado</p>
</div>
```

### Modificar Textos
Todos os textos estão no `index.html`. Basta localizar e editar:

```html
<!-- Exemplo: Mudar título -->
<h2>BEM-VINDO AO MUNDO DA NATAÇÃO</h2>
<!-- Mude para -->
<h2>SEU NOVO TÍTULO AQUI</h2>
```

## 🔧 Extensões VSCode Recomendadas

- **Live Server** - Para visualizar em tempo real
- **CSS Peek** - Para inspecionar CSS
- **HTML CSS Support** - Para sugestões de completamento
- **Prettier** - Para formatação automática
- **Thunder Client** - Para testar APIs (se expandir o projeto)
- **Color Picker** - Para escolher cores facilmente

## 💡 Dicas de Desenvolvimento

1. **Use a aba Inspetor (F12)** para ver mudanças em tempo real
2. **Teste em diferentes dispositivos** usando o modo responsivo (Ctrl+Shift+M)
3. **Verifique a acessibilidade** testando com leitores de tela
4. **Otimize as imagens** antes de adicionar ao projeto
5. **Use control+Shift+P** para a paleta de comandos do VSCode

## 📊 Compatibilidade de Navegadores

- ✅ Chrome (versão 90+)
- ✅ Firefox (versão 88+)
- ✅ Safari (versão 14+)
- ✅ Edge (versão 90+)
- ✅ Opera (versão 76+)

## 🎓 Para Aprender Mais

- [MDN - CSS Grid](https://developer.mozilla.org/pt-BR/docs/Web/CSS/grid)
- [MDN - Flexbox](https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Flexible_Box_Layout)
- [HTML Semântico](https://developer.mozilla.org/pt-BR/docs/Glossary/Semantics)
- [Responsive Design](https://developer.mozilla.org/pt-BR/docs/Learn/CSS/CSS_layout/Responsive_Design)

## 📝 Licença

Este projeto é de código aberto e pode ser utilizado livremente para fins educacionais e comerciais.

## 🤝 Contribuições

Sinta-se à vontade para fazer fork, modificar e melhorar este projeto!

---

**Desenvolvido com ❤️ para aprender e praticar HTML & CSS**

**Última atualização:** Junho 2024
