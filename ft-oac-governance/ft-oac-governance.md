# Atividades Administrativas

## Introdução

Neste Lab você vai aprender a gerenciar a solução Oracle Analytics Cloud.

[Oracle Video Hub video scaled to Large size](videohub:1_k00wf9ol:large)

*Este Lab só pode ser realizado por usuários que possuam o perfil de Administrador dentro do Oracle Analytics Cloud.*

*Tempo estimado para o Lab:* 30 Minutos

### Objetivos

* 
* 
* Customizar uma url customizada de acesso a solução

## Tarefa 1: Acessar Cache e Sessões Abertas

1.	Na página inicial, clique no hambúrguer na lateral esquerda e, em seguida, clique em **"Console"**.

![acesse o menu de administração da solução](./images/1-acesso_snapshot.png)

2.	Buscar o botão **"Cache e Sessões Abertas"** e clicar nele.

![acesse Cache e Sessões Abertas](./images/2-botao_cache.png)

3.  Navegue pela página e analise as consultas que estão sendo realizadas.

![analise Cache e Sessões Abertas](./images/3-cache.png)



## Tarefa 2: Ativar Opção Desenvolvedor

Nessa Task iremos ativar a funcionalidade de Desenvolvedor no Oracle Analytics Cloud.

1.	Na página inicial, clique nas iniciais do usuário na lateral direita e, em seguida, clique em **"Perfil"**.

![acesse o perfil](./images/4-perfil.png)

2.	Entrar na aba **"Avançado"** e ativar o botão **"Ativar opções Desenvolvedor"** e clicar em **"Salvar"**.

![ative a opção desenvolvedor](./images/5-developer.png)

3.  Acesse uma pasta de trabalho no modo edição, clique no botão dos **"3 pontinhos"** do lado direito superios, selecione **"Desenvolvedor"**.

![acesse a funcionalidade desenvolvedor dentro de uma pasta de trabalho](./images/6-developer2.png)

4.  Analise os tempos envolvendo a renderização das visualizações na aba **"Resumo"**, na aba **"SQL Lógico"** pode ver qual SQL está sendo utilizada para cada visualização.

![analise a os dados fornecidos na funcionalidade desenvolvedor](./images/7-developer3.png)



## Tarefa 3: Customização de url de acesso ao Oracle Analytics Cloud (Opcional)

Nessa Task iremos personalizar a url de acesso ao Oracle Analytics Cloud. Porém, para esse caso, é necessário possuir um certificado X.509 com extensão .pem, .cer ou .crt para que seja possível utilizar o domínio desejado na url.

1.	Na console inicial do Oracle Cloud Infrastructure, dentro da tela do Oracle Analytics Cloud, após URL Personalizado, clicar em **"Criar"**.

![dentro da console do OCI, acesse o botão criar](./images/11-criar_urlpersonalizado.png)

2.	Na nova tela, digitar o nome do host desejado para a url, incluir o certificado X.509 com o domínio a ser utilizado, incluir uma chave privada no formato .pem ou .key e clicar em **"Criar"**.

![preencher as informações necessárias e clicar em criar](./images/12-inclusao_informacoescertificado.png)

3. A instância será atualizada, portanto, ficará indisponível por alguns minutos, em seguida voltará a ficar disponível quando o símbolo do OAC voltar a ficar na cor verde.

![atualização OAC](./images/13-disponibilidade_oac.png)


## Tarefa 4: Usage Tracking e DV Governance (Opcional)

1.	Para criação de Usage Tracking, tem o passo a passo na seguinte documentação [Usage Tracking com o Semantic Modeler](https://docs.oracle.com/en/cloud/paas/analytics-cloud/acabi/track-usage.html#GUID-F7298880-BE4A-457B-AE24-5DB889848FCC).

2.	Pode criar dashboards para acompanhar as análises. Entender quando está tempo maior volume de acesso e em quais dashboards, quais as consultas com os piores tempo, quem acessa com maior frequência, entro outras análises.

![dashboard usage tracking](./images/8-usagetracking.png)

3.  Agora para o DV Governance, será necessário o Plugin DV Governance da Biblioteca de Extensões e realizar a Tarefa 3 do Laboratório de Atividades Administrativas. [Oracle DV Governence - vídeo](https://www.youtube.com/watch?v=QWi06ivvcDI)

![analise Cache e Sessões Abertas](./images/9-dvgov.png)

4.  A partir dos dados fornecidos pelo plugin, pode se criar dashboards para realizar as análises de governança dos Dashboards, entender quais conjuntos de dados não estão sendo utilizados, quantas pastas de trabalhos existem e quais dados estão utilizando.

![analise Cache e Sessões Abertas](./images/10-dvgov1.png)
![analise Cache e Sessões Abertas](./images/10-dvgov2.png)





Parabéns, você terminou esse laboratório!
Você pode **seguir para o próximo Lab**.

## Conclusão

Nesta sessão você aprendeu a realizar tarefas de gerenciamento do Oracle Analytics Cloud, desde definir a permissão de usuários, realizar backups, customizar a url de acesso a solução e verificar a performance de utilização da solução.

## Autoria

- **Autores** - Gabriela Miyazima
- **Último Updated Por/Data** - Gabriela Miyazima, Agosto/2024