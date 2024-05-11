# Contador de histórias infantis usando o Gemini

Esse projeto python tem como objetivo gerar estórias infantis e transformá-las em áudio para que possam ser ouvidas pelas crianças, tudo isso utilizando a inteligência artificial Gemini. 

# Funcionamento Básico
- Usuário opta por usar o tema do dia, pedir ao Gemini que sugira um tema ou ele mesmo informar o tema que deseja para a estória;
- É gerado randomicamente um gênero para a estória, a partir de um rol fixo de gêneros;
- Um prompt é gerado ao Gemini, usando critérios de segurança do conteúdo elevados, pedindo que gere a estória infantil conforme o tema e o gênero (com final feliz);
- Essa estória é exibida e, também, é gerado/executado um áudio (utilizando a lib gTTS) com a leitura da estória.

# Próximos passos possíveis
- Aperfeiçoar o prompt;
- Buscar uma voz mais amigável para leitura da estória (mais calma e sutil);
- Integração com aplicativo de celular.
