#Target #Solution

3 different independent layers


![Target](./Arquitetura_Alvo.png)



Description: (EN)
Basically we have a first layer (VIEW), which connects to a layer of Controller (API), which connects to a third layer (API) that the latter will connect to databases, external APIs, etc. There are 3 independent projects, 1 View and 2 APIs. But the only peculiarity among the solutions is that in addition to a REST API communication between the layers that is the most common that we see on the internet, we will need in some cases, communication Via Socket.io, either between the APIs or between the View layer and the API, allowing that, if information is changed in the database, this information is updated in the View without the need of refresh or request by the browser.


Descrição: (PT)
Basicamente temos uma primeira camada (VIEW), que se conecta a uma camada de Controller (API), que se conecta a uma terceira camada (API) que esta última sim, fará a conexão com as bases de dados, APIs externas, etc. São 3 projetos independentes, sendo 1 View e 2 APIs. Porém a única particularidade entre as soluções, é que além de uma comunicação REST API entre as camadas que é o mais comum que vemos na internet, é que precisaremos em alguns casos, a comunicação via Socket.io, seja entre as APIs ou entre a camada View e a API, permitindo que, caso uma informação seja alterada na base de dados, esta informação seja atualizada na View sem a necessidade de refresh ou requisição pelo browser.