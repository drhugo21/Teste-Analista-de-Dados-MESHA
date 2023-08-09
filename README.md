# Teste Analista de Dados
Critérios avaliadas:
- Uso de Funções DAX
- Documentação das medidas
- ETL
- Modelagem dimensional dos dados

### Desejáveis
- Esquema Estrela
- Criação de visuais com indicadores além dos requisitados.
- SQL (Caso deseje modelar os dados em algum banco)


### Steps:

1. Realizar um Fork desse projeto
2. Realizar a modelagem dimensional da base (Pode ser dentro do próprio PowerBI ou outra ferramenta de ETL)
    - A base está disponível para download [clicando aqui](https://download.inep.gov.br/microdados/microdados_enem_2020.zip).
    - Após descompactar a paste, o Arquivo com a base encontra-se no diretório microdados_enem_2020/DADOS/MICRODADOS_ENEM_2020.csv
    - A documentação necessária sobre os campos da base está disponível nos demais diretórios dentro da pasta descompactada.
4. Disponibilizar o link do seu repositório para posterior avaliação


### Levantar Indicadores
#### Responder às seguintes perguntas:
1. Qual a escola com a maior média de notas?
2. Qual o aluno com a maior média de notas e o valor dessa média?
3. Qual a média geral?
4. Qual o % de Ausentes?
5. Qual o número total de Inscritos?
6. Qual a média por disciplina?
7. Qual a média por Sexo?
8. Qual a média por Etnia?

# ------------------------------------------------------------------------- #

Link do Dashboard com os dados solicitados abaixo. 
São duas abas, onde a primeira responde os dados solicitados acima e a segunda trás mais alguns dados relevantes.

Link: https://bit.ly/45pDwO9

Link no One Drive do arquivo .pbix: https://1drv.ms/f/s!Am18BM21NkHg6hcpvb54e2MbIqHa?e=bDlihY

Também subi os dados num servidor local no MySQL, deixarei aqui no repositório um diagrama de como isso está estruturado no BD.
Preferi dessa forma pois facilitou a subida desses dados no Power BI.

Respondendo as perguntas:

1: Qual a escola com a maior média de notas?

    Desde a LGPD o INEP não fornece mais o nome da escola detalhado, porém através da análise desvendei que as escolas privadas possuem melhor média geral.
   
2: Qual o aluno com a maior média de notas e o valor dessa média?

    O aluno com a inscrição 200005996961, fazendo uma nota geral de 858,58.
    
3: Qual a média geral?

    A média geral é de 523,87.
    
4: Qual o % de Ausentes?

    55,14% dos inscritos se ausentaram.
    
5: Qual o número total de Inscritos?

    Se inscreveram 5 milhões e 783 mil candidatos.
    
6: Qual a média por disciplina?

    Ciências humanas fechou com média 511,15, ciências da natureza com média 490,41, linguagens com média 523,80, matemática com média 520,58 e redação com média 573,41.
    
7: Qual a média por Sexo?

    O sexo masculino fechou com média 531,70, enquanto o sexo feminino fechou com 518,74.

8: Qual a média por Etnia?

    A etnia branca fechou com 533,84, os não declarados fecharam com média 530,56, os de etnia Amarela fecharam com média 522,11, os pardos fecharam com média 506,07, os pretos com média 498,37 e os indígenas com média 470,65.

Outros insights que pude tirar se referem a quantidade de "notas mil" na redação, que foram apenas 28, e a faixa etária de 18 anos que se destacou no número de inscrições, beirando as 1 milhão.
