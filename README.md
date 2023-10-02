# Introdução
O processo de aprendizagem de máquina surgiu com o advento da tecnologia no século XXI e logo se tornou fundamental para a construção de sistemas preditivos e de personalização para UX (User Experience). No entanto, no mundo contemporâneo, tecnologias e informações sofrem alterações frequentemente, o que pode acarretar uma imprecisão nos dados fornecidos por esses sistemas de aprendizagem. Nesse contexto, o conceito de aprendizagem contínua surge como uma alternativa e solução para este problema, haja vista que, dessa forma, estruturas de Machine Learning (ML) sofrerão atualizações periódicas, tornando suas respostas mais precisas e com maior índice de acerto. Este se difere do modelo tradicional (treinamento com uma base fixa), uma vez que a cada atualização, o treinamento é feito com uma base diferente de dados (com novas adições e conhecimento adquirido), integrando novas informações sem abrir mão do conhecimento prévio. Todo esse cenário está inserido no conceito de "concept drift", visto que este é um problema que ocorre quando a distribuição dos dados muda ao longo do tempo, tornando o modelo desatualizado e incapaz de lidar com novas informações. 

# Solução 
Diante deste cenário, surge a necessidade de encontrar uma alternativa para este problema, com o objetivo de potencializar a precisão dos modelos e impedirem sua obsolescência. Para isso, uma abordagem válida é o CKL (Continuous Knowleadge Learning), com a implementação de sistema de feedback com NLP e Web Scrapping, que tornarão as estruturas de ML dinâmicas e adaptadas para as novas informações que surgirão com o tempo.

## Diagrama de blocos

### Sistema de feedback
Este sistema será introduzido após as respostas, para que o usuário possa avaliar a qualidade e acurácia. Após esse procedimento, o feedback será coletado e utilizado para filtrar as informações relevantes para uma próxima base de dados. Além disso, o feedback também será submetido a um NLP (Natural Language Processing) para a identificação de categorias e sentimentos, que também contribuirão com a construção da próxima base a ser treinada.

### Web Scrapping
Atrelado ao sistema de feedback, será integrado o Web Scrapping, com o objetivo de realizar consultas constantes em sites pré-definidos e confiáveis e, assim, atualizar os registros que já possuem com informações renovadas e atuais. Este processo levará em consideração as categorias e sentimentos encontrados na fase anterior, durante o NLP.

# Conclusão
Como conclusão, a implementação da solução proposta torna-se essencial no que tange a construção de um modelo de aprendizagem de máquina de qualidade e preciso ao longo do tempo, pois com o funcionamento baseado em CKL, a base de dados sofrerá atualizações frequentes a fim de deixar os dados mais relevantes e atuais possíveis, garantindo uma maior assertividade em suas respostas. No entanto, sua implementação pode ser um desafio, uma vez que alguns sistemas como NLP e Web Scrapping terão que ser desenvolvidos e devidamente integrados. Porém, os benefícios dessa adoção fazem com que a substituição por uma aprendizagem contínua valha a pena, uma vez que o chatbot fornecerá respostas mais precisas e solucionará o problema de "concept drift".

# Referências

JANG, J. et al. **TOWARDS CONTINUAL KNOWLEDGE LEARNING OF LANGUAGE MODELS**. [s.l: s.n.]. Disponível em: <https://arxiv.org/pdf/2110.03215.pdf>. Acesso em: 02 out. 2023.
