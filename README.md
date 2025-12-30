# Projeto: Dashboard de Assinaturas e Receitas — Excel

Visão Geral
Este projeto consiste na construção de um dashboard analítico em Microsoft Excel para acompanhamento de assinaturas, planos e receitas, a partir de uma base de dados estruturada. O objetivo é transformar dados brutos em informações consolidadas e visuais, apoiando análises de negócio e tomada de decisão.

O dashboard permite visualizar o perfil dos assinantes, a distribuição de planos, a receita total e o impacto de produtos adicionais e cupons.

Estrutura do Arquivo Excel
O arquivo está organizado em quatro abas principais:
* Assets
Aba de apoio visual que contém elementos gráficos e recursos utilizados no dashboard, como ícones e referências visuais. Essa aba auxilia na padronização estética do painel.
* Bases (Dados Brutos)
Contém a base de dados principal, com um registro por assinante. Essa aba funciona como a fonte de dados do projeto e não deve ser alterada manualmente.
Principais campos:
Subscriber ID: identificador único do assinante
Name: nome do assinante
Plan: tipo de plano contratado (Core, Standard, Ultimate)
Start Date: data de início da assinatura
Auto Renewal: indicação de renovação automática
Subscription Price: valor do plano
Subscription Type: periodicidade (mensal, trimestral ou anual)
EA Play Season Pass: indicação de produto adicional
EA Play Season Pass Price: valor do EA Play
Minecraft Season Pass: indicação de produto adicional
Minecraft Season Pass Price: valor do Minecraft Pass
Coupon Value: valor de desconto aplicado
Total Value: valor total final da assinatura
* Cálculos
A aba Cálculos é responsável por todas as consolidações e métricas intermediárias utilizadas no dashboard. Nela são realizados somatórios, contagens e agregações, como:
Receita total
Receita por tipo de plano
Quantidade de assinantes por plano
Impacto de cupons e produtos adicionais
Essa separação garante melhor organização e manutenção do arquivo.
* Dashboard
A aba Dashboard apresenta os principais indicadores e gráficos do projeto. Os dados exibidos são alimentados exclusivamente pela aba Cálculos, garantindo consistência das informações.
Principais Métricas Analisadas
Total de assinantes
Receita total
Receita por tipo de plano
Distribuição dos planos (Core, Standard, Ultimate)
Adoção de Season Passes
Impacto dos cupons no valor final
Como Reproduzir o Dashboard no Excel

Preparação dos dados
Abra o arquivo Excel e acesse a aba Bases. Verifique se os dados estão completos, sem linhas vazias, com valores numéricos corretamente formatados e datas no formato adequado.

Criação de tabelas dinâmicas
Selecione toda a base de dados da aba Bases e insira uma Tabela Dinâmica. Crie as tabelas na aba Cálculos para consolidar as informações necessárias, como soma de receitas por plano e quantidade de assinantes.

Criação de gráficos
A partir das tabelas dinâmicas, insira gráficos adequados (colunas, barras ou indicadores). Esses gráficos servirão como base visual para o dashboard.

Montagem do dashboard
Copie os gráficos e indicadores para a aba Dashboard, organize os elementos de forma clara e padronize cores, fontes e layout. Utilize os recursos da aba Assets para melhorar a apresentação visual.
Ferramentas Utilizadas
Microsoft Excel
Tabelas
Fórmulas
Tabelas Dinâmicas
Gráficos

Objetivo do Projeto
Demonstrar como dados estruturados podem ser transformados em insights estratégicos utilizando Excel, aplicando conceitos de análise de dados, modelagem simples e visualização de informações.

Considerações Finais
Este projeto simula um cenário real de análise de assinaturas e receitas, utilizando apenas Excel, mas seguindo boas práticas de organização, separação de dados, cálculos e visualização, tornando o dashboard escalável e de fácil manutenção.
