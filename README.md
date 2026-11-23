# Artefato de Apoio à Decisão Regulatória e Assistencial para o TEA na Saúde Suplementar

Repositório dos scripts computacionais desenvolvidos na dissertação de Mestrado Profissional em Desenvolvimento de Tecnologia (**Instituto de Tecnologia para o Desenvolvimento – LACTEC**).

- **Autora:** Renata de Souza Vitorino
- **Orientador:** Prof. Dr. Eduardo Kazumi Yamakawa
- **Coorientador:** Prof. Dr. Marcelo Rosano Dallagassa
- **Ano:** 2026

## Estrutura dos Notebooks (Ambiente Databricks / Python)

1. **`01_analise_rede_ans_rmc.ipynb`**  
   Ingestão, higienização e cruzamento de dados abertos da ANS (Operadoras e Prestadores Não Hospitalares) com registros de CNPJ (BrasilAPI) em PySpark, mapeamento por UF e recorte territorial para os 29 municípios da Região Metropolitana de Curitiba (RMC).
2. **`02_priorizacao_ahp_monte_carlo.ipynb`**  
   Modelagem multicritério via *Analytic Hierarchy Process* (AHP) com agregação por média geométrica (AIJ), cálculo da Razão de Consistência (CR) e Simulação Estocástica de Monte Carlo (10.000 iterações).
3. **`03_avaliacao_prototipo_sus_tlx_pln.ipynb`**  
   Avaliação empírica do protótipo junto a potenciais usuários: *System Usability Scale* (SUS), confiabilidade interna ($\alpha$ de Cronbach), análise fatorial (Lewis & Sauro), *Raw NASA-TLX*, correlação convergente (Spearman), análise lexical por N-gramas e *Treemap*.

## Nota de Integridade e Sigilo Ético
As bases de dados públicos da ANS e IBGE utilizadas no Notebook 01 são de acesso aberto. Em conformidade com o Termo de Consentimento Livre e Esclarecido (TCLE), os arquivos brutos contendo respostas individuais dos participantes (Notebooks 02 e 03) não são disponibilizados neste repositório.
