# NLW-UNITE-04-2024-
Projeto feito em três aulas para estudar HTML, CSS e JavaScript 

Então, este é um projeto bem legal onde basicamente temos uma tela onde as pessoas podem se inscrever. Você sabe quando você quer ir a um evento e precisa se registrar com seu nome e e-mail? É isso que as pessoas podem fazer aqui.

Para esse projetinho foi usado:

HTML, que é tipo uma linguagem de marcação de hipertexto. 
O CSS é para deixar tudo bonitinho, com cores, formatos legais e na posição certa. 
E o JavaScript que é a parte mais inteligente que faz os botões funcionarem e guarda as informações que as pessoas escrevem.
Também usamos uma biblioteca chamada Day.js para ajudar a lidar com as datas e horas, assim, sabemos quando as pessoas se inscreveram e quando fizeram check-in de melhor maneira.

Estrutura do HTML:
No HTML, a gente tem várias tags que formam a página. Tem uma parte para o cabeçalho (header), onde a gente coloca um ícone. Depois, tem um formulário onde as pessoas podem se inscrever, com espaço para nome e e-mail. Mais abaixo, tem uma seção onde a lista de participantes é mostrada.

Estilização com CSS:
Com o CSS, a gente deixa tudo bonitinho. Colocamos fundos, cores e formatos legais nos botões, nos campos de texto e na lista de participantes. Isso deixa o site mais atraente visualmente.

Interatividade com JavaScript:
Ele fez os botões funcionarem e guarda as informações que as pessoas escrevem. Por exemplo, quando alguém clica no botão de se inscrever, o JavaScript pega as informações do formulário e adiciona na lista de participantes.

Algumas funcionalidades importantes de serem citadas:

Função criarNovoParticipante
Esta função recebe um objeto representando um participante e retorna uma string formatada com as informações desse participante para ser adicionada à lista na página. Ela cria uma linha na tabela com o nome, e-mail, data de inscrição e botão para fazer check-in.

Função atualizarLista
Essa função recebe uma lista de participantes e atualiza a lista na página com esses participantes. Ela percorre a lista e utiliza a função criarNovoParticipante para criar uma representação em HTML de cada participante, e então atualiza o conteúdo da tabela na página com essas representações.

Função adicionarParticipante
Quando alguém preenche o formulário de inscrição e envia, esta função é chamada. Ela pega os dados do formulário, cria um objeto representando o novo participante e o adiciona à lista de participantes. Antes de adicionar, verifica se o e-mail já foi cadastrado para evitar que acabe registrado duas vezes.

Função fazerCheckIn
Quando alguém clica no botão de fazer check-in, esta função é chamada. Ela confirma com o usuário se ele realmente deseja fazer o check-in e, se confirmado, encontra o participante correspondente na lista e atualiza a data de check-in desse participante.

Creio que esse seja um bom resumo do projeto.

