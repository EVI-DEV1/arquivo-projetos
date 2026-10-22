# Entre Luz — documentação do projeto

## Visão geral

**Entre Luz** é uma landing page narrativa sobre dor emocional, autocrítica, solidão, sobrevivência e reconstrução. O conteúdo é apresentado como expressão pessoal e material de inspiração — não como diagnóstico, fato universal ou incentivo a comportamentos de risco.

O percurso visual contrasta sombras, espelhos quebrados e frases fragmentadas com luz quente, uma porta aberta e elementos de esperança.

## Tecnologias

- React
- TypeScript
- Vite
- CSS responsivo sem dependências visuais adicionais

## Como executar

Na pasta do projeto, instale as dependências e inicie a prévia local:

```bash
npm install
npm run dev
```

Para validar a versão de produção:

```bash
npm run build
```

## Estrutura principal

```text
src/
  main.tsx       Interface, conteúdo e interações
  styles.css     Direção visual e responsividade
public/images/
  hero-reconstrucao.png  Imagem principal da abertura e dos fragmentos
  personagem.webp         Foto de referência original
```

## Experiência da página

1. **Abertura** — imagem cinematográfica e a ideia central: o que feriu não define a pessoa.
2. **Conselhos** — cinco cartões para momentos de crítica, solidão, urgência, comparação e culpa.
3. **Fragmentos** — espelhos interativos que destacam temas e revelam reflexões sem remover o fragmento da tela.
4. **Dor e realidade** — contraste entre pensamentos críticos e respostas mais cuidadosas.
5. **Reconstrução** — pequenas ações possíveis, porta aberta, luz e crescimento.
6. **Encerramento** — mensagem de esperança e continuidade.

## Responsividade e acessibilidade

- Layout adaptado para celulares estreitos, celulares grandes, tablets, notebooks e telas amplas.
- Sem rolagem horizontal nos tamanhos testados.
- Botões e espelhos podem ser usados com teclado e toque.
- Preferência de movimento reduzido é respeitada.
- Há link para pular diretamente ao conteúdo.
- O aviso de apoio inclui o CVV (188) de forma discreta e sem sair do card.

## Imagens e conteúdo sensível

As imagens e o texto foram usados com direcionamento respeitoso, evitando exibir novamente insultos diretos ou conteúdos que incentivem automutilação ou suicídio. A imagem principal permanece como metáfora de dor, escuta e recomeço.

## Repositório

O código está publicado em:

https://github.com/EVI-DEV1/entre-luz

## Publicação na Vercel

1. Entre na Vercel com a conta conectada ao GitHub.
2. Importe o repositório `EVI-DEV1/entre-luz`.
3. Mantenha o framework detectado como **Vite**.
4. Clique em **Deploy**.
5. A Vercel fornecerá uma URL pública no formato `entre-luz.vercel.app`.

Depois da primeira publicação, cada envio para a branch `main` do GitHub cria uma nova publicação automaticamente.
