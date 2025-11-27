# ratos-twister-data

Repositório para organização, versionamento e análise de dados dos ratos twister.

## Estrutura sugerida

```bash
ratos-twister-data/
├─ data/
│  ├─ raw/
│  │  └─ planilha_ratinhos_2.0.xlsx
│  └─ processed/
├─ notebooks/
│  └─ analise_ratos.ipynb
├─ figs/
├─ docs/
├─ src/
│  └─ __init__.py
├─ .gitignore
└─ README.md
```

### Pastas

- `data/raw/`: dados originais digitados à mão (planilhas, CSVs).
- `data/processed/`: versões tratadas/limpas (se você decidir salvar saídas intermediárias).
- `notebooks/`: notebooks Jupyter de exploração e análises.
- `figs/`: gráficos gerados (PNG, SVG, etc.).
- `docs/`: relatórios, protocolos, textos complementares.
- `src/`: scripts Python reutilizáveis (funções de leitura, limpeza, gráficos, etc.).

## Fluxo de trabalho sugerido

1. Atualizar os dados em `data/raw/planilha_ratinhos_2.0.xlsx`.
2. Abrir `notebooks/analise_ratos.ipynb`.
3. Rodar as células de leitura, limpeza e visualização.
4. Salvar gráficos em `figs/` e, se quiser, relatórios em `docs/`.
