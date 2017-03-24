O projeto monitoramento-rmi-base terá as classes que serão implementadas tanto pelo servidor quanto pelo cliente e também uma class que configura o acesso ao servidor rmi na criação do mesmo.

O projeto monitoramento-rmi-server terá a classe que cria a conexão e também a classe que implementa a interface do projeto monitoramento-rmi-base e o método main que inicializa o servidor.

O projeto monitoramento-rmi-client terá a classe que inicializará o projeto class main.

Pra que os projetos monitoramento-rmi-server e monitoramento-rmi-client consigam acessar as classes do monitoramento-rmi-base, uma configuração deverá ser feita: adicionar ao build path do projeto monitoramento-rmi-server e monitoramento-rmi-client.

*como adicionar ao build path dos projetos:
	*clica com o lado direito no projeto monitoramento-rmi-server
	*file -> build path -> configure build path
	*aba projects -> add -> monitoramento-rmi-base -> ok
	*repete o procedimento para o projeto monitoramento-rmi-client