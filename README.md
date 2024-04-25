# machine_learning_stroke
Projeto MVP realizado na pós-graduação de ciência de dados onde realizo uma predição da ocorrência de avc em um indivíduo e encontro os principais features que contribuem para a doença.

# - OBJETIVOS:
  
O projeto em questão aborda um conjunto de dados que se concentra em pacientes, com o objetivo de prever a ocorrência de AVC (Acidente Vascular Cerebral). O conjunto de dados consiste em 10 colunas que contêm informações sobre a saúde e o estilo de vida dos pacientes. A tarefa principal é utilizar modelos de aprendizado supervisionado para prever, matematicamente, a probabilidade de um paciente sofrer um AVC.

O foco principal deste projeto é maximizar o resultado do recall do nosso modelo. Isso é crucial para minimizar o número de falsos negativos, uma vez que uma predição errônea, nesse contexto, pode ter implicações significativas para a saúde do paciente.

Além disso, uma análise mais aprofundada dos dados pode fornecer insights sobre as principais causas de AVC, conforme identificadas em nosso conjunto de dados. Essas informações são valiosas para os profissionais de saúde, pois podem orientar estratégias de tratamento e prevenção mais eficazes para os pacientes.


# - A seguintes informações podem ser retiradas do dataset:

sex: Gênero do paciente (1: homem; 0: mulher)

age: Idade do paciente (em anos)

hypertension: Paciente tem hipertensão (1), ou não tem(0)

heart_disease: Paciente já teve problemas no coração(1), ou não (0)

ever_married: Paciente casado (1) ou não (0)

work_type: Tipo de trabalho: 0 - Nunca Trabalhou, 1 - Criança, 2 - Emprego governamental, 3 - Conta própria, 4 - Privado

Residence_type: Área do paciente: 1 - Urbano, 0 - Rural

avg_glucose_level: Nível médio de açucar no sangue

bmi: Índece de massa corporal

smoking_status: 1 - fumante, 0 - nunca fumou

stroke: Paciente teve um avc (1), ou não (0)


# - CONCLUSÃO

Identifiquei um fator chave que contribui para o desempenho excepcional dos modelos de árvore de decisão em nosso conjunto de dados. A variável 'avg_glucose_level' demonstra uma forte correlação com esse tipo de modelo. Com base nisso, podemos considerar o nível de glicose no sangue como um indicador significativo da probabilidade de ocorrência de AVC em um indivíduo.

Além disso, várias outras informações revelaram-se relevantes para orientar profissionais de saúde sobre os cuidados necessários na detecção de AVC. Fatores como hipertensão, histórico de doenças cardíacas e índice de massa corporal do paciente demonstraram ter uma influência substancial nos resultados de nosso conjunto de dados. Esses insights são cruciais para garantir uma abordagem cuidadosa ao lidar com essa condição médica.

Nossas análises revelaram resultados notáveis em termos de acurácia e recall, este último sendo de especial importância. Após uma minuciosa análise de nosso conjunto de dados e o devido tratamento dos dados, conduzimos testes com diversos modelos, incluindo a padronização e normalização dos dados para comparação. Destacamos uma relação particularmente forte entre nossos dados e modelos baseados em árvore de decisão, especialmente quando otimizados com a hiperparametrização do modelo para alcançar os melhores resultados.
