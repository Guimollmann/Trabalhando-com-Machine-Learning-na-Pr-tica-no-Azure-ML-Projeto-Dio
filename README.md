# Trabalhando-com-Machine-Learning-na-Pratica-no-Azure-ML-Projeto-Dio

## Segue abaixo principais instruções para a criação 
# Primeiramente foi necessário criar um recurso de Machine Learning.
    • Clicar em CRIAR RECURSO ( botão +) e depois pesquisar por Azure Machine Learning no chamado marketplace. Após encontrar o recurso, criar.
    • Na aba NOÇÕES BÁSICAS, DETALHE DE RECURSOS, é  necessário informar a assinatura para cobrança (campo Assinatura ) e  informar o GRUPO DE RECURSOS que  englobarão o recurso.
    • Em DETALHES DA ÁREA DE TRABALHO, informar os detalhes do workspace que será criado: Nome, Região e Conta de Armazenamento. Para finalizar clicar Consultar + criar. Após a 
     aprovação, clicar em CRIAR.
    • Após o recurso ser criado, clicar em IR PARA O RECURSO para acessar a página do recurso. 
    • Nessa página, clicar em INICIAR O ESTÚDIO que redirecionará para o estúdio do Azure Machine Learning. 
# Na criação do modelo deve-se seguir os seguintes passos:
    • Acessar a opção menu ML AUTOMATIZADO e após clicar em NOVO TRABALHO DE ML AUTOMATIZADO.
    • Nas  Configurações básicas preencher: Nome do trabalho, Novo nome do experimento e Descrição". Clicar em AVANÇAR.
    • Em Tipo de tarefa e dados, selecionar o tipo REGRESSÃOe em seguida, em Selecionar dados clicar em CRIAR.
    • Após aberto em Tipos de dados preencher os campos  Nome, Descrição e Tipo ( tabular ).
    • Clicar em AVANÇAR.
    • Em Fonte de dados  escolher o botão  De arquivos da Web
    • Clicar em AVANÇAR.
    • No quesito  URL da Web informar a URL desejada, neste caso a utilização foi feito [site]( https://aka.ms/bike-rentals)
    • Em quesito configurações preencher  as configurações do conjunto avançar para Esquema. Verificar os dados criados
    • Verificar as configurações criadas e clicar em CRIAR.
    • No quesito Configurações de tarefas a escolha foi pôr o  conjunto de dados importado.
    • Em  Coluna de destino selecionar a coluna rentals e  target.
    • Nos campos de Limite preenchi os valores com os seguintes dados : Máximo de avaliações (3), Máximo de avaliações simultâneas (3),  Máximo de nós(3), Limite de pontuações da me ´ 
    trica(0,085), Tempo limite do experimento(minutos)(15) 
    • Flegar em Habilitar encerramento antecipado.  
    • Clicar em AVANÇAR.
    • Nos quesitos Validar e testar e Tipo de validação a escolha foi  Divisão de validação de treinamento.
    • No icone  Computação, manter os valores que se apresentaram.
    • Clicar em Enviar trabalho de treinamento.
    • Para criação de modelo foi necessário clicar em Modelo de registro, manter as opções padrões para Selecionar saída.
    • No quesito  Configurações do modelo, preencher: Nome e versão
    • Clicar em CRIAR O MODELO.
  ##  Acessandoo o teste de modelo
    • Para visualização clicar  ícone no lado esquerdo escrito Tarefas (Jobs), clicar no link ir  em informado em Criado por trabalho e acessar a aba METRICAS.
    • Na página TESTE DE MODELO acessar os seguintes itens:
    • Acessar a aba  Pontos de extremidade e clicar em CRIAR.
    • Clicar em SELECIONAR alterar a Contagem de instancias  para  valor 1.
    • IMPLANTAR
            
  Após a implantação acessar a aba Testar.

  
 ## Para o teste realizado se obteve o json abaixo:



  ## A previsão gerada foi:

