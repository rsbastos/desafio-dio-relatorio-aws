# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 17/10/2024  
Empresa: Abstergo Industries   
Responsável: René

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por René. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- **Ferramenta:** Amazon EC2 Spot Instances
- **Foco:** Instâncias de computação sob demanda que usam capacidade de servidor ociosa da AWS
- **Descrição de caso de uso:** A ferramenta entrega poder computacional para executar análises de dados ou simulações científicas através das *spot instances*, podendo economizar até 90% em relação às instâncias *on-demand*. São ideais para workloads que podem ser interrompidos e reiniciados, como testes em larga escala, análise de dados não críticas e renderização de gráficos. 

Etapa 2: 
- **Ferramenta:** AWS Lambda
- **Foco:** Execução de código sem necessidade de gerenciar servidores
- **Descrição de caso de uso:** A AWS Lambda pode ser usada para executar funções de análise de dados  ou processar eventos disparados por sensores de pesquisa ou fabricação. Como o pagamento é feito apenas pelo tempo de execução do código, isso ajuda a reduzir custos com infraestrutura, evitando a necessidade de manter servidores constantemente ativos.  

Etapa 3: 
- **Ferramenta:** Amazon S3 Intelligent-Tiering
- **Foco:** Armazenamento de objetos com otimização automática de custo com base no acesso
- **Descrição de caso de uso** A empresa **Abstergo Industries** gera e armazena grandes volumes de dados e pesquisa, que variam em frequência de acesso. O Amazon S3 Intelligent-Tiering move automaticamente os dados entre as camadas de armazenamento de alto e baixo custo, com base nos padrões de acesso, reduzindo custos sem comprometer a performance. 



## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a redução de custos tanto no uso de recursos de computação quanto no armazenamento de dados, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos.


Assinatura do Responsável pelo Projeto:

René
