# JD CRED Assistente Virtual com LLaMA 4
 Este repositório contém a estrutura para integrar o modelo LLaMA 4 da Together AI como
 assistente de atendimento para a JD CRED.
 ## Objetivo
 Automatizar o atendimento inicial via WhatsApp (ou outro canal) usando o modelo LLaMA 4, com
 exemplos reais de interações para aperfeiçoamento contínuo.
 ## Estrutura- `/dataset`: Contém os exemplos reais de atendimento usados para treinar o modelo.- `/scripts`: Scripts Python para carregar, formatar e enviar os dados para o modelo.- `main.py`: Ponto de entrada do projeto para teste e execução.- `.env`: Arquivo com variáveis de ambiente (como API key da TogetherAI).- `.gitignore`: Arquivo para evitar versionamento de pastas e arquivos sensíveis.
 ## Requisitos- Python 3.10+- Conta na Together AI (https://www.together.ai/)- Biblioteca `llama-stack-client`
 ## Como usar
 1. Clone o repositório
 2. Crie e ative um ambiente virtual
 3. Instale as dependências com `pip install -r requirements.txt`
4. Adicione sua API key da TogetherAI no arquivo `.env`
 5. Execute `python main.py` para fazer um teste com o modelo
 ## Treinamento Contínuo
 Periodicamente, novos exemplos reais de atendimento devem ser adicionados ao diretório
 `/dataset`. O script de atualização irá consolidar os dados e reconfigurar o prompt para afinar o
 comportamento do assistente.
 ## Licença
 Uso interno para JD CRED - todos os direitos reservados
