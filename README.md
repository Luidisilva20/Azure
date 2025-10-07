# Desafio de Laboratório DIO: Explorando IA Generativa com Azure Speech e Language Studio

## 📝 Descrição do Projeto

Este repositório documenta minha jornada de aprendizado e exploração prática das ferramentas de Inteligência Artificial da Microsoft Azure: o **Speech Studio** e o **Language Studio**. O objetivo deste desafio, proposto pela DIO, é aplicar os conceitos de análise de fala e linguagem natural para entender suas capacidades e possíveis aplicações no mundo real.

## 🤖 Ferramentas Utilizadas

-   [Azure Speech Studio](https://speech.microsoft.com/)
-   [Azure Language Studio](https://language.cognitive.azure.com/)
-   [GitHub](https://github.com/) para versionamento e documentação.
-   Markdown para a elaboração deste `README`.

---

## 🗣️ Exploração do Azure Speech Studio

Nesta seção, detalho os experimentos realizados com o serviço de Fala do Azure.

### 1. Conversão de Fala em Texto em Tempo Real (Speech-to-Text)

Realizei um teste simples utilizando o microfone para transcrever uma frase em português.

**Entrada:** "Olá, mundo! Este é um teste para o serviço de transcrição da Microsoft Azure."

**Resultado:**
![Print da tela de Speech-to-Text](images/seu-print-speech-to-text.png)

**🧠 Insights e Observações:**
* A precisão da transcrição foi impressionante, capturando todas as palavras corretamente.
* A latência foi muito baixa, com o texto aparecendo quase instantaneamente.
* Notei que a ferramenta também oferece opções para identificar diferentes locutores e analisar a pronúncia, o que demonstra um grande potencial para aplicações de call centers ou aprendizado de idiomas.

### 2. Conversão de Texto em Fala (Text-to-Speech)

Explorei a galeria de vozes neurais para sintetizar áudio a partir de um texto.

**Entrada:** "Descubra o futuro da tecnologia com a Inteligência Artificial da Azure."

**Configurações:**
* Voz: `pt-BR-FranciscaNeural`
* Estilo: `Default` (ou "Empolgado", se você testou)

**Resultado:**
*(Aqui você pode descrever o resultado, já que não dá pra colocar um áudio)* O áudio gerado foi extremamente natural e fluido, sem o som "robotizado" comum em outros sistemas.

**🧠 Insights e Observações:**
* A qualidade das vozes neurais é um diferencial enorme. A voz "Francisca" soa muito humana.
* A capacidade de ajustar estilos (como "atendimento ao cliente" ou "noticiário") torna a ferramenta muito versátil para diferentes cenários de negócios, como assistentes virtuais e narração de conteúdo.

---

## 🌐 Exploração do Azure Language Studio

Aqui, documento os testes com os serviços de análise de linguagem.

### 1. Análise de Sentimento

Analisei duas avaliações de produtos para testar a capacidade do serviço de identificar o sentimento.

**Texto de Entrada:** "Amei o celular novo, a câmera é fantástica! No entanto, a bateria poderia durar mais."

**Resultado:**
![Print da tela de Análise de Sentimento](images/seu-print-analise-de-sentimento.png)

**🧠 Insights e Observações:**
* O serviço corretamente identificou o sentimento geral como "Misto".
* O mais impressionante foi a análise a nível de sentença, que marcou a primeira parte ("Amei o celular...") como positiva e a segunda ("a bateria poderia durar mais") como negativa. Isso é extremamente útil para obter feedback detalhado de clientes.

### 2. Reconhecimento de Entidades Nomeadas (NER)

Utilizei uma frase complexa para verificar a identificação de entidades.

**Texto de Entrada:** "O presidente da DIO, Iglá Generoso, anunciou uma nova formação em IA em parceria com a Microsoft."

**Resultado:**
![Print da tela de NER](images/seu-print-ner.png)

**🧠 Insights e Observações:**
* A ferramenta identificou com precisão "Iglá Generoso" como Pessoa e "DIO" e "Microsoft" como Organizações.
* Esse tipo de recurso é fundamental para sistemas que precisam extrair e categorizar informações de grandes volumes de texto não estruturado, como notícias, e-mails e relatórios.

## 🏁 Conclusão

Este laboratório foi uma experiência prática fantástica. Pude comprovar o quão poderosas e acessíveis são as ferramentas de IA da Azure. A capacidade de analisar e gerar fala e texto com alta qualidade abre um leque imenso de possibilidades para a criação de soluções inovadoras. A documentação clara e a interface intuitiva dos Studios facilitaram muito o processo de aprendizado.
