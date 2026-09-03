# 📊Simulador de Investimentos em Fundos Imobiliários (FIIs)
Projeto desenvolvido como desafio prático do Bootcamp Excel Avançado com IA e Claude (Santander Open Academy) da [DIO](https://www.dio.me/), aplicando fórmulas financeiras e lógicas de referência do Excel para construir uma ferramenta de simulação de aportes em Fundos Imobiliários com três tipos de perfis de investimento.

## 🎯 Sobre o projeto
Este projeto é uma ferramenta desenvolvida em Excel para simular investimentos em Fundos de Investimento Imobiliário (FIIs). A planilha funciona como um pequeno dashboard interativo, permitindo ao usuário calcular o valor total investido, o patrimônio acumulado ao longo do tempo e os dividendos mensais estimados — ajudando investidores iniciantes a entender melhor o impacto de seus aportes.

## 🔑 Objetivo
- Aplicar os conceitos de Excel no desenvolvimento de uma ferramenta prática de simulação de investimentos;
- Automatizar cálculos financeiros complexos (valor investido, patrimônio acumulado, dividendos mensais);
- Documentar um processo técnico de forma clara e estruturada;
- Compartilhar a solução via GitHub.

## Como Utilizar o Simulador
A aba INVESTIMENTO reúne todas as informações em um único painel:

1. Configurações
Dados de referência do usuário (salário e rendimento médio da carteira), usados para sugerir um valor de investimento mensal.

2. Investimentos Mensais
O usuário define:

Quanto pretende investir por mês
Por quantos anos pretende investir
A taxa de rendimento mensal estimada
A partir disso, a planilha calcula automaticamente o Patrimônio Acumulado (usando a função FV — Valor Futuro, com juros compostos) e os Dividendos Mensais estimados sobre esse patrimônio.

3. Cenários
Uma tabela mostra o patrimônio e os dividendos projetados em 5 horizontes de tempo diferentes (2, 5, 10, 20 e 30 anos), permitindo comparar o efeito do tempo sobre os investimentos.

4. Perfil e Alocação por Tipo de FII
Um seletor (dropdown) permite escolher entre os perfis Conservador, Moderado e Agressivo. Ao selecionar um perfil, a planilha distribui automaticamente o valor mensal investido entre os diferentes tipos de fundos (Papel, Tijolo, Híbridos, FOFs, Desenvolvimento e Hotelarias), de acordo com percentuais pré-definidos para cada perfil de risco. Um gráfico de pizza ilustra essa distribuição em tempo real.

##   Como Usar
1. Baixe o arquivo `planilha_investimentos_imobiliarios.xlsx`
2. Preencha os campos destacados (Salário, Rendimento da Carteira, Quanto Investir por Mês, Por Quantos Anos, Taxa de Rendimento)
3. Escolha seu perfil de investidor no dropdown
4. Acompanhe os resultados calculados automaticamente

## Autor
Maurício
