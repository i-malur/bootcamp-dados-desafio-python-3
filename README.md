# Challenge Probabilidade e Amostragem
Repositório com o desafio para o Bootcamp Data Analytics da Womakers Code.

## Questões:
Suponha que você trabalha em uma empresa de streaming e, com as mudanças no
mercado, a equipe de marketing suspeita que o perfil dos clientes que cancelaram a
assinatura mudou. Eles pediram sua ajuda para entender:
1. Se o perfil dos clientes que cancelam hoje é diferente do perfil dos clientes
que cancelaram anteriormente.
Dica: Fazer um comparativo dos clientes que cancelaram nos últimos 6
meses com os que cancelaram a mais de 24 meses.
2. Quais são as principais diferenças entre os perfis, para que possam criar
estratégias mais eficazes de retenção. Para isso, eles fornecem a base de
dados clientes.csv, que contém informações anonimizadas sobre os clientes
ao longo do tempo.

Dica / Passo a Passo:
1. Analise a distribuição de idade, tempo de assinatura, frequência de uso e região
dos clientes que cancelaram e dos novos clientes no período de 24 meses.
2. Plote gráficos para identificar padrões nos clientes que mantêm e cancelam a
assinatura.
3. Utilize testes estatísticos para verificar se há uma relação significativa entre
tempo de assinatura e taxa de cancelamento.
4. Suponha agora que os dados recebidos são somente uma amostra da sua
população total de clientes. Suponha que a sua "população" de clientes
verdadeira é de 100000. Qual o tamanho da amostra necessária para chegarmos a
conclusões com 95% de confiança e 2% de margem de erro? A base informada é
suficiente? E com uma margem de erro de 10%?

## Variáveis:
* cliente_id - identificador único do cliente.
* idade - idade do cliente.
* tempo_assinatura_meses - quantos meses o cliente possui/possuia de assinatura.
* frequencia_uso_mensal - quantas vezes o cliente usa o serviço por mês
* regiao - qual a região de moradia do cliente.
* mensalidade - preço do plano.
* cancelou - mostra se a assinatura está ativa ou não

## Tecnologias usadas:
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)

```py
print('Feito com carinho 🌹')
```
