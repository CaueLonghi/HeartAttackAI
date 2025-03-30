# HeartAttackAI - Previsão de Ataque Cardíaco

## Sobre o Conjunto de Dados (PORTUGUÊS)

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

---

# About Dataset (INGLÊS - ORIGINAL DO CRIADOR)
 There are 13 attributes: 
1. **Age**: Age (in years) 
2. **Sex**: gender (1 = male; 0 = female) 
3. **ChestPain**: Chest Pain type:

   - 1: typical angina (all criteria present)
   - 2: atypical angina (two of three criteria satisfied)  
   - 3: non-anginal pain (less than one criteria satisfied) 
   - 4: asymptomatic (none of the criteria are satisfied) 

4. **Restbps**: Resting Blood pressure (in mmHg, upon admission to the hospital) 
5. **Chol**: serum cholesterol in mg/dL 
6. **Fbs**: fasting blood sugar > 120 mg/dL (likely to be diabetic) 
   - 1 = true; 0 = false

7. **RestECG**: Resting electrocardiogram results 
   - Value 0: normal 
   - Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV) 
   - Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria 
8. **MaxHR**: Greatest number of beats per minute your heart can possibly reach during all-out strenuous exercise. 
9. **Exang**: exercise induced angina 
   - 1 = yes;
   - 0 = no
10. **Oldpeak**: ST depression induced by exercise relative to rest (in mm, achieved by subtracting the lowest ST segment points during exercise and rest) 
11. **Slope**: the slope of the peak exercise ST segment, ST-T abnormalities are considered to be a crucial indicator for identifying presence of ischaemia 
   - Value 1: upsloping
   - Value 2: flat 
   - Value 3: downsloping 
12. **Ca**: number of major vessels (0-3) colored by fluoroscopy. 
Major cardial vessels are as goes: aorta,  superior  vena,cava, inferior vena cava, pulmonary artery (oxygen-poor blood --> lungs), pulmonary veins (oxygen-rich blood --> heart), and coronary arteries (supplies blood to heart tissue). 
13. **AHD**: 
   - 0 = normal; 
   - 1 = fixed defect (heart tissue can't absorb thallium both under stress and in rest);
   - 2 = reversible defect (heart tissue is unable to absorb thallium only under the exercise portion of the test) 
14. **AHD**:
   - 0 = no disease,
   - 1 = disease
