# Acessibilidade na Web: Tropicália 🌺🎶

Site temático sobre a Tropicália usado como exercício para aplicar fundamentos de acessibilidade digital com HTML, CSS e JavaScript (Bootstrap e ScrollReveal inclusos).

## Objetivos pedagógicos 🎯
- ✅ Construir páginas com semântica correta, textos alternativos e navegação por teclado.
- 💬 Entender o impacto da acessibilidade em pessoas usuárias reais e como comunicar decisões inclusivas.
- 🔍 Praticar revisão contínua com ferramentas e testes manuais (ex.: contraste, foco, leitores de tela).

## Habilidades desenvolvidas 🚀
- **Técnicas**: estrutura semântica, uso de `aria-*`, gerenciamento de foco em modais/menus, contraste de cores, responsividade acessível, organização de CSS e componentes em Bootstrap, microanimações não invasivas com ScrollReveal, auditoria rápida com Lighthouse/axe.
- **Soft skills**: empatia e diálogo com usuários, escrita clara de rótulos e mensagens, colaboração em revisões de código, disciplina em testes manuais, documentação que orienta outras pessoas.

## Caminho sugerido (aulas em passos) 📚
1) **Mapa inicial**: ler o código, identificar pontos críticos de acessibilidade (foco, contraste, leitura por leitor de tela) e registrar hipóteses de melhoria.
2) **Semântica e textos**: ajustar títulos em hierarquia, listas, landmarks (`header`, `nav`, `main`, `footer`) e adicionar `alt` e rótulos descritivos em imagens e controles.
3) **Teclado primeiro**: garantir ordem lógica de `tab`, estados de foco visíveis e comportamento de menus/modais com Enter/Espaço/Escape.
4) **ARIA com propósito**: aplicar `aria-label`, `aria-expanded`, `role` só quando necessário, evitando sobreposição com semântica nativa; validar com leitor de tela.
5) **Visual inclusivo**: revisar contraste de cores, tamanhos de fonte e espaçamento; assegurar que animações de ScrollReveal respeitem preferências de movimento reduzido.
6) **Teste e feedback**: rodar auditorias (Lighthouse/axe), revisar com checklist, pedir feedback a colegas e atualizar documentação.

## Como executar 🧭
- 🌐 Abrir `index.html` em um navegador; garantir que imagens em `img/` estejam no mesmo diretório do projeto.
- 🎛️ Para revisar animações, desativar preferências de movimento reduzido no sistema e depois testar novamente com a preferência ativada.

## Possíveis melhorias 🌟
- 🤖 Incluir testes automatizados de acessibilidade (axe-core/Playwright) no fluxo de CI.
- ⌨️ Adicionar atalho de teclado para abrir o menu de acessibilidade.
- 🎧 Incluir legenda/transcrição em mídias relacionadas à Tropicália (áudio/vídeo).
- 🎨 Criar tema de alto contraste e opção de aumentar espaçamento de texto.
- ✅ Publicar um checklist rápido de QA de acessibilidade no repositório.
