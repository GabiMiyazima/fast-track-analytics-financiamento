# Apresentar e Exportar os Dashboards

## Introdução

Neste Lab você vai aprender a utilizar o modo de apresentação do Oracle Analytics Cloud e vai aprender a exportar seus dashboards podendo escolher entre os formatos oferecidos pela ferramenta.

[Oracle Video Hub video scaled to Large size](videohub:1_k7t0njfr:large)

*Tempo estimado para o Lab:* 15 Minutos

### Objetivos
* Configurar o modo de apresentação
* Ocultar gráfico no modo de apresentação
* Exportar o dashboard em PDF e em DVA (formato nativo do OAC)


## Tarefa 1: Apresentar Dashboards

A última etapa na construção das nossas visualizações é a configuração do modo de apresentação, a definição de como cada Tela será disponibilizada para o usuário que vai apenas consumir os dashboards e não fará nenhum tipo de alteração.

O Oracle Analytics Cloud oferece uma área dedicada para essa etapa, na aba Apresentar:

![Aba Apresentar](./images/present-1.png)

Nessa aba você verá todas as tela criadas no modo de edição (na aba Visualizar).

![Aba Apresentar](./images/present-2.png)

Teremos opções diferentes em cada aba, desde definir qual dos gráficos estarão visíveis até o estilo de navegação entre as telas;

1.	No menu a esquerda, é possível encontrar as opções de configuração **Pasta de Trabalho** e **Tela Ativa**. Sua primeira missão é explorar essas opções e se familiarizar com as duas abas.


![Opções de configuração da apresentação](./images/present-3.png)

![Opções de configuração da apresentação](./images/present-4.png)

Agora que você está familiarizado com as opções de configuração de apresentação, vamos escolher as telas da nossa apresentação.

2.	Selecione a tela **Explicar Produto** e clique na seta que ira abrir as opções; Essa é uma tela que **NÃO** iremos apresentar no projeto final, por isso, selecione a opção **Ocultar Tela**. Faça o mesmo para a tela **Autoinsights**;

![Ocultar Telas](./images/present-5.png)

Dessa forma, teremos em nosso projeto a apresentação das telas **Geral**, **Contratos**, **Avançado**, **Detalhe** e **Explicar Estado Civil**. 


Agora vamos alterar a forma como as telas serão exibidas durante nossa apresentação. Podemos alterar o estilo do **Navegador de Histórias** e escolher entre essas 4 opções: **Guia Inferiores (Padrão)**, **Principais Guias**, **Barra de Navegação**, **Tira de Filme** ou **Nenhum**.

4.	Na aba **Pasta de Trabalho**, localize a opção **Navegação na Tela – Estilo**. Clique na opção **Barra de Navegação**.

![Estilo de Apresentação](./images/present-7.png)

A opção "Barra de Navegação" adiciona pontinhos representando cada uma das suas telas. Ela é bem discreta e muito útil para manter o foco da apresentação na tela atual.

Vamos salvar nossas modificações e visualizar como ficou nossa apresentação.

5.	Clique no **ícone de disquete** no canto superior direito para salvar e após a mensagem de confirmação clique no ícone de **Play**.

![Salve as edições e clique em Play](./images/present-8.png)

Observe que:
* A Barra de Navegação indicada abaixo na imagem

![Vizualização Final](./images/present-9.png)

Agora explore as outras telas através da Barra de Navegação.

## Tarefa 2: Exportar Dashboards

