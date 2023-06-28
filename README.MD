### Automação de Envio de Mensagem

Essa automação em Python foi desenvolvida para simplificar o processo de leitura de uma planilha e enviar mensagens automáticas com base nas informações fornecidas. A interface gráfica foi criada utilizando a biblioteca tkinter, proporcionando uma experiência amigável ao usuário.

Ao iniciar a automação, o usuário é solicitado a inserir o nome do funcionário e a situação do pagamento desejada nos campos fornecidos. Essas informações serão utilizadas posteriormente para personalizar as mensagens a serem enviadas.

Após inserir os dados e clicar no botão "Enviar", a automação começa a trabalhar nos bastidores. Primeiramente, a biblioteca pandas é utilizada para carregar a planilha ('Cobrancas.xlsx'), fornecendo os dados necessários (nome, telefone, situação do pagamento e valor devido). Essas informaçções são fundamentais para personalizar a mensagem a ser enviada ao cliente.

No final, a automação atualiza a situação do pagamento na planilha para "Mensagem Enviada". Dessa forma, é possível manter um registro do status da comunicação com cada cliente.

Em resumo, essa automação em Python com tkinter e selenium simplifica o processo de leitura de planilha e envio de mensagens personalizadas. Ela oferece uma interface gráfica amigável e automatiza tarefas repetitivas, tornando o processo mais eficiente e produtivo.

<b>Principais Bibliotecas</p>
Tkinter
Pandas
Selenium
