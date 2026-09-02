# PROSE NES 2026/2 - Leva Sprint 0

Repositorio dos dashboards SPACE do NES preparados para a coleta da Sprint 0 de 2026/2.

Cada equipe fica isolada em `teams/tX`, compartilhando o mesmo motor em
`common/dashboard_app.py`. As planilhas brutas, respostas individuais, metricas
de auditoria e pacotes ZIP nao sao versionados.

## Estado desta leva

- T1 a T10: Sprint 0 carregada a partir do Survey Alunos.
- Dashboards separados por equipe, com notas agregadas do Survey e dimensoes SPACE.
- PDFs das devolutivas da Sprint 0 gerados para todas as equipes.
- Dados sem respostas futuras devem ser exibidos como `n/d`.

## Deploy no Streamlit Cloud

Use este repositorio e a branch `main`. Cada dashboard possui um arquivo de entrada:

```text
teams/t1/app.py
teams/t2/app.py
...
teams/t10/app.py
```

## Execucao local

```bash
python -m pip install -r requirements.txt
python -m streamlit run teams/t1/app.py
```

## Dados publicados

Somente artefatos agregados necessarios ao dashboard sao versionados, como os
relatos Markdown e os PDFs de devolutiva. Respostas individuais, planilhas de
Forms, auditorias de classificacao e ZIPs permanecem fora do repositorio.

## Relatorios PDF

- [T1 - Sprint 0](pdfs/relatorio_T1_sprint_0.pdf)
- [T2 - Sprint 0](pdfs/relatorio_T2_sprint_0.pdf)
- [T3 - Sprint 0](pdfs/relatorio_T3_sprint_0.pdf)
- [T4 - Sprint 0](pdfs/relatorio_T4_sprint_0.pdf)
- [T5 - Sprint 0](pdfs/relatorio_T5_sprint_0.pdf)
- [T6 - Sprint 0](pdfs/relatorio_T6_sprint_0.pdf)
- [T7 - Sprint 0](pdfs/relatorio_T7_sprint_0.pdf)
- [T8 - Sprint 0](pdfs/relatorio_T8_sprint_0.pdf)
- [T9 - Sprint 0](pdfs/relatorio_T9_sprint_0.pdf)
- [T10 - Sprint 0](pdfs/relatorio_T10_sprint_0.pdf)
