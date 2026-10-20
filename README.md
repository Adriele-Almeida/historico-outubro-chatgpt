# Histórico de Outubro | ChatGPT

Aplicativo estático e responsivo para explorar, do macro ao micro, a distribuição cronológica de horários de interação de **01/10/2026 a 20/10/2026**.

## Recursos

- Visão geral com indicadores e gráfico de atividade diária.
- Calendário visual com intensidade de registros.
- Distribuição por período: madrugada, manhã, tarde e noite.
- Linha do tempo com duas visualizações: lista e mapa de calor por hora (24h).
- Detalhamento sob demanda ao selecionar cada dia, com horários no formato HH:MM:SS.
- Navegação entre dias e cópia de horários de um dia.
- Exportação do período completo em CSV, compatível com planilhas.
- Layout responsivo para celular e computador.

## Como executar

Abra o arquivo **index.html** no navegador. O projeto utiliza HTML, CSS e JavaScript puro, sem etapa de instalação nem servidor de dados.

Também é compatível com GitHub Pages: em **Settings > Pages**, configure **Deploy from a branch**, usando **main** e **/(root)** para publicar o site.

## Organização

| Arquivo | Conteúdo |
|---|---|
| index.html | Estrutura do painel e janela de detalhes |
| styles.css | Estilo e adaptação a diferentes telas |
| app.js | Gráficos, navegação, cópia e exportação |
| data.js | Datas, dias da semana e horários |

## Proveniência e limitações

- Fonte desta versão: horários previamente apresentados na conversa do ChatGPT.
- Há **433 horários listados** distribuídos em **19 dos 20 dias**.
- Horário de referência: **America/Sao_Paulo (UTC-3)**, conforme a visualização original.
- **Os metadados de origem não foram revalidados.** A base pode ter omissões ou imprecisões.
- A falta de registros recuperados para **12/10/2026** não prova ausência de interação nessa data.
- As distâncias entre horários não são estimativas de duração de trabalho ou tempo on-line.

## Atualização da base

Edite as linhas de **data.js**. Cada entrada contém dia, abreviação do dia da semana e horários separados por espaço. A interface calcula automaticamente todos os indicadores a partir desses dados.

