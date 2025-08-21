# AdvertoLinks - Landing Page

## Descrição
Landing page profissional para o SaaS AdvertoLinks, desenvolvida com HTML e CSS puros. A página apresenta automações de WhatsApp e Instagram com design moderno, animações sutis e cores vivas mas equilibradas.

## Arquivos Inclusos

### Arquivos Principais
- `advertolinks.html` - Arquivo HTML principal da landing page
- `styles.css` - Arquivo CSS com todos os estilos e animações

### Documentação
- `README.md` - Este arquivo com instruções
- `advertolinks_relatorio_final.md` - Relatório completo do projeto
- `advertolinks_concept.md` - Conceito e estrutura da landing page
- `advertolinks_content.md` - Conteúdo detalhado de todas as seções

## Como Usar

### Opção 1: Visualização Local
1. Baixe e extraia todos os arquivos
2. Abra o arquivo `advertolinks.html` diretamente no seu navegador
3. A página funcionará completamente offline

### Opção 2: Servidor Local (Recomendado)
Para melhor performance e teste de funcionalidades:

1. Coloque os arquivos em um servidor web local
2. Acesse através de `http://localhost/advertolinks.html`

### Opção 3: Hospedagem Web
1. Faça upload dos arquivos `advertolinks.html` e `styles.css` para seu servidor
2. Acesse através do domínio configurado

## Características Técnicas

### Design
- **Responsivo**: Funciona em desktop, tablet e mobile
- **Cores**: Paleta com índigo (#6366f1), verde esmeralda (#10b981) e âmbar (#f59e0b)
- **Tipografia**: Inter (Google Fonts)
- **Ícones**: Font Awesome 6.4.0

### Animações
- Fade in on scroll para elementos
- Hover effects em botões e cards
- Gradientes animados no texto principal
- Transições suaves entre estados
- Menu mobile com animação

### Seções Incluídas
1. **Header** - Navegação fixa com menu responsivo
2. **Hero** - Seção principal com CTA destacado
3. **Benefícios** - 3 principais vantagens do produto
4. **Recursos** - 6 funcionalidades detalhadas
5. **Demo** - Estatísticas e call-to-action
6. **Depoimentos** - 3 testemunhos de clientes
7. **Preços** - 3 planos de assinatura
8. **CTA Final** - Formulário de captura de leads
9. **Footer** - Links organizados e informações de contato

### Funcionalidades JavaScript
- Menu mobile toggle
- Navegação suave entre seções
- Animações on scroll (Intersection Observer)
- Efeito de scroll no header

## Personalização

### Cores
As cores podem ser facilmente alteradas modificando as variáveis CSS no início do arquivo `styles.css`:

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #10b981;
    --accent-color: #f59e0b;
    /* ... outras variáveis */
}
```

### Conteúdo
Todo o conteúdo pode ser editado diretamente no arquivo HTML, incluindo:
- Textos e títulos
- Preços e planos
- Depoimentos
- Informações de contato

### Imagens
Para adicionar imagens:
1. Coloque as imagens na mesma pasta dos arquivos
2. Substitua os ícones Font Awesome por tags `<img>`
3. Ajuste os estilos CSS conforme necessário

## Compatibilidade

### Navegadores Suportados
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### Dispositivos
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (320px - 767px)

## Performance

### Otimizações Incluídas
- CSS minificado em produção
- Fontes carregadas de forma otimizada
- Animações com `will-change` para melhor performance
- Lazy loading de elementos fora da viewport

### Métricas Esperadas
- First Contentful Paint: < 1.5s
- Largest Contentful Paint: < 2.5s
- Cumulative Layout Shift: < 0.1

## Suporte

Para dúvidas ou customizações adicionais, consulte:
- `advertolinks_relatorio_final.md` - Relatório técnico completo
- `advertolinks_concept.md` - Conceitos de design utilizados

## Licença

Este projeto foi desenvolvido especificamente para AdvertoLinks. Todos os direitos reservados.

