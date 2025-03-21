# Passo a Passo para Criar um Agente de Viagens no Copilot Studio

## 1. Criar uma Conta no Office 365 Copilot
- Acesse [Microsoft 365](https://www.microsoft.com/pt-br/microsoft-365).
- Inscreva-se para uma conta do Office 365 Copilot, garantindo que você tenha uma licença válida para o Microsoft 365 Copilot.
- Certifique-se de que sua conta tenha permissões administrativas para configurar o ambiente.

## 2. Configurar o Ambiente de Desenvolvedor no Power Platform
- Acesse o [Power Platform](https://powerplatform.microsoft.com/pt-br/).
- Crie um ambiente de desenvolvedor:
  - No menu principal, clique em **Administração** e selecione **Ambientes**.
  - Clique em **Novo Ambiente** e configure o nome, região e tipo (escolha "Desenvolvedor").
- Certifique-se de que o ambiente está vinculado à sua conta do Microsoft 365.

## 3. Criar uma Solução no Power Apps
- No Power Platform, acesse o [Power Apps](https://make.powerapps.com/).
- Clique em **Soluções** no menu lateral.
- Crie uma nova solução:
  - Nomeie a solução como "Agente de Viagens".
  - Escolha o ambiente configurado anteriormente.
- Salve e publique a solução.

## 4. Criar e Configurar um Agente no Copilot Studio

### 4.1. Agente Baseado em Modelo
- No Copilot Studio, selecione **Criar Agente**.
- Escolha a opção **Baseado em Modelo**.
- Configure:
  - Nome do agente: "Agente de Viagens".
  - Descrição: "Assistente para planejamento de viagens nacionais e internacionais".
  - Adicione origens de conhecimento, como SharePoint ou conectores do Microsoft Graph.

### 4.2. Agente Baseado em Descrição com IA
- No Copilot Studio, selecione **Criar Agente**.
- Escolha a opção **Baseado em Descrição**.
- Forneça uma descrição detalhada:
  - "Este agente ajuda os usuários a planejar viagens, oferecendo opções personalizadas com base no perfil do viajante, incluindo destino, orçamento, transporte e hospedagem."
- O Copilot Studio usará IA para gerar tópicos e fluxos de conversa automaticamente.
- Revise e ajuste os tópicos gerados.

### 4.3. Copiloto em Branco
- No Copilot Studio, selecione **Criar Agente**.
- Escolha a opção **Copiloto em Branco**.
- Configure manualmente:
  - Adicione tópicos e frases de gatilho.
  - Crie fluxos de conversa personalizados para atender às necessidades específicas de planejamento de viagens.

## 5. Testar e Publicar o Agente
- Use a funcionalidade de teste no Copilot Studio para simular interações com o agente.
- Ajuste os fluxos de conversa e respostas conforme necessário.
- Publique o agente e compartilhe-o com sua organização.
