# Mapa de Configuração do Projeto

## Projeto

**Nome:** ml-news-classification  
**Descrição:** Projeto em andamento para classificação de notícias utilizando Machine Learning e práticas de MLOps.  

## 1. Política de Versionamento
**Estratégia de versionamento:** Versionamento Semântico.

Onde:

* **MAJOR:** mudanças incompatíveis com versões anteriores.
* **MINOR:** novas funcionalidades compatíveis com versões anteriores.
* **PATCH:** correções de bugs, ajustes pequenos e melhorias internas.

## 2. Itens de Configuração do Projeto

| ID     | Item de Configuração                   | Tipo                 | Descrição                                                                        | Versionamento            |
| ------ | -------------------------------------- | -------------------- | -------------------------------------------------------------------------------- | ------------------------ |
| IC-001 | Código-fonte                           | Código               | Scripts Python responsáveis por análise, treino, avaliação e execução do projeto | SemVer                   |
| IC-002 | Dataset                                | Dados                | Base de notícias contendo textos, categorias e metadados                         | Controle por data/versão |
| IC-003 | Notebooks                              | Documentação técnica | Notebooks usados para exploração, testes e experimentos                          | SemVer                   |
| IC-004 | Modelos treinados                      | Artefato ML          | Modelos gerados durante os experimentos de classificação                         | SemVer                   |
| IC-005 | Métricas de avaliação                  | Artefato ML          | Resultados de acurácia, precision, recall, F1-score e matriz de confusão         | SemVer                   |
| IC-006 | Arquivo `.env.example`                 | Configuração         | Modelo de variáveis de ambiente necessárias para execução do projeto             | SemVer                   |
| IC-007 | `requirements.txt` ou `pyproject.toml` | Dependências         | Lista de bibliotecas utilizadas no projeto                                       | SemVer                   |
| IC-008 | README.md                              | Documentação         | Documentação principal do projeto                                                | SemVer                   |
| IC-009 | Scripts de pré-processamento           | Código               | Scripts para limpeza, tratamento de nulos e remoção de duplicados                | SemVer                   |
| IC-010 | Scripts de treino                      | Código               | Scripts responsáveis pelo treinamento do modelo                                  | SemVer                   |
| IC-011 | Scripts de avaliação                   | Código               | Scripts responsáveis pela validação do desempenho do modelo                      | SemVer                   |
| IC-012 | Pipeline de MLOps                      | Pipeline             | Fluxo de execução, automação, tracking e versionamento dos experimentos          | SemVer                   |
| IC-013 | Dockerfile                             | Infraestrutura       | Arquivo para criação do ambiente containerizado                                  | SemVer                   |
| IC-014 | docker-compose.yml                     | Infraestrutura       | Orquestração dos serviços do projeto                                             | SemVer                   |
| IC-015 | GitHub Actions                         | CI/CD                | Workflows de integração contínua e validação automática                          | SemVer                   |

---

## 3. Bibliotecas e Frameworks

| ID      | Biblioteca/Framework | Finalidade                              | Política de Versão                      |
| ------- | -------------------- | --------------------------------------- | --------------------------------------- |
| LIB-001 | Python               | Linguagem principal do projeto          | Fixar versão mínima                     |
| LIB-002 | Pandas               | Manipulação e análise de dados          | Fixar versão no arquivo de dependências |
| LIB-003 | NumPy                | Operações numéricas                     | Fixar versão no arquivo de dependências |
| LIB-004 | Scikit-learn         | Treinamento e avaliação dos modelos     | Fixar versão no arquivo de dependências |
| LIB-005 | Matplotlib           | Visualização de dados                   | Fixar versão no arquivo de dependências |
| LIB-006 | Seaborn              | Visualização estatística                | Fixar versão no arquivo de dependências |
| LIB-007 | MLflow               | Rastreamento de experimentos e modelos  | Fixar versão no arquivo de dependências |
| LIB-008 | FastAPI              | Criação de API para servir o modelo     | Fixar versão no arquivo de dependências |
| LIB-009 | Streamlit            | Interface simples para testes do modelo | Fixar versão no arquivo de dependências |
| LIB-010 | Pytest               | Testes automatizados                    | Fixar versão no arquivo de dependências |
| LIB-011 | Ruff                 | Linter e formatação do código           | Fixar versão no arquivo de dependências |
| LIB-012 | Docker               | Containerização do projeto              | Controlar versão mínima recomendada     |

---

## 4. Convenção para Tags no Git

As tags devem seguir o padrão:

```text
vMAJOR.MINOR.PATCH
```

## 5. Critérios para Alteração de Versão

### PATCH

Incrementar quando houver:

* Correção de bugs.
* Ajustes em scripts.
* Correção de documentação.
* Pequenas melhorias internas.

### MINOR

Incrementar quando houver:

* Nova funcionalidade.
* Novo script.
* Novo modelo.
* Nova etapa no pipeline.
* Nova métrica de avaliação.
* Nova interface ou endpoint.

### MAJOR

Incrementar quando houver:

* Mudança grande na arquitetura.
* Quebra de compatibilidade.
* Alteração significativa no formato dos dados.
* Troca completa do modelo ou pipeline principal.


## 9. Histórico de Versões

| Versão | Data       | Descrição                                                                                       |
| ------ | ---------- | ----------------------------------------------------------------------------------------------- |
| v0.1.0 | 2026-05-07 | Versão inicial com estrutura base do projeto, análise inicial do dataset e documentação inicial |

# Registro de Baselines

| Baseline | Tag | Data | Descrição |
|---|---|---|---|
| BL-001 | v1.0.0 | 2026-05-07 | Estrutura inicial do projeto, configuração base do ambiente, documentação inicial e análise preliminar do dataset |

