
# Projeto de Reconhecimento de Atividades Humanas com K-Means e PCA

## Objetivo do Projeto
O objetivo deste projeto é explorar o **UCI HAR Dataset** para identificar padrões relacionados a atividades humanas captadas por sensores. Utilizando técnicas de aprendizado de máquina não supervisionado, como **Análise de Componentes Principais (PCA)** e **K-Means**, o trabalho busca agrupar os dados de forma eficiente e compreender as relações intrínsecas entre diferentes tipos de atividades. Os resultados esperados incluem a identificação de um número ideal de clusters e insights sobre a separação das classes latentes nos dados.

## Instruções para Execução do Código

### Requisitos de Software
- Python 3.8 ou superior
- Jupyter Notebook (opcional, mas recomendado)
- Bibliotecas:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

### Passos para Execução
1. **Instale as dependências**:
   ```bash
   pip install -r requirements.txt
   ```

2. **Baixe o Dataset**:
   O projeto utiliza o **UCI HAR Dataset**, que pode ser baixado automaticamente ao executar o código. Certifique-se de ter conexão com a internet.

3. **Execute o Notebook**:
   Abra o arquivo `K_means_Human_Activity_Recognition.ipynb` no Jupyter Notebook ou em qualquer ambiente de desenvolvimento que suporte notebooks.
   ```bash
   jupyter notebook K_means_Human_Activity_Recognition.ipynb
   ```

4. **Siga as células no notebook**:
   - As células estão organizadas sequencialmente para carregar os dados, realizar a análise e visualizar os resultados.

5. **Interprete os Gráficos**:
   - Visualizações como o scatter plot após PCA e gráficos de inércia e silhouette score ajudam a compreender o desempenho dos clusters.

## Principais Conclusões e Considerações

### Resultados Obtidos
- O método do cotovelo e o silhouette score sugerem que o número ideal de clusters são 2.
- A aplicação de PCA foi fundamental para reduzir a dimensionalidade dos dados e permitir visualizações mais claras dos agrupamentos.

### Pontos de Melhoria
- Desequilíbrios nas classes e ruídos nos dados limitaram a separação total entre os clusters.
- Atividades fisicamente semelhantes apresentaram sobreposição, sugerindo a necessidade de métodos mais robustos de clustering.

### Recomendações Futuras
- Utilizar algoritmos como DBSCAN para lidar com outliers e clusters de formatos não lineares.
- Ampliar a análise com algoritmos supervisionados para comparação de desempenho.
- Recoletar dados com maior equilíbrio e menor presença de ruído.

---

Qualquer dúvida ou sugestão sobre o projeto pode ser encaminhada para o desenvolvedor responsável.
