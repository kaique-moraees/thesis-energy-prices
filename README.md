# Aplicação de Árvores de Hoeffding para Predição de Preços de energia elétrica sob mudanças de conceito. 

O mercado de energia elétrica caracteriza-se por alta volatilidade e complexidade estrutural, tornando a previsão precisa de preços essencial para formulação de estratégias comerciais e mitigação de riscos financeiros. Abordagens tradicionais de aprendizado de máquina, como ARIMA e SVMs, frequentemente assumem estacionariedade dos dados, hipóteses que se tornam nulas em ambientes sujeitos a mudanças estruturais, sazonalidades complexas e fenômenos de deriva de conceito. Este trabalho investiga a aplicabilidade de Árvores de Hoeffding e a variante Árvores Adaptativas de Hoeffding para predição de preços de energia elétrica considerando as eventuais mudanças de conceito. O objetivo é avaliar comparativamente o desempenho preditivo dos algoritmos de Hoeffding, verificando se a incorporação de mecanismos de detecção e adaptação a mudanças de conceito resulta em desempenho superior. A metodologia, estruturada segundo os frameworks CRISP-DM e KDD, utiliza o dataset público "Hourly energy demand generation and weather" da Espanha, contendo 35.000 observações horárias de 2015 a 2018. Os modelos serão avaliados por métricas quantitativas (RMSE, MAE, MAPE, R²) e análises de adaptação a mudanças de conceito, incluindo tempo de recuperação e substituições de ramos. Espera-se demonstrar que algoritmos adaptativos incrementais apresentam vantagens significativas em ambientes não estacionários, contribuindo para o avanço teórico e prático em predição de séries temporais energéticas.


## Roadmap

- Melhorar o suporte de navegadores

- Adicionar mais integrações


## Stack utilizada

**Front-end:** React, Redux, TailwindCSS

**Back-end:** Node, Express


## Autores

- [@kaique_moraees]([https://github.com/kaique-moraees])


## Licença

[MIT](https://choosealicense.com/licenses/mit/)
