semana 12 -- Banco de Dados

### passo-a-passo

 Criar arquivo JSON 
  db.paises.insert ({

		"pais": {
		"nome": "China",
		"populacao": "1.433783,692",
		"indice": "primeiro Pais mais populoso"

		},

		"covid": {
		"contaminados": "92.605",
		"mortes": "4.636",
		},
                
         "vacinacao": {
		"vacinados": "223.000",
		"recuperados": "87.228",
		
		"dataHora": ISODate ("2021-07-2 T10: 00: 00Z")

	}) 


({

		"pais": {
		"nome": "india",
		"populacao": "1.366.417.756",
		"indice": " segundo Pais mais populoso"

		},

		"covid": {
		"contaminados": "314.000",
		"mortes": "421.000",
		},
                
                 "vacinacao": {
		"vacinados": "95.000",
		"recuperados": "30.000",
		
		"dataHora": ISODate ("2021-07-2 T10: 00: 00Z")

	}) 

 
 # no prompt de comando entrar no caminho abaixo : 
/c/Program Files/MongoDB/Server/5.0/bin 

 # para executar os comandos:
 no terminal dentro da pasta bin digitamos mongod e deixamos esse servidor rodando para executarmosos os demais passos . 

abrimos outro terminal entramos no caminho /c/Program Files/MongoDB/Server/5.0/bin aqui teclamos mongo. feito isso vamos começar a trabalhar como mongo

vamos criar uma " coleção " chamada * Paises * para armazenar informações, com o comando  o comando `db.createCollection ('paises')` 
para deletá-la usamos o comando `db.paises.drop ()` 

##  Inserindo documentos na coleção

no robo 3t vamos vamos cris nossas consultas na coleção ' paises '
 dar dois cliques na coleção `paises` no Robo 3T. Feito isso ele já vai abrir o comando `db.getCollection ('paises'). Find ({})` para visualizar tudo o que contém nessa coleção:
 vamos inserir documento clicando com o botão direito em ' inserir documento'
 ira abrir uma tela e inserimos nosso json.
 
rodando o  comando `db.getCollection ('paises'). Find ({})` no Robo 3T e o mesmo irá listar o documento que criamos:
e assim podemos excutar os comandos .


