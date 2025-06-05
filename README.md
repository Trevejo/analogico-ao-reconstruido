# 📡 Projeto: Analógico ao Reconstruído

## 🎯 Visão Geral

Este projeto demonstra de forma prática e educativa o processo completo de **conversão analógico-digital-analógico** em sistemas de comunicação digital. Através de uma série de notebooks Jupyter interativos, exploramos cada etapa do processamento de sinais, desde a geração de formas de onda até a reconstrução final do sinal analógico.

### 🔬 Objetivo Educacional

O projeto foi desenvolvido para ilustrar conceitos fundamentais de:
- **Processamento Digital de Sinais (DSP)**
- **Teoria da Comunicação Digital**
- **Análise de Fourier**
- **Conversores A/D e D/A**
- **Filtragem Digital**
- **Análise Espectral**

## 📋 Estrutura do Projeto

### 🗂️ Arquivos Principais

```
analogico-ao-reconstruido/
│
├── 📓 etapa2_geracao_sinais.ipynb           # Geração de sinais periódicos
├── 📓 etapa3_serie_fourier.ipynb            # Análise de Fourier
├── 📓 etapa4_modulo_fase.ipynb              # Espectros pré-processamento
├── 📓 etapa5_digitalizacao.ipynb            # Amostragem e quantização
├── 📓 etapa6_processamento_digital.ipynb    # Ruído e distorções
├── 📓 etapa7_filtragem_digital.ipynb        # Filtros digitais
├── 📓 etapa8_modulo_fase_pos_processamento.ipynb # Espectros pós-processamento
├── 📓 etapa9_reconstrucao_analogica.ipynb   # Conversão D/A
├── 📋 requirements.txt                       # Dependências
└── 📖 README.md                             # Esta documentação
```

## 🚀 Início Rápido

### 📦 Instalação

1. **Clone o repositório:**
   ```bash
   git clone <url-do-repositorio>
   cd analogico-ao-reconstruido
   ```


2. **Instale as dependências:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Inicie o Jupyter:**
   ```bash
   jupyter lab
   # ou
   jupyter notebook
   ```

## 🔧 Requisitos

### 📊 Dependências

| Biblioteca | Versão | Função |
|------------|--------|---------|
| `numpy` | ≥1.20.0 | Computação numérica |
| `scipy` | ≥1.7.0 | Processamento de sinais |
| `matplotlib` | ≥3.3.0 | Visualização |
| `notebook` | ≥6.0.0 | Interface Jupyter |
| `jupyterlab` | ≥3.0.0 | Interface moderna |

## 📈 Resultados Esperados

### 🎯 Aprendizados Principais

1. **Digitalização:** Compreensão dos efeitos de amostragem e quantização
2. **Processamento:** Impacto de ruído e distorções não-lineares
3. **Filtragem:** Trade-offs entre redução de ruído e preservação de características
4. **Reconstrução:** Diferentes métodos DAC e suas implicações na fidelidade
5. **Análise Espectral:** Evolução do conteúdo em frequência ao longo da cadeia

### 📊 Métricas de Qualidade

- **SNR:** Variação de ~20dB (original) para ~8dB (processado) para ~15dB (filtrado)
- **Fidelidade:** Preservação da frequência fundamental (1 Hz) e 3ª harmônica (3 Hz)
- **Distorção:** Suavização das transições, perda de harmônicas superiores
- **Correlação:** ~0.85-0.95 entre original e reconstruído (dependendo do método DAC)

## 🔬 Conceitos Técnicos Abordados

### 📡 Processamento de Sinais
- Teorema de Nyquist-Shannon
- Fenômeno de Gibbs
- Windowing e vazamento espectral
- Filtros IIR (Butterworth)
- Interpolação e decimação

### 🎛️ Sistemas de Comunicação
- Conversores A/D e D/A
- Canal AWGN
- Distorções não-lineares
- Limitação de largura de banda
- Métricas de qualidade (SNR, BER conceitual)

### 🧮 Análise Matemática
- Transformada de Fourier Discreta (DFT/FFT)
- Série de Fourier
- Convolução digital
- Estatística de sinais (RMS, correlação)
- Análise de erro (MSE, MAE)

## 📄 Licença

Este projeto está licenciado sob a **MIT License** - veja o arquivo [LICENSE](LICENSE) para detalhes.

## 🎖️ Reconhecimentos

### 📚 Referências Acadêmicas
- Oppenheim, A. V. & Schafer, R. W. - "Discrete-Time Signal Processing"
- Proakis, J. G. & Manolakis, D. G. - "Digital Signal Processing"
- Haykin, S. - "Communication Systems"

### 🛠️ Ferramentas Utilizadas
- **Python:** Linguagem de programação
- **Jupyter:** Ambiente interativo
- **NumPy/SciPy:** Computação científica
- **Matplotlib:** Visualização de dados

---

## 📊 Status do Projeto

![Status](https://img.shields.io/badge/Status-Completo-brightgreen)
![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Notebooks](https://img.shields.io/badge/Notebooks-8-orange)