# PROMPT — Design e Criação da Página HTML: Kit Consultório Lúdico

## SUA TAREFA

Crie a página de vendas HTML completa do "Kit Consultório Lúdico", um produto digital para psicólogas infantis. Use o prompt de copy que já está neste projeto (prompt-copy-kit-consultorio-ludico.md) para entender o produto, a persona e preencher todos os textos. Sua responsabilidade aqui é o DESIGN, LAYOUT e CÓDIGO. A copy você puxa do outro arquivo.

---

## PÁGINA DE REFERÊNCIA (copiar o estilo visual)

A referência de design é: https://odontopediatria.fioseformas.com.br/

Estude essa página e replique o MESMO padrão visual, adaptando para o universo de psicologia infantil. Especificamente:

### FONTES
- **Use Google Fonts Poppins** em toda a página (a mesma da referência)
- Poppins 400, 500, 600, 700, 800, 900
- NÃO use Inter, Roboto, DM Sans, Nunito, Space Grotesk ou qualquer outra fonte genérica de IA

### ESTRUTURA VISUAL DA REFERÊNCIA (replicar)
- Faixa vermelha de urgência no topo (sticky)
- Hero com fundo branco, tag pequena acima da headline, headline grande, mockup centralizado, bullets com ícones, CTA grande com sombra, preço abaixo, selos de confiança
- Carrossel de imagens com scroll infinito automático (duplica os slides)
- Seções alternando fundo branco e fundo cinza claro
- Cards de benefícios em grid com ícone + título
- Bloco de urgência com fundo colorido (gradiente)
- Stack de valor com mockup à esquerda e lista de bullets à direita
- Cards de bônus em grid com imagem, título, descrição, preço riscado + GRÁTIS
- Dois planos lado a lado, o completo com destaque visual (borda, badge "MAIS VENDIDO", escala maior)
- Garantia com selo circular + texto ao lado
- FAQ com accordion funcional (JS)
- CTA final com fundo colorido
- Footer simples

---

## PALETA DE CORES (adaptar para psicologia infantil)

