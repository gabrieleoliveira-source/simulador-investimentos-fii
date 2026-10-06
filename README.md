# simulador-investimentos-fii

## Sobre o projeto
Simulador de investimentos em FIIs desenvolvido em Excel para projeção de patrimônio, dividendos e distribuição de aportes por perfil.

## Objetivo
A ferramenta responde às seguintes perguntas:
- Quanto investir por mês?
- Por quantos anos investir?
- Qual taxa de rendimento mensal está sendo considerada?
- Qual patrimônio pode ser acumulado?
- Qual seria o valor de estimado de dividendos mensais?

## Como funciona?
### VF
A função VF é utilizada para projetar o patrimônio acumulado a partir do aporte mensal, taxa de rendimento e período de investimento.

### PROCV
O PROCV é utilizado para localizar o percentual de cada tipo de Fundo Imobiliário de acordo com o perfil selecionado.
A busca utiliza uma chave composta formada por:
Perfil → Tipo de FII

## Perfis
- Conservador
- Moderado
- Agressivo
> Os percentuais utilizados, de cada perfil, são exemplos didáticos e não constituem recomendação de investimento.

## Tecnologias utilizadas
- Microsoft Excel
- VF
- PROCV
- Validação de Dados
- Intervalos nomeados
- Gráfico de pizza
- Chave composta
