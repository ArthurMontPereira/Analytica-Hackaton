# Análise de superlotação de ônibus na cidade do Rio de Janeiro

Projeto realizado para o processo seletivo da equipe Analytica no primeiro semestre de 2026.

## Organização do projeto

Na pasta [materiais/](materiais/) encontram-se os materiais já providos pela equipe da Analytica, para consulta.

Na pasta do Google Drive [dados-analytica-hackathon/](https://drive.google.com/drive/folders/1h9cDrlc3Y-eUHJsikezlWNYYBTkDD9Um?usp=sharing), encontram-se todos os datasets usados no projeto. O notebook *eda.ipynb* fará o download dela automaticamente quando for executado. Segue abaixo uma breve descrição dos conteúdos dessa pasta e suas respectivas fontes:

- limite_de_bairros_rj.csv: limites de cada bairro da cidade do Rio de Janeiro, retirado do data.rio;
- ids_por_bairro_rj.csv: Índice de Desenvolvimento Social de cada bairro da cidade do Rio de Janeiro, retirado do data.rio;
- lotacao_onibus_formatado_final.csv: a preencher;
- dashboard_subsidio_sppo: pasta com tabelas consolidadas utilizadas para acompanhamento financeiro, fonte: SMTR;
- gtfs: pasta com base padronizada de transporte contendo linhas, paradas, viagens, geometria das rotas e operação temporal, fonte: SMTR;

## Rodando o projeto

Siga os passos abaixo para configurar o ambiente local e reproduzir a análise de dados.

### Pré-requisitos
![Python Version](https://img.shields.io/badge/python-3.12%2B-blue)

### Configuração do Ambiente
Crie uma cópia local desse repositório:
```bash
git clone https://github.com/joaordc/analytica-hackathon
```
Crie o ambiente virtual:
```bash
python3 -m venv venv
```
Ative o ambiente:
```bash
# Linux/macOS:
source venv/bin/activate
# Windows:
venv\Scripts\activate
```
Instale todas as dependências presentes em *requirements.txt*:
```bash
pip install -r requirements.txt
```

### Uso
Rode o Jupyter Notebook na sua máquina: 
```bash
jupyter notebook
```
Siga as instruções e realize a EDA presente em *notebooks/eda.ipynb*.