# prototipo
Repositório destinado a ser um protótipo de conceitos do Sistema de Gestão da Sincronos em Visual Studio C#. 

Desenvolveremos um sistema de controle de chamados buscando utilizar todos os conceitos de arquitetura e termos condições de realizar experimentos em um ambiente voltado ao aprendizado.

Versão Beta

Objetivo: Sistema de Gestão de Chamados - Controlar o suporte da Tetra Soluções.

Arquitetura do sistema:
	- Banco de Dados Postgre rodando no Azzure
	- Projeto Visual Studio / C# - organizado em camadas MVC
	- Prepara procedimentos com cobertura de Testes
	- O projeto vai ser organizado para trabalhar com Biblioteca de Classes Portáteis visando um CORE, um projeto ASP.Net, Desktop e Mobile. Compartilhando métodos do Core.
	- Engine de Relatórios Crystal Reports

Metodologia e Ferramentas de trabalho:
	- GIT - Tudo será versionado através de um ou mais repositórios GIT.
	- Engine de Relatório - Crystal Reports
	- IDE: Visual Studio
	- Banco de Dados: Postgre
	- Servidor WEB - Azzure

Recursos do Sistema: 

	- Estrutura -
		* CRUD de Usuários
		* Login de Usuários
		* CRUD Grupo de Usuários
		* Tela de config

	- Cadastros -
		* CRUD de Clientes;
		* CRUD de Técnicos;
		* CRUD de Classificação de Problemas;

	- Controle de Chamados -
		* Abrir chamado
		* Atribuir chamado
		* Finalizar/Cancelar/Tranferir Chamado
		* Manter Histórico de Atendimento por Técnico no chamado
		* Enviar fechamento de chamado por e-mail
		* Possibilidade imprimir comprovande do chamado
		* Regra de negócio

	- Relatórios
		* Chamados por período
		* Chamados por Técnico
		* Listagem de Clientes
		* Análise de Chamados por cliente
		* Análise de Chamados pro Problema (Gráfico)

	- Base de Conhecimento
		* Publicar o procedimento
		* Autorizar a publicação (Gerente)
		* Imprimir procedimento
		* Enviar procedimento por e-mail
