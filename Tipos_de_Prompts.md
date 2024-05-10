# Imersão Inteligência Artificial 2ª Edição
# DIA 3
LINKS:
- Galeria de prompts do Google AI Studio -> https://ai.google.dev/examples?hl=pt-br

OBJETIVOS:
 - Conhecer os 3 tipos de prompts do Google AI Studio: chat prompts, freeform prompts e structured prompts;
 - Explorar os parâmetros do Google AI Studio;
 - Conhecer mais sobre os tokens e PLN;
 - Iniciar o contato com Python pelo Google Colab.


## Exemplo 1 - Geração de Texto
  Através do prompt "Redatora de descrição de marketing", inseriu-se (INPUT) uma "imagem" e o alvo de audiência em "People / AI", tendo como saída (OUTPUT) um "texto de uma descrição de marketing".

#### Usando o prompt:
- Redatora de descrição de marketing

#### INPUT:
 - Imagem:
   ![image](https://github.com/area-41/Gemini/assets/87396846/77b02653-da01-4dec-9143-b8d6af61c642)
 - Target Audience:
   People / AI

#### OUTPUT:
  Aprenda sobre inteligência artificial e como aplicá-la em seus projetos. Com aulas ministradas por especialistas, você terá acesso a todo o conhecimento necessário para se tornar um profissional qualificado na área. Inscreva-se já! 

*IMAGEM DO OUTPUT*
![image](https://github.com/area-41/Gemini/assets/87396846/9147cb3d-94b4-4554-b1f8-a31dca10e97f)


## Exemplo 2 - Postagem do blog
  Através do prompt "Criador de postagem do blog", inseriu-se (INPUT) um texto dizendo o que deveria ser criado e uma "imagem", tendo como saída (OUTPUT) uma "postagem do blog".

#### Usando o prompt:
- Criador de postagem do blog
  
#### INPUT:
 - Texto:
    Escreva uma postagem de blog curta e envolvente com base nesta imagem. Deve incluir uma descrição do quadro na foto e falar sobre a preparação profissional e da importância das pessoas da minha viagem.

 - Imagem:
   ![image](https://github.com/area-41/Gemini/assets/87396846/77b02653-da01-4dec-9143-b8d6af61c642)
 

#### OUTPUT:
  Olá pessoal!

Estou muito animado para compartilhar com vocês a minha jornada de aprendizado em inteligência artificial. Como vocês sabem, a inteligência artificial é um campo em constante evolução, e estou ansioso para aprender o máximo que puder sobre ela.

Na semana passada, tive a oportunidade de participar de um curso intensivo de inteligência artificial na Alura. O curso foi ministrado por alguns dos principais especialistas em inteligência artificial do Brasil, e aprendi muito sobre os fundamentos da inteligência artificial, bem como sobre as últimas tendências no campo.

Estou muito grato pela oportunidade de ter participado deste curso, e estou ansioso para continuar aprendendo sobre inteligência artificial. Acredito que a inteligência artificial tem o potencial de revolucionar o mundo, e estou animado para fazer parte dessa revolução.

Além do curso, também estou participando de uma comunidade de estudos de inteligência artificial no Discord. A comunidade é formada por pessoas de todas as origens, e estamos todos interessados em aprender mais sobre inteligência artificial. Estamos nos reunindo regularmente para discutir artigos, compartilhar ideias e trabalhar em projetos.

Estou muito feliz por ter encontrado essa comunidade, e estou ansioso para aprender mais sobre inteligência artificial com eles. Acredito que a inteligência artificial é um campo muito importante, e estou animado para fazer parte dessa comunidade.

Se você está interessado em aprender mais sobre inteligência artificial, eu recomendo que você se junte a uma comunidade de estudos. Existem muitas comunidades online, e você certamente encontrará uma que seja adequada para você.

Obrigado por lerem!

*IMAGEM DO OUTPUT*
![image](https://github.com/area-41/Gemini/assets/87396846/8a84f044-9e6c-42e4-823d-00e9526733d7)



## Exemplo 3 - Listar itens da imagem
  Através do prompt "Listar itens com base na imagem", inseriu-se (INPUT) uma "imagem", tendo como saída (OUTPUT) uma "lista de ítens".

#### Usando o prompt:
- Listar itens com base na imagem
  
#### INPUT:
 - Imagem:
   ![image](https://github.com/area-41/Gemini/assets/87396846/77b02653-da01-4dec-9143-b8d6af61c642)
 

#### OUTPUT:
 - Lista:
      - 3 people
      - alura logo
      - aulas
      - calendario
      - grupos de estudos
      - imersao ia
      - manha
      - noite
      - tarde 



*IMAGEM DO OUTPUT*
![image](https://github.com/area-41/Gemini/assets/87396846/e8d1924b-f6d6-4692-8585-2c61150f4b8c)

----

## Exemplo Chat

Agora utilizando o "chat prompt" e definindo "Instruções de Sistema".

#### Usando o prompt:
- Chat Prompt
  
#### INPUT:
 - System Instructions:
   Você é um especialista em inteligência artificial
 

#### OUTPUT:

#### Estrutura de um sistema de automação de aprendizado de máquina para reciclagem
Este sistema visa melhorar a reciclagem através da educação e automatização, utilizando aprendizado de máquina e visão computacional.
##### Componentes principais:
- Identificação de materiais:
Visão computacional: Câmeras instaladas em pontos de coleta (lixeiras inteligentes, esteiras de triagem) capturam imagens do lixo.
Algoritmos de classificação de imagem: Modelos de deep learning, como redes neurais convolucionais (CNNs), são treinados para identificar diferentes tipos de materiais (plástico, papel, vidro, metal, orgânico) nas imagens.
Banco de dados de materiais: O sistema precisa de um banco de dados extenso com imagens de diferentes tipos de lixo para treinar os algoritmos de classificação.
- Educação e feedback:
Interface de usuário: Aplicativo móvel ou telas nas lixeiras inteligentes exibem informações sobre o material identificado e se ele foi descartado corretamente.
Feedback personalizado: O sistema rastreia o histórico de reciclagem do usuário e oferece feedback personalizado para melhorar seus hábitos de reciclagem.
Gamificação: Implementação de elementos de jogos como pontuações, níveis e recompensas para motivar os usuários a reciclar mais e melhor.
- Automação do processo:
Classificação automatizada: Com base na identificação dos materiais, o sistema direciona os resíduos para os recipientes corretos, utilizando esteiras e braços robóticos.
Compactação e armazenamento: O sistema otimiza o armazenamento dos resíduos, compactando os materiais e organizando-os de forma eficiente.
- Monitoramento e análise:
Painel de controle: Monitoramento em tempo real dos dados de reciclagem, como tipos e quantidades de materiais coletados, taxas de contaminação e desempenho do sistema.
Análise de dados: Utilização de técnicas de aprendizado de máquina para identificar padrões e tendências nos dados de reciclagem, permitindo otimizar o sistema e campanhas de conscientização.

##### Benefícios:
- Aumento das taxas de reciclagem: Identificação precisa dos materiais e feedback aos usuários reduzem a contaminação e melhoram a qualidade dos recicláveis.
- Eficiência operacional: Automação da classificação e compactação reduz custos e aumenta a produtividade.
- Educação e conscientização: Feedback personalizado e gamificação promovem mudanças de comportamento e maior engajamento na reciclagem.
- Dados valiosos: Análise de dados permite insights sobre hábitos de reciclagem, otimização de sistemas e desenvolvimento de políticas públicas.

##### Desafios:
- Custo de implementação: Câmeras, sensores, robótica e desenvolvimento de software podem ser caros.
- Manutenção: O sistema precisa de manutenção regular para garantir o funcionamento adequado.
- Contaminação: Materiais sujos ou misturados podem dificultar a identificação e classificação.
- Privacidade: É necessário garantir a privacidade dos usuários ao coletar e analisar dados de reciclagem.

##### Considerações adicionais:
- Integração com sistemas existentes: O sistema deve ser compatível com a infraestrutura de coleta de lixo e as instalações de reciclagem.
- Adaptabilidade: O sistema deve ser adaptável a diferentes tipos de resíduos e fluxos de reciclagem.
- Sustentabilidade: O sistema deve ser projetado com foco em eficiência energética e uso de materiais sustentáveis.

#### Conclusão:
Um sistema de automação de aprendizado de máquina para reciclagem tem o potencial de revolucionar a forma como lidamos com os resíduos, promovendo um futuro mais sustentável. Superando os desafios e implementando o sistema de forma eficaz, podemos aumentar as taxas de reciclagem, reduzir o impacto ambiental e criar comunidades mais limpas e saudáveis.


*IMAGEM DO OUTPUT*
![image](https://github.com/area-41/Gemini/assets/87396846/2b98b015-5169-4f85-ad19-88dca56b11bb)



## Exemplo Figuras

Agora utilizando o "chat prompt" e carregando um desenho feito no "Paint" do Windows.

#### Usando o prompt:
- Chat Prompt
  
#### INPUT 01:
 - Imagem:
   ![image](https://github.com/area-41/Gemini/assets/87396846/dbe6c464-a8a0-4ff3-b0dc-f36cca562315)

#### OUTPUT:
A imagem mostra um desenho simples de um rosto feliz com orelhas grandes.


#### INPUT 02:
![image](https://github.com/area-41/Gemini/assets/87396846/e99b1d41-7944-462c-ae85-5dff68f2c91f)

#### OUTPUT:
A imagem mostra o presidente dos Estados Unidos, Joe Biden, discursando em um pódio. Ele está vestindo um terno azul e uma gravata azul clara e tem uma expressão séria no rosto. Ele está gesticulando com a mão direita e há microfones na sua frente. Atrás dele, há uma bandeira americana.

AGORA COM UMA PEQUENA ALTERAÇÃO NA IMAGEM
#### INPUT 02 - 01:
![image](https://github.com/area-41/Gemini/assets/87396846/3fef9256-358e-48ea-b6ce-f6939b0cdd4d)

#### OUTPUT:
A imagem mostra o presidente dos Estados Unidos, Joe Biden, discursando em um pódio. Ele está vestindo um terno azul, camisa branca e uma gravata azul clara. Ele está gesticulando com a mão direita e há microfones posicionados em sua frente. Atrás dele, há uma grande bandeira americana. Biden parece estar falando com paixão, sua boca está aberta e seus olhos estão semicerrados.

Podemos observar que o Gemini entendeu a alteração na imagem como "Biden parece estar falando com paixão, sua boca está aberta e seus olhos estão semicerrados."

E ainda classificou como uma imagem com baixa possibilidade de ser imprópria por conteúdo sexual.
![image](https://github.com/area-41/Gemini/assets/87396846/004b02b0-a721-4e48-85dc-ca47f303f1bc)


*IMAGEM DO OUTPUT*
![image](https://github.com/area-41/Gemini/assets/87396846/d535a930-651d-4d87-9b1a-c31ba54ac474)
