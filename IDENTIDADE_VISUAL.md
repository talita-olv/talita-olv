# Identidade visual · Talita Souza

**Aplicação:** portfólio pessoal e demonstrações independentes de engenharia, manutenção, automação e dados. Documento de referência para próximas versões e novos projetos. A proposta visual baseia-se no Reliability Lab, mas cada produto mantém nome, função e regras próprias.

## Identidade da família

- **Assinatura:** Talita Souza · Engenharia | Dados | Automação.
- **Tom:** técnico, objetivo, limpo e legível; não substituir informação operacional por ornamentos.
- **Elementos:** monograma TS geométrico/hexagonal, barras de indicadores, linhas de conexão, ícones técnicos simples.
- **Fonte:** Inter quando já disponível; fallback sem dependência externa: `ui-sans-serif, system-ui, -apple-system, 'Segoe UI', sans-serif`.
- **Estilo:** superfícies com pequenos cantos, contornos sutis, números tabulares e destaques contidos.

## Paleta principal

| Nome | HEX | Uso |
| --- | --- | --- |
| Fundo profundo | `#08111C` | Fundo de sistemas escuros |
| Azul petróleo | `#081B2E` | Marca, navegação e heros |
| Azul estrutural | `#0B2D4F` | Gradientes e superfícies de apoio |
| Painel | `#0E1D2D` | Cards, tabelas e controles |
| Turquesa | `#4AD7BE` | CTAs, indicadores e foco |
| Azul técnico | `#79AEFA` | Acento secundário e dados |
| Texto principal | `#EDF5F9` | Títulos e conteúdo em fundos escuros |
| Texto auxiliar | `#A0B7C8` | Legendas com contraste suficiente |
| Bordas | `#294557` | Estrutura de cards e divisões |

Vermelho/âmbar/verde de status **não** devem ser substituídos pelo turquesa quando possuírem significado operacional. Reforçar o sentido com texto, ícones e avisos — nunca comunicar criticidade apenas por cor.

## Arquivos oficiais

- Marca-mãe: [SVG completo](assets/talita-brand.svg).
- Exemplo de capas: [SmartRoute](https://github.com/talita-olv/smart-route/blob/main/assets/project-banner.svg), [Reliability Lab](https://github.com/talita-olv/reliability-lab/blob/main/assets/project-banner.svg), [Mapa 52 Semanas](https://github.com/talita-olv/mapa-52-semanas/blob/main/assets/project-banner.svg).
- Símbolo/favicon para novos projetos: `assets/talita-mark.svg` nos repositórios públicos citados acima.

Os arquivos SVG devem preservar a geometria e a paleta comum; cada projeto tem título/descrição e elementos auxiliares próprios. Evitar alterar proporção ou substituir por imagens genéricas. Colocar autoria no rodapé e README, sem confundir portfólio com vínculo institucional.

## Regra de manutenção

1. Abrir Issue para cada atualização visual relevante, com escopo e riscos.
2. Alterar em branch própria e PR; não afetar lógica de cálculo, importação e exportação.
3. Verificar responsividade (desktop, 390px, 320px), contraste, foco, leitores de tela, tabelas e mapas.
4. Não publicar dados empresariais nem aplicar marca pessoal em sistemas corporativos sem autorização da organização.
5. Validar CI e publicar após merge; guardar evidência do status real. A alteração visual não garante validação funcional completa.
6. Respeitar a **licença própria de cada projeto**; identidade gráfica compartilhada não muda direitos de uso de código nem de recursos de terceiros.

## Produtos na família

- **Reliability Lab** — confiabilidade, FMEA e criticidade.
- **SmartRoute** — roteirização de atendimentos por prazo, criticidade e geografia.
- **Mapa 52 Semanas** — estratégias, ciclos, calendário e planejamento.
- **FIELD Analytics** — sistema operacional privado; propostas de branding somente mediante revisão/aprovação, sem revelar dados e sem alterar o painel legado inadvertidamente.

**© 2026 Talita Souza — autoria e padrão visual do portfólio.**
