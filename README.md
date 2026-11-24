<p align="center">
  <img src=".github/banner.svg" alt="Projeto Monitoria IP" width="100%" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square" alt="Matplotlib" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter" />
</p>

## Sobre o Projeto

Projeto desenvolvido para a monitoria de **Introdução à Programação (CIn - UFPE)**: realiza o *parsing* de arquivos de texto contendo anúncios reais de veículos (`Code/test1.txt` a `Code/test15.txt`), estrutura atributos como **marca, ano, cor, motor, quilometragem e câmbio**, e gera visualizações estatísticas com `pandas` e `matplotlib`.

## Gráficos Gerados

<p align="center">
  <img src="Graficos_em_PNG/Porcentagem_de_carros_por_marca.png" alt="Porcentagem de carros por marca" width="48%" />
  <img src="Graficos_em_PNG/Quantidade_de_carros_por_ano_de_fabricacao.png" alt="Quantidade de carros por ano" width="48%" />
</p>
<p align="center">
  <img src="Graficos_em_PNG/Quantidade_de_carros_em_relacao_ao_motor_e_tipo_de_cambio.png" alt="Motor e tipo de câmbio" width="48%" />
  <img src="Graficos_em_PNG/Quantidade_de_carros_por_cores.png" alt="Quantidade de carros por cores" width="48%" />
</p>

## Estrutura

```text
Projeto_monitoria_IP/
├── Code/
│   ├── Projeto_monitoriaIP.ipynb  # Notebook com parser e geração de gráficos
│   └── test1.txt ... test15.txt   # Amostras de anúncios de veículos
└── Graficos_em_PNG/               # Gráficos exportados em PNG
```

## Como Executar

```bash
git clone https://github.com/charles-gabriel-cc/Projeto_monitoria_IP.git
cd Projeto_monitoria_IP/Code
jupyter notebook Projeto_monitoriaIP.ipynb
```
