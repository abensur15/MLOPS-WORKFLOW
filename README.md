# LAB 0 — MLOps na Prática
Este laboratório demonstra de forma prática o ciclo de vida de um modelo de
Machine Learning utilizando conceitos de MLOps.

## Fluxo do laboratório
Dados
→ Treinamento
→ Avaliação
→ Tracking de Experimentos
→ Versionamento
→ Quality Gate
→ Model Registry
→ Monitoramento
→ Drift
→ Continuous Training

## Tecnologias utilizadas
- Python
- Scikit-learn
- MLflow
- Joblib
- Google Colab
- GitHub

## Objetivos

Durante o laboratório serão demonstrados:
- treinamento de um modelo de Machine Learning;
- avaliação automática do modelo;
- rastreamento de experimentos;
- versionamento do artefato;
- Quality Gate para promoção do modelo;
- Model Registry simplificado;
- monitoramento de performance;
- simulação de Data Drift;
- Continuous Training.

## Arquitetura
DATA
  ↓
TRAIN
  ↓
EVALUATE
  ↓
MLFLOW TRACKING
  ↓
QUALITY GATE
  ↓
MODEL REGISTRY
  ↓
MONITOR
  ↓
DRIFT
  ↓
RETRAIN

Laboratório desenvolvido exclusivamente para fins educacionais.
