<!DOCTYPE html>
<html>
<head>
	<h1>README</h1>
</head>
<body>
	<h1>Este projeto foi desenvolvido utilizando as seguintes tecnologias:</h1>
	<ul>
		<li>Django Rest Framework</li>
		<li>Modelos, Admin e Serializers do Django</li>
		<li>Viewset, Urls e requisições GET e POST</li>
		<li>ListAPIView e Autenticação</li>
	</ul>
less
Copy code
<h2>Instalação</h2>
<p>Para instalar o Django Rest Framework, utilize o seguinte comando:</p>
<code>pip install djangorestframework</code>

<h2>Configuração</h2>
<p>Após a instalação, adicione o Django Rest Framework ao seu projeto, adicionando-o à lista de aplicativos em seu arquivo settings.py:</p>
<pre>
INSTALLED_APPS = [
# ...
'rest_framework',
# ...
]
</pre>

css
Copy code
<h2>Modelos, Admin e Serializers</h2>
<p>Neste projeto, foram utilizados modelos do Django para definir a estrutura dos dados a serem manipulados. A interface de administração padrão do Django foi utilizada para gerenciar esses dados. Além disso, foram criados Serializers para garantir a integridade dos dados na manipulação via API.</p>

<h2>Viewset, Urls e requisições GET e POST</h2>
<p>A API foi construída utilizando Viewsets para lidar com as operações CRUD (Create, Read, Update, Delete) em um modelo específico. Foram criadas rotas no arquivo urls.py para cada operação, utilizando as requisições HTTP GET e POST.</p>

<h2>Atualizando e deletando recursos</h2>
<p>A API também permite a atualização e exclusão de recursos específicos, utilizando as requisições HTTP PUT e DELETE. Essas operações foram definidas nos métodos update e destroy dos Viewsets.</p>

<h2>ListAPIView e Autenticação</h2>
<p>Para obter uma lista de recursos, foi utilizado o ListAPIView do Django Rest Framework, que permite a exibição de uma lista de objetos a partir de um modelo específico. Além disso, a API também conta com autenticação, garantindo que apenas usuários autorizados possam realizar operações na API.</p>

<h2>Conclusão</h2>
<p>Este projeto demonstra o uso do Django Rest Framework para criar uma API completa, com todas as operações CRUD disponíveis, além de autenticação e autorização. O uso de Viewsets, Serializers e ListAPIView torna a construção de uma API rápida e eficiente, permitindo que os desenvolvedores se concentrem no desenvolvimento de recursos mais complexos para a aplicação.</p>
</body>
</html>
