# Tarefas-pw
##Descrição do Projeto
Repositório destinado à realização de tarefas e trabalhos da matéria de Programação Web

##Passo a Passo para construção e edição do projeto

	###1º - Clonar o repositório em sua máquina local através do comando:
		    `git clone https://github.com/HitalloFlavyo/tarefas-pw`


	###2º - Nesse momento, o projeto já está em sua máquina. Sendo assim, você já pode fazer alterações no mesmo.

##Passo a Passo para execução do projeto	

	###1º - Clonar o repositório em sua máquina local através do comando:
			`git clone https://github.com/HitalloFlavyo/tarefas-pw`

	###2º - Embutir o Maven no Projeto através do comando:
			'mvn io.takari:maven:0.3.3:wrapper -Dmaven=3.3.9'
	
	###3º - Empacotar a aplicação através do comando:
			'mvnw package'
	
	###4º - Rodar o plugin do Tomcat que se encontra dentro do Maven através do comando:
			'mvnw org.apache.tomcat.maven:tomcat7-maven-plugin:run'
			
	###5º - Para poder ter acesso à aplicação, basta digitar no navegador:
			'http://localhost:8080/tarefas-pw/'