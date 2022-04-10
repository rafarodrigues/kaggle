# 001 Titanic - Machine Learning from Disaster
<img src="https://storage.googleapis.com/kaggle-competitions/kaggle/3136/logos/header.png" alt="exemplo imagem">

> Essa é a competição mais conhecida do Kaggle, considerada como sendo a recomendada para todos iniciantes.
> 
> A ideia é: a partir de uma base de dados *test*, montar um modelo que possa identificar com a maior precisão possível se um passageiro poderia ou não morrer no acidente, dados algumas variáveis como gênero, idade, preço da passagem, classe econômica e etc.
> 
>  

## 📊 Intenções / Metas
Apesar de saber que não é o melhor momento para começar a olhar para Machine Learning, esse projeto do Kaggle serviu para me apresentar algumas ferramentas e conceitos de aprendizado de máquina.<br><br>
Foquei em seguir o tutorial da Alex Cook apresentado no Kaggle, para posteriormente acrescentar meus próprios *insghts* e manipulações gráficas.
1. Entender como funciona uma competição do Kaggle
2. Ter o primeito contato com ferramentas de `Machine Learning`
3. Treinar conceitos de bibliotecas de `Ciência de Dados` como NumPy, Pandas e Matplotlib
4. Treinar GitHub, Jupyter Lab e Python
5. Aprender a manipular arquivos e gráficos

## 📑 Ajustes e melhorias

O projeto ainda está em desenvolvimento e as próximas atualizações serão voltadas nas seguintes tarefas:

- [ ] Retornar em 01/04/2023 e realizar o desafio novamente, já com novos conhecimentos
- [X] Adicionar gráficos e bibliotecas
- [ ] Melhorar gráficos e adicionar explicações
- [X] Configurar exportação do Jupyter Notebook para PDF
- [ ] Adicionar análises do resultado 
- [ ] Montar no README.md passo-a-passo de como organizei o projeto 
- [ ] Montar e explicar forma de validação dos dados 
- [ ] Corrigir 'warnings' do projeto `001 Titanic`

## 🗺 Resumo

A competição é simples: Nós queremos usar uma base de dados de passageiros do Titanic (Nome, Idade, Gênero, preço da passagem, et c.) e predizer quem vai morrer e quem vai sobreviver. `~~Sim, macabro~~`
Temos 3 arquivos para o projeto:
* (1) train.csv 
* (2) test.csv
* (3) gender_submission.csv

`train.csv` contém detalhes de diversos passageiros a bordo (891 passageiros, para ser exato). Os valores na coluna `Survived` representam `0 morreu` e `1 sobreviveu` <br> 

`test.csv` Após treinar o modelo com o primeiro arquivo, devemos aplicar o modelo no arquivo `test.csv` e predizer se os 418 passageiros sobreviveram ou não.<br> 

`gender_submission.csv` é um arquivo fornecido pelo desafio para demonstrar como deve se o resultado. Esse arquivo possui o 'modelo' de que todos os homens morreram e todas as mulheres sobreviveram. 
<br><br><br>
`A ideia do desafio é melhorar a acuracidade desse modelo`
[⬆ Voltar ao topo](#001_Titanic)<br>
