Essa automação em Python foi desenvolvida para simplificar o processo de leitura de uma planilha e enviar mensagens automáticas com base nas informações fornecidas. A interface gráfica foi criada utilizando a biblioteca tkinter, proporcionando uma experiência amigável ao usuário.

Ao iniciar a automação, o usuário é solicitado a inserir o nome do funcionário e a situação do pagamento desejada nos campos fornecidos. Essas informações serão utilizadas posteriormente para personalizar as mensagens a serem enviadas.

Após inserir os dados e clicar no botão "Enviar", a automação começa a trabalhar nos bastidores. Primeiramente, a biblioteca pandas é utilizada para carregar a planilha, fornecendo o caminho do arquivo Excel contendo os dados necessários.

Com a planilha carregada, a automação procura o valor devido com base no nome fornecido pelo usuário. Essa informação é fundamental para personalizar a mensagem a ser enviada ao funcionário.

Em seguida, a automação atualiza a situação do pagamento na planilha para "Mensagem Enviada". Dessa forma, é possível manter um registro do status da comunicação com cada cliente.

Após atualizar a planilha, a automação utiliza a biblioteca selenium para automatizar o processo de envio das mensagens. O navegador é aberto e a URL do serviço de mensagens é acessada (o usuário deve substituir pela URL do serviço que está utilizando).

A automação localiza o campo de pesquisa na página e insere o nome do funcionário fornecido anteriormente. Em seguida, o campo de mensagem é encontrado e preenchido com a mensagem personalizada, incluindo o nome do funcionário e o valor devido.

É importante ressaltar que o código fornecido é apenas um exemplo básico e precisa ser adaptado de acordo com o serviço de mensagens utilizado. É necessário adicionar o código necessário para enviar a mensagem através do serviço específico.

Após o envio da mensagem, o navegador é fechado e uma mensagem de sucesso é exibida na interface gráfica, informando ao usuário que a mensagem foi enviada com êxito.

Em resumo, essa automação em Python com tkinter e selenium simplifica o processo de leitura de planilha e envio de mensagens personalizadas. Ela oferece uma interface gráfica amigável e automatiza tarefas repetitivas, tornando o processo mais eficiente e produtivo.