NÃO use roxo (#6C5CE7), gradiente roxo, azul elétrico ou qualquer combinação "padrão IA".

Use uma paleta que comunique **acolhimento, cuidado, confiança e ambiente terapêutico infantil**. Sugestão:

- **Primária:** Verde-azulado suave tipo teal (#2A9D8F ou similar). Remete a equilíbrio, saúde, calma. É a cor mais usada em ambientes terapêuticos e consultórios de psicologia.
- **Primária escura:** versão mais escura do teal para hover/contraste
- **Acento quente:** Pêssego/salmão suave (#F4A261 ou similar). Traz calor humano, acolhimento, trabalho com crianças.
- **Vermelho de urgência:** Para a faixa de topo e tags de escassez (#E63946 ou similar)
- **Fundo principal:** Off-white levemente quente (#FAF9F6 ou #FAFAF8). NÃO branco puro.
- **Fundo alternativo:** Creme/bege muito claro (#F5F0EB ou similar) para seções alternadas.
- **Texto escuro:** Cinza muito escuro (#2B2D42 ou similar), nunca preto puro
- **Texto corpo:** (#4A4A5A)
- **Texto leve:** (#7F8C9B)

A paleta deve ter cara de "consultório de psicóloga infantil": acolhedor, profissional sem ser clínico, leve sem ser infantilóide.

---

## ÍCONES

**NÃO use emojis.** Use a biblioteca Lucide Icons (https://unpkg.com/lucide@latest) ou Phosphor Icons (https://unpkg.com/@phosphor-icons/web@2.0.3) carregada via CDN.

Os ícones devem ser SVG inline ou via classe da biblioteca. Estilo: outline, stroke suave, peso regular. Cor seguindo a paleta.

Exemplos de ícones que fazem sentido pro contexto:
- Impressora (imprimir e usar)
- Relógio (economizar tempo)
- Coração (acolhimento)
- Estrela (diferencial)
- Escudo/check (segurança, confiança)
- Cérebro (desenvolvimento infantil)
- Puzzle/quebra-cabeça (recursos lúdicos)
- Usuários/família (pais, crianças)
- Pasta/arquivo (materiais organizados)
- Download (acesso digital)
- Award/troféu (competência profissional)

---

## SEÇÕES DA PÁGINA (12 seções, nessa ordem exata)

### 1. FAIXA DE URGÊNCIA (topo sticky)
- Fundo vermelho (#E63946), texto branco
- Fonte Poppins 700, 13-14px
- Uma linha só

### 2. HERO
- Fundo branco
- Tag pequena (pill) com fundo claro e texto teal
- Headline: Poppins 800-900, clamp(26px, 5vw, 40px), parte em cor escura + parte em teal
- Sub-headline: Poppins 400-500, 16-17px
- Placeholder de mockup (div com borda dashed teal, fundo creme, texto "MOCKUP DO PRODUTO")
- 5 micro-bullets com ÍCONE (não emoji) + texto curto, layout flex horizontal (wrap no mobile)
- Frase emocional de reforço
- CTA: botão grande, fundo teal, texto branco, border-radius 50px, sombra, hover com lift
- Preço abaixo do CTA
- 3 selos de confiança (ícone + texto pequeno)

### 3. PREVIEW DO MATERIAL
- Fundo alternativo (creme/bege)
- Headline + sub
- Carrossel CSS puro com scroll infinito (animation, duplicar slides)
- Slides: cards com fundo branco, borda sutil, border-radius, 220x280px
- Dentro de cada slide: placeholder "Imagem X" com borda dashed
- CTA

### 4. CATEGORIAS / SITUAÇÕES COBERTAS
- Fundo branco
- Headline + sub
- Grid 2 colunas (1 no mobile) com 12 itens
- Cada item: fundo creme, border-radius, ícone teal (bullet ou ícone Lucide) + texto
- CTA

### 5. BENEFÍCIOS (grid de 8 cards)
- Fundo alternativo
- Headline + sub
- Grid 4 colunas no desktop, 2 no tablet, 1 no mobile
- Cada card: fundo branco, sombra sutil, border-radius, ícone Lucide grande (32px) em teal + título Poppins 600
- CTA

### 6. BLOCO DE URGÊNCIA
- Fundo gradiente teal (primária → primária escura)
- Texto branco
- Headline com parte em amarelo/dourado (#FDCB6E)
- Texto de agitação
- CTA com fundo branco, texto teal
- 3 selos de confiança

### 7. STACK DE VALOR + BÔNUS
- Fundo branco
- Headline + tag "ACESSO IMEDIATO"
- Layout flex: mockup placeholder à esquerda (300x380px) + lista de bullets à direita com ícone check verde
- Transição para bônus: headline com destaque em teal
- Tag "5 BÔNUS EXCLUSIVOS" em pill com gradiente salmão/vermelho
- Grid 2 colunas (1 no mobile) com 5 cards de bônus
- Cada card: fundo creme quente, border sutil, placeholder de imagem (dashed salmão), título Poppins 800, descrição, preço riscado + "GRÁTIS" em verde
- CTA

### 8. PLANOS DE PREÇO
- Fundo alternativo
- Tag de urgência vermelha (pill)
- Headline
- Grid 2 colunas com 2 cards
- **Card básico:** fundo branco, borda cinza, sem destaque
- **Card completo (featured):** fundo branco, borda teal, sombra maior, scale(1.03), badge "MAIS VENDIDO" posicionado absolute no topo
- Dentro de cada card: nome, mockup placeholder, lista de items (check verde, bônus com ícone presente), preço de/por, parcelas, economia em verde, CTA full-width
- Prova social abaixo
- Selos de pagamento

### 9. GARANTIA
- Fundo branco
- Layout flex: selo circular à esquerda (140px, borda teal, fundo creme, texto "GARANTIA 15 DIAS") + texto à direita
- Headline + texto + frase de destaque

### 10. FAQ
- Fundo alternativo
- Headline + sub
- 8 perguntas em accordion
- Cada item: fundo branco, border-radius, sombra sutil
- Botão com texto à esquerda + "+" à direita (teal)
- Quando ativo: "+" rotaciona 45°, resposta aparece com transição max-height
- CTA pós-FAQ

### 11. CTA FINAL
- Fundo gradiente teal
- Headline branca
- CTA branco com texto teal

### 12. FOOTER
- Fundo escuro (#2B2D42)
- Texto cinza claro
- Copyright, disclaimers

---

## REGRAS TÉCNICAS

1. **Arquivo único HTML** com CSS inline (dentro de `<style>`) e JS inline (dentro de `<script>`)
2. **Mobile-first e responsivo.** Breakpoints em 768px e 480px
3. **Carregar via CDN:**
   - Google Fonts Poppins: `https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700;800;900&display=swap`
   - Lucide Icons: `https://unpkg.com/lucide@latest` (usar como `<i data-lucide="icon-name"></i>` e chamar `lucide.createIcons()` no script)
4. **Placeholders de imagem:** usar divs com borda dashed, fundo creme, texto descritivo centralizado. NÃO usar img src com links externos. Marque claramente onde as imagens reais devem ser inseridas.
5. **Links de checkout:** usar `href="#"` como placeholder. Marcar com comentário `<!-- LINK CHECKOUT -->` para fácil substituição.
6. **Accordion do FAQ:** JavaScript vanilla, sem biblioteca externa.
7. **Carrossel:** CSS animation puro (keyframes translateX), duplicar os slides pro loop infinito, pausar no hover.
8. **Transições:** hover nos CTAs (translateY -2px + sombra maior), transição suave nos FAQ items.
9. **NÃO use:** emojis nos ícones (use Lucide), gradientes roxos, fonte Inter/Roboto, border-radius exagerado (>16px), sombras muito pesadas.

---

## IDENTIDADE VISUAL DO PÚBLICO

O público são **psicólogas infantis** (mulheres, 24-35 anos, início de carreira). A linguagem visual deve comunicar:

- **Acolhimento profissional** — não pode parecer site médico frio, nem brinquedo infantil. É o meio-termo: profissional mas humano.
- **Confiança e segurança** — ela se sente insegura. A página precisa transmitir que esse material vai dar estrutura pra ela.
- **Praticidade** — visual limpo, organizado, sem poluição. Ela quer ver que o material é prático e pronto pra usar.
- **Universo infantil sutil** — referências visuais ao lúdico e ao infantil através das cores quentes, formas arredondadas, ícones de puzzle/cérebro/coração. Mas sem ser "fofo demais". É profissional.

---

## O QUE NÃO FAZER (evitar a todo custo)

- ❌ Gradientes roxos ou azul-roxo (padrão IA)
- ❌ Fonte Inter, Roboto, DM Sans, Nunito ou qualquer sans-serif genérica
- ❌ Emojis como ícones
- ❌ Fundo branco puro (#FFFFFF) como fundo principal da página
- ❌ Cards com sombra box-shadow muito pesada
- ❌ Layout que parece template Elementor/WordPress genérico
- ❌ Cores saturadas demais ou neon
- ❌ Excesso de border-radius (não passar de 16px nos cards, 50px só nos botões/pills)
