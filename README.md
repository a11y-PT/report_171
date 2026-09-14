---
website: "Site institucional da APEC"          # Entre as aspas escreve o nome do website
date: "20/07/2026"                    # Entre as aspas escreve a data de criação do 1º relatório. Os restantes estão no histórico
uri: "https://www.apec.org.pt/"   # Entre as aspas escreve o domínio do website
a11y_statement: "https://www.apec.org.pt/acessibilidade/" # Entre as aspas escreve o URL da Declaração de Acessibilidade do website
owner: "APEC - Associação Promotora do Ensino dos Cegos"         # Entre as aspas escrever o nome do owner do website
seal: "Ouro"                          # Entre as aspas escreve Bronze, Prata ou Ouro
validity: "14/09/2026 a 14/09/2027" # Entre as aspas escreve data de início e data de fim no formato 31/12/1999 a 31/12/2000
status: "Concluído" # Entre as aspas escreve uma das seguintes opções: "Auditoria a decorrer", "A aguardar correções da entidade", "Concluído" 
---

# Relatório de auditoria

Sítio Web: {{ page.website }}

- Data de criação: {{ page.date }}
- URL: {{ page.uri }}
- Propriedade: {{ page.owner }}
- Candidatura: {{ page.seal }}
- Validade do selo: {{ page.validity }}
- Estado: {{ page.status }}

## Relatório {{ page.website }}

<p>O presente relatório resultou da auditoria da informação publicada na <a href="{{ page.a11y_statement }}">Declaração de Acessibilidade e Usabilidade</a>.</p>

Consulte aqui a última atualização: [Relatório {{ page.website }}](report.html)

<details>
  <summary>Histórico de atualizações</summary>
  <ul aria-label="lista de relatórios já efetuados">
    <li><a href="14092026_report.html">(14/09/2026). Relatório {{ page.website }}</a></li>
    <li><a href="22072026_report.html">(22/07/2026). Relatório {{ page.website }}</a></li>
  </ul>
</details>

<hr>

<p><small>2025 - 2026, GitTemplateReports Web (v.1.0.4)</small></p>
