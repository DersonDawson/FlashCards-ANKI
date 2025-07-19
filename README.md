# FlashCards-ANKI

Prompt poderoso para usar com Gemini e criar flashcards poderosos com Python para o aplicativo ANKI.
Confeccione flashcards a partir do material base que foi adicionado neste

chat obedecendo as seguintes diretrizes:

CONTEXTO - Você deve criar flashcards com base no conteúdo do material base. - O objetivo é que as informações mais importantes do documento sejam

abordadas para me auxiliar a memorizar o conteúdo durante a minha preparação

para provas de concursos públicos. - É imprescindível que **TODO O CONTEÚDO SEJA EXPLORADO**, de modo

que **nada fique de fora** para evitar que eu seja privado de informações

importantes para a prova que irei realizar.

CLAREZA CONTEXTUAL E AUTOSSUFICIÊNCIA - Cada card deve ser compreensível de forma independente, incluindo

contexto suficiente para que a pergunta faça sentido sem referência externa. - Assegure-se de que cada card contenha todo o conteúdo necessário para

responder à pergunta sem depender de outros cards ou do texto do material

base. - Evite se limitar a fazer apenas uma correlação simples e direta entre o

conteúdo de determinado dispositivo legal ao seu conteúdo, pois para a minha

prova eu não preciso decorar o número de artigos. - O dispositivo legal pode e deve ser citado como informação extra ou

justificativa da resposta sempre que for pertinente e estiver presente no material

base, mas saber o número do artigo que trata de tal ou qual informação não é

relevante

EVITAR REPETIÇÕES DESNECESSÁRIAS - Mescle cards semelhantes para evitar redundância e otimizar a eficiência da

aprendizagem. - Crie cards separados para conceitos complexos que podem ser

decompostos em partes mais simples. - Use apenas formas simples/finais de um conceito já abordado em cards

anteriores. - Não repetir detalhes já cobertos em outros cards.

SELEÇÃO DE INFORMAÇÕES - **Realize uma análise contextual (detalhada e criteriosa) do material base**

para conseguir extrair quais são as informações mais importantes a serem

lembradas. - Concentre-se em pontos essenciais, identificando e extraindo as ideias

principais ou conceitos-chave do texto, levando em consideração a análise

contextual acima referida. - Mantenha a concisão, preparando cards curtos e precisos, eliminando

verbosidade desnecessária para facilitar a memorização sem sobrecarga

cognitiva. - Use linguagem clara e precisa, com termos exatos e formulações claras para

evitar qualquer ambiguidade tanto na pergunta quanto na resposta.

TIPOS DE CARD - Explore vários tipos diferentes de cards conforme o conteúdo explorado,

adaptando-os da melhor maneira ao conteúdo que está sendo explorado

naquele card.

Exemplos:

+ Card Simples (Q&A): Recomendável para conceitos curtos e objetivos, que

normalmente podem ser apresentados em 1 linha.

+ Card de lista/classificação: Recomendável quando há uma lista de exceções,

classificações de um instituto jurídico etc.

+ Card Cloze Deletion: Útil para leis, definições formais e classificações. - É imprescindível que pelo menos os três tipos de cards acima apresentados

sejam explorados por você. - Os tipos previstos acima são apenas sugestões, mas você pode criar

quaisquer outros tipos que considerar relevantes, seguindo a sintaxe e linguagem

pertinente para cards do software Anki

PLANO DE AÇÃO - 1º Passo: Fazer a análise contextual do material apresentado para ser capaz

de extrair o conteúdo mais importante para confecção dos cards. - 2º Passo: Confeccionar os cards utilizando a linguagem Python para que o

usuário possa copiar, colar e salvar na extensão `.py` a fim de executar em sua

própria máquina local e gerar automaticamente um arquivo consolidado na

extensão `.akpg`, que será importado para o Anki. - 3º Passo: Insira código CSS para garantir que os cards tenham uma

aparência agradável e atrativa ao usuário.

+ Seja atencioso à formatação dos cards e à identidade visual, pois ela auxilia

bastante na memorização. Utilize negrito, itálico, sublinhado, cores no texto,

cores de fundo e outros recursos visuais para tornar a experiência do usuário

agradável. A paleta deve ter por base a cor #A1CC14

+ Seja criterioso com o código em relação à criação de diferentes tipos de

cards para evitar erros de lógica que impeçam a criação dos cards. Utilize

"type_model=0" para cartões do tipo básico e "type_model=1" para cartões do

tipo cloze (lacunas), pois essa é a nomenclatura utilizada pela biblioteca genanki

para os tipos de cards

Créditos : Anderson Machado Morais https://www.linkedin.com/in/anderson-machado-morais/
