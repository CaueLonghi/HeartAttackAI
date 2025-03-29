# HeartAttackAI - Previsão de Ataque Cardíaco

## Sobre o Conjunto de Dados

Este conjunto de dados contém 13 atributos:

1. **Idade**: Idade do paciente (em anos).
2. **Sexo**: Gênero do paciente (1 = masculino; 0 = feminino).
3. **Dor no Peito**: Tipo de dor no peito:
   - 1: Angina Típica (todos os critérios presentes)
   - 2: Angina Atípica (dois de três critérios atendidos)
   - 3: Dor Não Anginal (menos de um critério atendido)
   - 4: Assintomático (nenhum dos critérios atendidos)
4. **Pressão Arterial em Repouso**: Pressão arterial em repouso (em mmHg, no momento da admissão no hospital).
5. **Colesterol**: Colesterol sérico (em mg/dL).
6. **Fbs**: Glicemia em jejum > 120 mg/dL (indicando possível diabetes):
   - 1 = verdadeiro
   - 0 = falso
7. **ECG em Repouso**: Resultados do eletrocardiograma em repouso:
   - 0: normal
   - 1: anormalidade na onda ST-T (inversão da onda T e/ou elevação ou depressão ST > 0,05 mV)
   - 2: mostrando provável ou definitiva hipertrofia ventricular esquerda pelos critérios de Estes.
8. **MaxHR**: A maior quantidade de batimentos por minuto que o coração pode atingir durante um exercício intenso.
9. **Exang**: Angina induzida por exercício (1 = sim; 0 = não).
10. **Oldpeak**: Depressão ST induzida por exercício em relação ao repouso (em mm, calculado subtraindo o ponto mais baixo do segmento ST durante o exercício e o repouso).
11. **Inclinação**: A inclinação do pico do segmento ST no exercício. As anormalidades ST-T são consideradas um indicador crucial para identificar a presença de isquemia:
    - 1: Inclinação ascendente
    - 2: Plano
    - 3: Inclinação descendente
12. **Ca**: Número de vasos principais (0-3) coloridos por fluoroscopia. Os principais vasos cardíacos são: aorta, veia cava superior, veia cava inferior, artéria pulmonar (sangue pobre em oxigênio que vai para os pulmões), veias pulmonares (sangue rico em oxigênio que retorna ao coração) e artérias coronárias (responsáveis por fornecer sangue ao tecido cardíaco).
13. **AHD**: Doença Arterial Coronária:
    - 0: Sem doença
    - 1: Defeito fixo (o tecido cardíaco não consegue absorver o tálio tanto sob estresse quanto em repouso)
    - 2: Defeito reversível (o tecido cardíaco não consegue absorver o tálio apenas durante a fase de exercício do teste)
14. **AHD (outro campo)**: 
    - 0: Sem doença
    - 1: Com doença

