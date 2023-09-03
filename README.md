# Dasboards Centro Cirúrgico

## Contexto
O Hospital se via em uma situação onde ele não tinha acesso a nenhum dado do Centro Cirúrgico, seja de sua produtividade, censo de pacientes e KPI's obrigatórios por Lei.

## Objetivos
O Objetivo principal nesse primeiro momento era apresentar de forma estruturada os dados basicos do setor, assim como a criação dos KPI's obrigatórios por Lei e comparação de performance dos mesmos entre os meses.

## Público alvo
Gestão local do Centro Cirúrgico, Direção Médica, Gerencia Adminisstrativa e Setor Comercial

## Fontes de Dados
Foram extraídas as informações do Banco de dados do sistema Hospitalar, assim como de controles manuais que o time realiza, totalizando 5 bases de dados

## Processos de Integração e Carga (ETL)
Houve uma integração das datas entre as 5 bases utilziadas, através da criação de um calendário padronizado. No momento não houve a necessidade de uma estruturação mais complexa, porem, para podermos contextualizar os dados inseridos, assim como realizar a criação dos 16 Indicadores Obrigatórios e a criação do Censo do setor, onde medimos quantidade de procedimentos por cirurgão, divisão por faixa etária e porte de cirurgia, foram criadas mais de 30 interaçãoes através de Fórmulas DAX.

## O Dashboard
![Painel Centro Cirúrgico 1](https://github.com/chscharth/Dasboards/assets/85425294/806b41cf-7f88-4805-8b7a-c4eabed13baf)

![Painel Centro Cirúrgico 2](https://github.com/chscharth/Dasboards/assets/85425294/d5d979e8-a000-449e-8eaf-dce0f3451ddb)

![Painel Centro Cirúrgico 3](https://github.com/chscharth/Dasboards/assets/85425294/badd2707-0171-408f-b48d-30383e32d593)

## Conclusões
Com a visualização estruturada dos dados conseguimos determinar que o nosso perfil majoritário é feminino e está entre os 40 e 79 anos, sendo o perfil mais proeminete o perfil de 50-59, verifcamos também que nosso foco são cirugias de pequeno porte e eletivas, além disso percebemos que para um centro cirúgico aberto 24h por dia e 7 dias por semana, o perfil médio de 300 cirurgias é pouco e por sí só e em termos de capacidade instalada, ele pode dobrar de tamanho, porem isso depende da quantidade de leitos hospitalares para absorver o paciente pós cirúrgico, assim como a agenda dos cirurgiões para horários diferenciados (noite, madrugada), verificamos também que a taxa de cancelamento vem aumentando e precisa ser adereçada, quanto ao número de atrasos vemos uma pequena variação na casa dos 40%, o que é valor consideravelmente alto e que deve ser sanado o quanto antes, além disso de fato relevante temos a quantidade de preenchimentos incompletos do formulário de cirurgia segura, o que se trata de um indicador que deve ser zero, de resto temos ótimos números quanto a cirurgias em pacientes errados, local de cirurgia errada e queda, onde temos zero eventos. 
Como proposta de melhorias, foi sugerida a instalação de um comitê multidiscipliar para o acompanhamento e construção/execução de planos de ação para mitigação dos indicadores negativos, assim como para entender o porque da baixa adesão cirúrgica de pacientes masculinos e planos de aumento estruturado de cirurgias realizadas no hospital. 

**DISCLAIMER - PARA PROTEGER A SEGURANÇA DAS INFORMAÇÕES, TODOS OS DADOS APRESENTADOS FORAM RANDOMIZADOS**
