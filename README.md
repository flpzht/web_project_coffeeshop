# Coffee Shop - Triple Peaks Library ☕

## Descrição do Projeto

Este projeto consiste em um site responsivo para uma cafeteria localizada na biblioteca Triple Peaks. O site apresenta informações sobre o estabelecimento, receitas de café, um formulário de reserva de mesa e informações de contato através das redes sociais.

A página foi desenvolvida como parte do curso de Desenvolvimento Web da Practicum, aplicando conceitos avançados de HTML e CSS, com foco em semântica, acessibilidade e organização de código seguindo a metodologia BEM (Block Element Modifier).

## Funcionalidades

- **Seção Header**: Apresentação da cafeteria com horários de funcionamento e endereço
- **Seção de Receitas**: Vídeos do YouTube incorporados mostrando receitas de café (Aeropress e Prensa Francesa)
- **Formulário de Reserva**: Sistema de reserva de mesa com validação de campos obrigatórios
- **Footer**: Links para redes sociais e informações de copyright

## Tecnologias Utilizadas

### HTML5
- Estrutura semântica com tags apropriadas
- Formulários com validação nativa do HTML5
- Tipos de input específicos (text, number, datetime-local, email, checkbox)
- Atributos de acessibilidade (alt, title, labels)
- Meta tags para SEO e responsividade

### CSS3
- **Metodologia BEM** para organização e nomenclatura de classes
- **Arquitetura modular** com separação em múltiplos arquivos CSS por bloco
- Flexbox para layouts responsivos
- Posicionamento absoluto e relativo
- Backgrounds com imagens SVG
- Transições e efeitos hover
- Custom checkbox styling
- Google Fonts (Inter e Noto Serif)
- Normalize.css para consistência entre navegadores

### Organização de Arquivos
```
project/
├── blocks/
│   ├── page.css
│   ├── header.css
│   ├── nav.css
│   ├── recipes.css
│   ├── reservation.css
│   ├── form.css
│   └── footer.css
├── images/
├── pages/
│   └── index.css (arquivo principal de importação)
├── vendor/
│   └── normalize.css
└── index.html
```

## Destaques Técnicos

- ✅ Código 100% validado (HTML e CSS)
- ✅ Semântica apropriada e acessibilidade
- ✅ Organização BEM para escalabilidade
- ✅ Formulário funcional com validação
- ✅ Estados hover e active em elementos interativos
- ✅ Checkbox customizado com ícone SVG
- ✅ Integração com vídeos do YouTube
- ✅ Design fiel ao protótipo fornecido

## Planos de Melhoria Futura

### 1. Responsividade Completa
- Implementar media queries para tablets (768px) e smartphones (320px)
- Adaptar o layout do formulário para telas menores
- Criar um menu hambúrguer para navegação mobile
- Ajustar tamanhos de fonte e espaçamentos para diferentes viewports

### 2. Funcionalidade Backend
- Integrar o formulário com um servidor para processamento real de reservas
- Implementar confirmação de reserva por e-mail
- Criar um sistema de disponibilidade de mesas em tempo real
- Adicionar calendário interativo para seleção de data

### 3. Seção de Menu
- Criar uma nova seção apresentando o cardápio da cafeteria
- Incluir imagens dos produtos
- Adicionar filtros por categoria (bebidas quentes, frias, doces, etc.)
- Implementar preços e descrições detalhadas

### 4. Melhorias de UX/UI
- Adicionar animações suaves ao scroll entre seções (smooth scroll)
- Implementar lazy loading nas imagens e vídeos
- Criar um sistema de feedback visual ao enviar o formulário
- Adicionar microinterações nos botões e links

### 5. Performance e SEO
- Otimizar imagens (converter para WebP)
- Implementar carregamento assíncrono de recursos
- Adicionar schema markup para SEO local
- Criar páginas adicionais (sobre, blog de receitas, etc.)

### 6. Acessibilidade Avançada
- Implementar navegação completa por teclado
- Adicionar modo de alto contraste
- Incluir suporte para leitores de tela em todos os elementos interativos
- Testar com ferramentas como WAVE e Lighthouse

### 7. Recursos Interativos
- Galeria de fotos do ambiente
- Sistema de avaliações e comentários de clientes
- Mapa interativo mostrando a localização
- Integração com redes sociais para compartilhamento

## Autor

**Felipe Carvalho (<a href="https://github.com/flpzht">flpzht</a>)**

---

© 2026 Felipe Carvalho (flpzht) - Todos os direitos reservados
