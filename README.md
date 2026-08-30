# Dataset Titanic - Data Science 01
# Titanic - Previsão de Sobrevivência

Projeto de classificação binária usando o dataset clássico do Kaggle (Titanic - Machine Learning from Disaster).

## Pipeline
- EDA: análise de padrões de sobrevivência por Sex, Pclass, Age e Fare
- Split treino/validação com train_test_split

## Modelos testados
| Modelo | Acurácia (validação) |
|---|---|
| Regressão Logística | 79.4% |
| Random Forest (n_estimators=5, max_depth=5) | 80.5% |
| Random Forest (n_estimators=100, max_depth=5) | 78% |

## Aprendizados
- Random Forest com poucos parâmetros ajustados não superou de forma consistente a Regressão Logística

## Próximos passos
- Cross-validation para comparação mais robusta entre modelos
