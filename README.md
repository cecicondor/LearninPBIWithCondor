# LearninPBIWithCondor
Intuito desse repositório é aprender power b.i comigo, tal como quando vemos Study With Me Korean no You Tube, mas dessa vez eu partilho o que tenho aprendido de POWER B.I, não com tratativa de dados, mas toda questão de automação de relatórios a fim de facilitar minha vida no trabalho já que minha vida pessoal não exige uma visão no Power BI

Dica! → Fórmula Switch utilizada para que eu consiga aplicar várias condições numa mesma fórmula. Abaixo são todas as fórmulas chave que podem te auxiliar.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1ac2abe9-3861-4bdd-a3a6-d9e5e04315e9/dd5924ee-3fa5-43d8-bb87-ff9e54247a10/Untitled.png)

---

# Fórmulas Básicas de Power B.I

### SUM

Quando vc não quiser criar uma coluna para calcular cada linha, mas quiser criar uma visão geral você vai precisar criar uma medida. Nesse exemplo do Alon, foi feita uma soma da tabela toda de faturamento para mensurar, não por linha/produto, mas o total de faturamento de uma empresa. Ou seja, as medidas podem auxiliar dessa forma. E para mudar a formatação do texto para moeda por exemplo, só clicar em cima da medida e ir em modelagem → campo: $

Para criar uma medida com outras medidas, tipo: faturamento total - custo total basta criar uma nova medida no relatório mesmo e referenciar suas medidas.

**Dica!**

Caso você tenha muitas medidas, é necessário que você crie uma tabela em branco para armazenar todas as suas medidas, será importante por bons costumes e assim você não se perde em meio a tratativa. E para criar essa nova tabela, clica em inserir dados → assim carrega numa nova tabela em branco para imputar suas medidas. E automaticamente cria uma nova tabela para você.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1ac2abe9-3861-4bdd-a3a6-d9e5e04315e9/afd8b79e-e404-4235-b2b1-a43377d4425a/Untitled.png)

### AVERAGE

A média de faturamento, basta incluir uma nova medida (caso você queira ter uma visão geral), coloca a fórmula AVERAGE ([*sua coluna de referencia*]) e então poderá incluir no relatório uma visão com a média de faturamento. 

### MAX

MAX = ([sua coluna de referencia)]

### MIN

MIN = ([sua coluna de referencia])

### DIVIDE

O exemplo do divide para utilizar, o resultado alternativo é para utilizar caso tenha algum erro, você pode colocar como ZERO, assim retorna 0 caso dê algum erro.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1ac2abe9-3861-4bdd-a3a6-d9e5e04315e9/b740545e-ef12-4e3c-bf21-1fe355f6fd9f/Untitled.png)