O Oracle Analytics Cloud (OAC) oferece algumas opções para exportação dos nossos Dashboards ou de um gráfico específico. Temos a possibilidade de exportar o arquivo, de imprimir e até [enviar por e-mail*](https://docs.oracle.com/en/cloud/paas/analytics-cloud/acabi/send-email-reports-and-track-deliveries.html#GUID-C5815E71-9348-4C13-BAB6-B5B0C887B3D6). Além disso, a plataforma oferece a opção de Copiar Link ou scanear um QR Code.

Para a exportar o arquivo temos diversões formatos disponíveis: PowerPoint(pptx), Acrobat(pdf), Imagem(png), Dados (csv) e Pacote(dva) formato nativo do OAC.

Vamos exportar nosso dashboard em PDF para ser compartilhado de forma mais simples com usuários que não tem acesso ao OAC.

1. Na aba Visualizar, clique no botão de "Exportar" no canto superior direito da tela e selecione a opção "Arquivo".

![Selecione Exportar Arquivo](./images/present-11.png)

2. Preencha preencha os campos com as informação abaixo e em seguida clique em **Salvar**.

*Nome:* Dash Financiamento
*Formato:* Acrobat (pdf)
*Incluir:* Todas os Painéis de Controle
*Tamanho:* A4 (210 mm x 297 mm)
*Orientação:* Paisagem

![Informações para exportação](./images/present-12.png)

Uma janela vai aparecer mostrando o processamento dos gráficos e você poderá acompanhar o processo através dela.

![Processando a página 1 de 6](./images/present-13.png)

Quando o processamento terminar o download automático do arquivo vai iniciar, basta verifica nas opções de download do seu navegador.

O resultado final deve similar ao abaixo:

![Resultado da exportação](./images/present-20.png)
![Resultado da exportação](./images/present-21.png)
![Resultado da exportação](./images/present-22.png)
![Resultado da exportação](./images/present-23.png)
![Resultado da exportação](./images/present-24.png)
![Resultado da exportação](./images/present-25.png)


Agora vamos exportar o nosso dashboard no formato .DVA que é o formato nativo do Oracle Analytics Cloud (OAC). Como esse tipo de arquivo você pode fazer importação de dashboard em outras instâncias do OAc ou manter essa arquivo salvo como um Backup.

3. Acesse "Exportar" e selecione "Arquivo".

![Selecione Exportar Arquivo](./images/present-11.png)

4. Dessa vez vamos mudar o formato de exportação para Pacote (dva) e será necessário adicionar uma senha para a exportação. (Essa senha  será necessária caso você for importar o arquivo)

*Nome:* Imersão Oracle Analytics
*Formato:* Pacote (dva)
*Incluir Dados* - MANTER HABILITADO
*Incluir Credenciais de Conexão* - DESABILITAR
*Proteger Senha:* Colocar uma senha

![Exportar Arquivo DVA](./images/present-15.png)

Uma janela vai aparecer mostrando o processo de exportação

![Janela de Exportação](./images/present-16.png)

Quando o processamento terminar o download automático do arquivo vai iniciar, basta verifica nas opções de download do seu navegador e buscar um arquivo com a extensão **.dva**.

Você pode utilizar o arquivo que acabou de baixar com todos os gráfico e configurações que você fez nos dados para importar em qualquer instancia do OAC sem a necessidade de ter que refazer todo o processo.

Parabéns, você terminou esse laboratório!
Você pode **seguir para o próximo Lab**.

## Saiba Mais

[Configurar envio de dashboards por e-mail](https://docs.oracle.com/en/cloud/paas/analytics-cloud/acabi/set-email-server-deliver-reports.html).
[Agendar o envio automático de dashboards por e-mail](https://docs.oracle.com/en/cloud/paas/analytics-cloud/acabi/send-email-reports-and-track-deliveries.html#GUID-49732584-010B-444F-84C6-37FABF533642).
[Importar um arquivo DVA](https://docs.oracle.com/en/middleware/bi/analytics-desktop/bidvd/import-workbook-file.html).

## Conclusão

Nesta sessão você aprendeu a configurar o modo de apresentação e aprendeu a exportar seus dashboards em dois formatos de arquivos diferentes PDF e DVA.

## Autoria

- **Autores** - Isabelle Dias, Gabriela Miyazima
- **Último Updated Por/Data** - Gabriela Miyazima, Agosto/2024