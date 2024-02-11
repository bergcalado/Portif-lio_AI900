# Portif-lio_AI900
Portifólio do Treinamento de Machine-Learning-na-pratica-no-Azure
1º Abrir o portal do Azure, https://portal.azure.com.
2º Clicar em create resource.
3º Pesquisar por Machine Learning. OBS: Podemos pesquisar vários outros recursos Azure.
4º Ao encontrar o recurso solicitado clicar e create, e iniciaremos a configuração na aba Basics.
5º Pontos importantes:
•	Subscription – É referente a sua conta, seu endereço.
•	Resource Group – Podemos referenciar como sua caixa de recursos, podendo não só conter o Azure Machine Learning, podemos adicionar outros recursos, para um melhor gerenciamento de tempo de vida e permissões e políticas, comum a todos.
•	Workspaces – Podemos definir como sendo espaços criados para colaboração de trabalho, criação de artefatos colaborativos de aprendizado de máquina relacionado ao grupo. Podemos efetuar trabalhos em conjunto.
Para mais informações: https://learn.microsoft.com/en-us/azure/machine-learning/concept-workspace?view=azureml-api-2&WT.mc_id=Portal-Microsoft_Azure_MLTeamAccounts.
Dentro do Workspace Temos:
	Nome  – Nome do Workspace
	Region – Região onde será criado o trabalho, onde alocaremos nosso recurso.
	Storage account – Podemos definir como sendo nosso HD “Hard Disk” para guardar informações.
	Key Vault  - Onde guardaremos nossas chaves de acesso.
	Application insights – Podemos dizer que é um espaço de trabalho onde o Azure Application insights vai armazenar informações de monitoramento.
	Container registry – Podemos dizer que é onde podemos pegar configurações já prontas de máquinas criadas registradas como Docker.

6º As demais abas:
	Networking – Podemos escolher o tipo de isolamento necessário para nossa Workspace, para mais informações , https://learn.microsoft.com/en-us/azure/machine-learning/how-to-managed-network?view=azureml-api-2&WT.mc_id=Portal-Microsoft_Azure_MLTeamAccounts&tabs=azure-cli.
	Encryption – Informa a encriptação que é utilizada nas instâncias do Azure Machine Learning nos serviços de métricas e metadados nas instâncias do Azure Cosmos DB, onde todos os dados são encriptados. Podemos encriptar com a chave criada pela Microsoft ou trazer nossa chave.
	Identidy – É uma identidade gerida que permite ao Azure se autenticar em serviços de nuvem sem armazenar credencias em código.
	Tags – São pares de nomes e valor, que servem para categorizar recursos e visualizar a cobrança consolidada, onde podemos aplicar a mesma tag a vários recursos e grupos de recursos.
	Review + create – É uma revisão do que já foi configurado.

6º Após as configurações clicamos em create, aguardamos a criação dos recursos, após criação clicamos em Go to Resources.
7º Após a finalização das configurações vamos na página do IA do Azure | Estúdio de Aprendizado de Máquina, onde vamos encontrar documentações de Exemplos. Clicamos em ML Automatizado, nele podemos treinar e localizar o melhor modelo com base em dados.
8º Avançando no tipo de tarefa de dados vamos escolher que tipo de aprendizado de máquina para o nosso experimento iremos utilizar. Para o nosso exemplo utilizaremos regressão. Para saber mais podemos consultar a documentação contida em: https://contentsafety.cognitive.azure.com/.
9º No tipo de dados vamos informar os dados onde a IA vai trabalhar para gerar as informações solicitadas.
10º Na fonte de Dados teremos vários tipos de entrada:
	A partir do SQL Azure.
	A partir do banco de dados SQL.
	De arquivos Locais.
	De arquivos WEB.
Para este projeto escolheremos WEB, URL da Web: https://aka.ms/bike-rentals.
11º Para quem já formatou um arquivo no Microsoft Excel bem bem familiar as configurações do mesmo na configurações do de entrada do arquivo WEB.
12º Na configuração de Esquema, configuraremos os tipos dos campos.
13º Após a carga do arquivo entraremos nas configurações de tarefas. Onde entramos os tipos de validações que queremos para o projeto. Em cada parâmetro existe um Help, desta forma podemos verificar e escolher o melhor parâmetro.


 
 


