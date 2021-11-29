# MonsterPark-Estacionamento

Projeto simples em JAVA com conexão ao Banco de Dados MySQL

Neste projeto temos as seguintes funcionalidades:

1º Cadastro de Cliente
2º Cadastro de Veiculos
3º Cadastro de Mensalistas
4º Cadastro de Empresas

No momento atual está um projeto simples, com interface grafica totalizando 6 Telas diferentes, sendo elas:
1 - Login
2- Opções do Sistema
3- Cadastros 
4- Novo Cadastro
5- Ocupação do Estacionamento
6- Controle de Vagas Ocupadas 

Futuramente pretendo realizar novas atualizações neste sistemas, no Back e no Front-End.


Explicando melhor cada tela que tenho neste sistema:

1- Login: Tela com uma verificação de Login basica realizada atraves de "IF" e "ELSE", sendo possivel realizar login como 'Administrados' e 'Cliente'. Com o login de 'ADM' tem acesso total a interface do sistema, sendo possivel realizar cadastros e finalizar o uso das vagas. Agora com o login de 'CLIENTE' é visivel apenas a tela de vagas para confirmação do veiculo cadastrado no sistema.

2- Opções do Sistema: Nesta tela é onde podemos visualizar as opções que o sistema entrega, sendo elas: Ocupações, Cliente/Empresa, Cadastrar Cliente/Empresa. E apenas para complementar um icone direcionando diretamente para as vagas ocupadas, e um icone de saida do sistema.

3- Ocupação: Essa tela nos permite realizar a reserva da vaga que possuimos no estacionamento,onde temos que cadastrar uma serie de dados para permitir o cadastro em nosso sitemas como os seguintes dados: Nome do Proprietario, Placa do Veiculo, Chassi, Registro do Veiculo, Tipo de Veiculo e Vaga desejada. Ao fim do preenchimento de todos esses dados não sendo possivel deixar nada em branco, temos os icones de 'Ocupar Vaga", onde será registrado no sistema a ocupação da vaga, novamente o icone de vagas ocupadas no estacionamento e um icone para 'Voltar'

4-Cadastrar Cliente/Empresa: Tela que realizamos os cadastros sejam eles de cliente ou empresas, cadastro totalmente de forma simples sendo necessario preencher todos os dados, não podendo deixar campos em branco, apos a conclusão do cadastro os dados vão para o banco de daods que está relacionado ao sistema, e vão para a tela de clientes ja cadastrados, podendo verificar todas as informações que foram digitadas anteriormente.

5- Clientes/ Empresa: Com essa tela, podemos visualizar todos os cliente ou empresas que temos cadastrado no sistema, sejam eles, Clientes, Empresas ou até mesmo se é ou não Mensalista, contendo dados basicos de cadastro como: nome, telefone, endereço, veiculo, placa, menslista ou não.

6- Vagas: Tela que visualizamos todos os veiculos cadastrados nas vagas do estacionamento, sendo possivel confirmar os seguintes dados: proprietario, placa, chassi, registro, modelo e vaga utilizada.
