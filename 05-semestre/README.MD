## 📝 5º Semestre 2023-1

<p align="justify">
Este projeto foi desenvolvido em parceria com a IACIT, uma empresa de tecnologia reconhecida por suas soluções inovadoras nos setores de defesa, segurança pública, controle de tráfego 
aéreo e meteorologia. 
</p>

<p align="justify">
Antes da implementação da aplicação, o Serviço de Atendimento ao Cliente (SAC) da empresa enfrentava diversos problemas relacionados à dispersão de informações. Os registros de 
ocorrência (ROs) chegavam por diferentes canais, como e-mail, telefone e formulários online, mas não havia uma centralização desses dados. Isso resultava em atrasos na resposta aos 
clientes, dificuldades para acompanhar o status das solicitações e uma experiência inconsistente para o usuário final. Além disso, os administradores tinham dificuldade em identificar e 
gerenciar pendências de forma eficiente, o que impactava negativamente a qualidade do atendimento. Diante desse cenário, o desafio do projeto foi criar uma aplicação híbrida e responsiva 
para centralizar o Serviço de Atendimento ao Cliente (SAC).
</p>

<p align="justify">
A solução proposta foi desenvolver uma aplicação capaz de consolidar e organizar esses ROs provenientes de diferentes canais de comunicação. A aplicação permite que os clientes criem e 
acompanhem suas solicitações, além de oferecer um chat para contato direto com os administradores, facilitando a comunicação. Do lado administrativo, a plataforma permite que os gestores 
recebam, atualizem o status das solicitações e acompanhem as pendências de forma centralizada. A aplicação, sendo híbrida e responsiva, garante uma experiência consistente tanto em 
dispositivos móveis quanto em desktop, otimizando o fluxo de trabalho e melhorando o atendimento ao cliente.
</p>

## 🚀 Demonstração da Plataforma

<p align="center">
  <img src="https://github.com/deborafaria01/TG-fatec/blob/main/Gifs/LoginAdmin.gif" width="90%">
</p>

[→ Link para o repositório do projeto no GitHub](https://github.com/deborafaria01/Reportify_Doc)

## 💻 Tecnologias Utilizadas
Ao longo do projeto, trabalhamos com as seguintes ferramentas:

#### Front-end
- **React Native**: Framework amplamente utilizado para o desenvolvimento de aplicativos móveis multiplataforma, permitindo a criação de interfaces nativas com o uso de componentes React 
e possibilitando o desenvolvimento de apps tanto para iOS quanto Android com uma única base de código.

#### Back-end
- **Javascript**: Linguagem de programação versátil utilizada no desenvolvimento do lado do servidor com Node.js, permitindo a criação de APIs e a manipulação eficiente de dados, além de 
integrar de forma ágil com o front-end e diferentes serviços.

#### Banco de Dados
- **MongoDB**: Banco de dados NoSQL orientado a documentos, ideal para lidar com grandes volumes de dados não estruturados, oferecendo alta escalabilidade e flexibilidade, facilitando o 
armazenamento e a recuperação de dados em tempo real.

## ✨ Contribuições Pessoais

<p align="justify">
Neste projeto, atuei como desenvolvedora front-end, utilizando React Native para construir a interface do aplicativo móvel que centraliza o atendimento ao cliente. Minha contribuição 
incluiu a implementação de componentes reutilizáveis, que garantiram consistência visual em todas as telas e facilitaram futuras manutenções.
Fui responsável pela integração do front-end com as APIs, enfrentando e solucionando problemas na exibição dos dados de Registros de Ocorrência (ROs). Trabalhei em colaboração com o time 
de back-end para corrigir inconsistências nos endpoints, garantindo que os dados fossem carregados e apresentados de maneira clara e organizada aos usuários.
Além disso, conduzi testes detalhados para identificar e corrigir problemas na interface em dispositivos móveis, como conflitos de layout em telas menores. Ajustei a renderização com 
media queries específicas e otimizações no CSS, assegurando uma experiência de usuário fluida e eficiente. Essas ações resultaram em uma aplicação robusta, funcional e alinhada às 
necessidades do cliente.
</p>

## 🛠️ Hard Skills
- **React Native**: Uso com ajuda.
- **Javascript**: Uso com autonomia.
- **MongoDB**: Uso com autonomia.

## 🌱 Soft Skills

- **Alinhamento Colaborativo**: Durante a última sprint, enfrentamos um problema inesperado na sincronização dos dados de atualização de status das ROs entre o front-end e o back-end, 
que estava impactando diretamente a experiência do cliente na área de acompanhamento. Por exemplo, os clientes não conseguiam visualizar em tempo real as mudanças no status de suas 
solicitações, devido a inconsistências nos endpoints de atualização da API. Para resolver a situação, organizei uma reunião emergencial com a equipe de back-end para revisar os logs de 
requisições e entender possíveis mudanças recentes na lógica do sistema. Identificamos que o problema estava relacionado a uma discrepância na formatação dos timestamps enviados pelo 
back-end. Após entender o contexto, ajustei o código do front-end para tratar corretamente os dados recebidos e, ao mesmo tempo, colaborei com o time de back-end para alinhar a 
formatação dos timestamps no endpoint. Essa abordagem coordenada permitiu que a funcionalidade fosse corrigida em menos de dois dias, garantindo que os clientes tivessem uma experiência 
consistente e melhorando a percepção geral sobre o sistema.
  
- **Habilidade de Diagnóstico e Solução**: Durante a fase de adaptação do aplicativo para dispositivos móveis, notei um problema específico na renderização do menu de navegação em 
smartphones com telas menores. O menu sobrepunha outros elementos, comprometendo a usabilidade. Investiguei a causa e percebi que o problema era decorrente de regras de CSS conflitantes 
no design responsivo. Propus uma abordagem usando media queries específicas e testei diferentes combinações para ajustar o layout conforme o tamanho da tela. Após implementar a solução, 
realizei testes em dispositivos reais, garantindo uma experiência consistente e fluida para os usuários. O ajuste foi concluído antes do prazo, sem comprometer outras 
entregas.

- **Integração e Refinamento de Funcionalidades**: Durante o desenvolvimento do sistema, enfrentei o desafio de estruturar e configurar as rotas de navegação para as páginas de cadastro 
e edição de usuários. As rotas existentes não estavam completas, o que limitava o acesso às funcionalidades. Para resolver, revisei e ajustei os arquivos de rotas (admin.routes.tsx e 
auth.routes.tsx), adicionando caminhos consistentes para páginas como CadastroUsuario e EditarUsuario. Paralelamente, implementei validações no front-end para campos obrigatórios, 
garantindo que os dados inseridos fossem consistentes antes de serem enviados à API. Além disso, integrei feedbacks visuais claros para erros e sucesso, utilizando react-toastify. Essas 
ações resultaram em um fluxo de navegação mais estável e em uma experiência de usuário otimizada, alinhada às necessidades do sistema.
