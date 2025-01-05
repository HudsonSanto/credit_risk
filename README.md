<h1>Análise de Risco de Crédito com Machine Learning</h1>

<h2>Descrição do Projeto</h2>
<p>📊 Este projeto tem como objetivo desenvolver e avaliar um modelo preditivo para análise de risco de crédito, utilizando dados simulados de agências de crédito. O foco está na classificação de solicitantes em grupos de maior ou menor risco de inadimplência, fornecendo uma ferramenta eficiente para instituições financeiras.</p>

<h2>Estrutura do Conjunto de Dados</h2>
<p>O conjunto de dados contém as seguintes colunas:</p>
<ul>
  <li><strong>person_age:</strong> Idade do solicitante.</li>
  <li><strong>person_income:</strong> Renda anual do solicitante.</li>
  <li><strong>person_home_ownership:</strong> Tipo de posse da residência (alugada, própria, hipotecada ou outras).</li>
  <li><strong>person_emp_length:</strong> Tempo de emprego do solicitante (em anos).</li>
  <li><strong>loan_intent:</strong> Finalidade do empréstimo.</li>
  <li><strong>loan_grade:</strong> Classificação do empréstimo (A a G, indicando risco de crédito).</li>
  <li><strong>loan_amnt:</strong> Valor solicitado no empréstimo.</li>
  <li><strong>loan_int_rate:</strong> Taxa de juros do empréstimo.</li>
  <li><strong>loan_status:</strong> Status do empréstimo (0 = não inadimplente, 1 = inadimplente).</li>
  <li><strong>loan_percent_income:</strong> Percentual da renda comprometido com o empréstimo.</li>
  <li><strong>cb_person_default_on_file:</strong> Histórico de inadimplência do solicitante (Y = sim, N = não).</li>
  <li><strong>cb_person_cred_hist_length:</strong> Duração do histórico de crédito do solicitante.</li>
</ul>

<h2>Metodologia</h2>
<ol>
  <li><strong>📊 Exploração dos Dados:</strong>
    <p>Análise estatística e visual para entender distribuições e identificar desequilíbrios entre classes.</p>
  </li>
  <li><strong>🛠️ Pré-Processamento:</strong>
    <p>Tratamento de valores ausentes, codificação de variáveis categóricas, normalização e balanceamento das classes com <strong>SMOTE</strong>.</p>
  </li>
  <li><strong>🚀 Treinamento do Modelo:</strong>
    <p>Avaliação de algoritmos de machine learning, incluindo <strong>Logistic Regression</strong>, <strong>Random Forest</strong>, <strong>SVM</strong>, <strong>XGBoost</strong> e <strong>AdaBoost</strong>, com validação cruzada (k-fold).</p>
  </li>
</ol>

<h2>Resultados</h2>
<p>O modelo <strong>XGBoost</strong> apresentou o melhor desempenho geral, com:</p>
<ul>
  <li><strong>Alta precisão:</strong> Em identificar inadimplentes (classificação da classe 1).</li>
  <li><strong>Recall e F1-score elevados:</strong> Para ambas as classes, indicando equilíbrio entre sensibilidade e especificidade.</li>
</ul>
<p><strong>Relatório de Métricas:</strong></p>
<ul>
  <li><strong>Accuracy:</strong> 93%.</li>
  <li><strong>Precision:</strong> 95% para inadimplentes.</li>
  <li><strong>Recall:</strong> 72% para inadimplentes.</li>
</ul>

<h2>Conclusão</h2>
<p>📌 Este projeto demonstra a aplicação de <strong>machine learning</strong> na mitigação de riscos financeiros. O modelo desenvolvido pode ser utilizado como base para decisões estratégicas na concessão de crédito, auxiliando instituições financeiras a identificar potenciais inadimplentes e otimizar suas políticas de crédito.</p>

<h2>Próximos Passos</h2>
<ul>
  <li>Implementar um pipeline automatizado para aplicação prática.</li>
  <li>Testar o modelo em dados de produção para validação real.</li>
  <li>Explorar novos algoritmos e técnicas de feature engineering.</li>
</ul>

<h2>Estrutura do Repositório</h2>
<ul>
  <li><strong>📁 Dados:</strong> Conjunto de dados utilizado para análise.</li>
  <li><strong>📁 Notebooks:</strong> Scripts de pré-processamento, modelagem e avaliação.</li>
  <li><strong>📊 Relatórios:</strong> Visualizações gráficas e métricas detalhadas.</li>
  <li><strong>📜 Documentação:</strong> Descrição detalhada do projeto e explicações técnicas.</li>
</ul>

<h2>Tecnologias Utilizadas</h2>
<ul>
  <li>Python (Pandas, NumPy, Scikit-learn, XGBoost)</li>
  <li>Jupyter Notebook</li>
  <li>Matplotlib e Seaborn para visualização de dados</li>
</ul>

<p><strong>Contribuições e sugestões são sempre bem-vindas! ⭐</strong></p>

