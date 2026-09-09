# LAB0 — Pipeline MLOps na Prática: Treinamento, Governança e Monitoramento

Este laboratório demonstra, de forma prática e simplificada, como um modelo de Machine Learning evolui para um fluxo MLOps.

## Objetivo

Demonstrar o ciclo de vida MLOps desde o treinamento do modelo até sua rastreabilidade, versionamento, validação, promoção, monitoramento e retreinamento.

## Fluxo do laboratório

Dados
→ Treinamento
→ Avaliação
→ MLflow Tracking
→ Versionamento
→ Quality Gate
→ Model Registry
→ Governança
→ Monitoramento
→ Mudança nos dados / Drift
→ Degradação de Performance
→ Continuous Training

## Tecnologias utilizadas

- Python
- Scikit-learn
- Random Forest
- MLflow
- Joblib
- Google Colab
- GitHub

## Conceitos demonstrados

- criação, treinamento e avaliação de um modelo de Machine Learning;
- rastreamento de experimentos com MLflow;
- versionamento do artefato do modelo;
- geração de evidência de integridade com SHA-256;
- implementação de Quality Gate;
- promoção controlada para um Model Registry simplificado;
- criação de metadados para rastreabilidade e governança;
- definição de baseline de performance;
- simulação de mudança nos dados de produção;
- identificação de degradação de performance;
- simulação de acionamento de Continuous Training.

## Modelo utilizado

Neste laboratório utilizamos um modelo de Machine Learning baseado em Random Forest para classificação.

O Random Forest faz parte do campo de Inteligência Artificial, especificamente de Machine Learning supervisionado.

Fluxo conceitual:

Inteligência Artificial
→ Machine Learning
→ Aprendizado Supervisionado
→ Classificação
→ Random Forest

## Arquitetura do LAB

DATA
  ↓
TRAIN
  ↓
EVALUATE
  ↓
MLFLOW TRACKING
  ↓
VERSIONING
  ↓
QUALITY GATE
  ↓
MODEL REGISTRY
  ↓
GOVERNANCE
  ↓
MONITORING
  ↓
DRIFT / PERFORMANCE DEGRADATION
  ↓
CONTINUOUS TRAINING

## Resultado esperado

Ao final do laboratório, o participante deverá compreender que Machine Learning cria o modelo, enquanto MLOps permite rastrear, versionar, validar, promover, monitorar e governar esse modelo ao longo de seu ciclo de vida.

Laboratório desenvolvido exclusivamente para fins educacionais.
