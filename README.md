# Trabalho Avaliativo 1 (T1) — Gerência de Configuração (ENS4000)
**Área de Ciências Exatas e Engenharias — Universidade de Caxias do Sul (UCS)**  
**Tema 4:** O fim da programação  
**Pergunta Principal:** A IA vai acabar com a profissão do desenvolvedor de software?

---

## 👥 Integrantes do Grupo
* **Pedro Carlesso:** Pergunta Principal
* **Otávio Cabalheiro Salton:** Pergunta Norteadora 1
* **Leonardo dos Anjos:** Pergunta Norteadora 2
* **Lucas Didoné Oliveira:** Pergunta Norteadora 3

---

## 🎯 Posicionamento do Grupo

A Inteligência Artificial não vai extinguir a Engenharia de Software, mas sim transformá-la. A automação absorve a escrita mecânica e operacional de código (complexidade acidental), enquanto a modelagem de problemas de negócio, a arquitetura de sistemas e a responsabilidade final continuam sendo exigências estritamente humanas (complexidade essencial). O desenvolvedor do futuro evolui de um "digitador de código" para um engenheiro e orquestrador de sistemas baseados em IA.

---

## 📌 Perguntas Norteadoras e Fundamentação

### Pergunta Principal: A IA vai acabar com a profissão do desenvolvedor de software?
**Responsável:** Pedro Carlesso

A rápida evolução dos Grandes Modelos de Linguagem (LLMs) e das ferramentas de Inteligência Artificial (IA) generativa trouxe para o centro do debate a pergunta: *"A IA vai acabar com a profissão do desenvolvedor de software?"*.

#### A Ascensão do "Software 2.0" e o Fim da Codificação Manual
A premissa de que a profissão do desenvolvedor está com os dias contados ganha força com o artigo-âncora de Matt Welsh (2023), *"The End of Programming"*. Welsh argumenta de forma incisiva que a Computação, nos moldes em que a conhecemos, está morta. Segundo o autor, a transição fará com que os profissionais deixem de "escrever código" linha por linha e passem a focar no treinamento e na curadoria de sistemas baseados em IA.

Essa mudança de paradigma foi antecipada conceitualmente por Andrej Karpathy (2017) através do conceito de **"Software 2.0"**. Enquanto no "Software 1.0" o programador escreve instruções lógicas explícitas (estruturas de repetição e condicionais), no Software 2.0 o comportamento do sistema é definido por redes neurais que "descobrem" a lógica a partir de vastos conjuntos de dados. A IA passa a ser quem escreve o código, deixando para as pessoas a parte de fundamentá-lo.

Levando essa visão ao extremo, Cao (2026) em *"The End of Software Engineering"* defende que não apenas a codificação manual desaparecerá, mas todo o ciclo de vida do software — incluindo arquitetura, testes e deploy — será engolido por agentes autônomos de IA, sugerindo a possível substituição de times inteiros de engenharia.

#### A Realidade Prática e os Limites da IA
No entanto, a prática nos mostra que as IAs ainda esbarram naquilo que Fred Brooks (1987) chamava de **"complexidade essencial"** do software: entender as regras reais do mundo e o impacto de cada decisão. 

Quando pesquisadores colocaram as Inteligências Artificiais de ponta para resolver problemas reais de código, os resultados foram bem diferentes do esperado. No famoso teste **SWE-bench**, modelos avançados conseguiram resolver sozinhos apenas 1,7% dos problemas. Posteriormente, o estudo *"The SWE-Bench Illusion"* (2026) mostrou algo ainda mais curioso: mesmo os testes que apontavam taxas de acerto maiores (perto dos 13%) estavam "contaminados". As IAs não estavam criando soluções novas, mas apenas lembrando e reproduzindo respostas de códigos que já existiam em seus bancos de dados de treinamento.

#### O Desenvolvedor Orquestrador
Trazendo essa discussão para o dia a dia, o desenvolvedor Lucas Montano (2026) reforça que a IA não vai acabar com a profissão, mas vai deixar para trás quem insiste em programar e revisar tudo manualmente. Ele destaca que o foco do trabalho já mudou para a coordenação de ferramentas de IA e a garantia de qualidade por meio de automação de processos repetitivos. 

Esse relato prático de mercado confirma a conclusão fundamental: o desenvolvedor não vai desaparecer, mas deixa definitivamente de ser um "digitador de código" para atuar como um **orquestrador de sistemas**.

#### Conclusão
A profissão não está morrendo, mas evoluindo. O desenvolvedor do futuro precisará atuar como um engenheiro de sistemas e orquestrador de IA, exigindo habilidades muito mais sofisticadas do que a simples digitação de código. O foco da profissão passará para o pensamento crítico, a engenharia de prompts avançada, a auditoria rigorosa do código gerado por máquinas e a compreensão profunda das regras de negócio. 

Em suma, a Inteligência Artificial não substituirá o engenheiro de software, mas o engenheiro que dominar a complexidade essencial e souber orquestrar a IA certamente substituirá aquele que se recusar a evoluir.

---

### 1. O que a engenharia de software resolve de verdade: escrever código ou outra coisa?
**Responsável:** Otávio Cabalheiro Salton

A Engenharia de Software não tem como objetivo primário a simples escrita de código. Escrever código representa a **complexidade acidental** da profissão — o esforço braçal e operacional de traduzir lógica para uma sintaxe compreensível pela máquina (Brooks, 1987). É justamente essa camada operacional que a Inteligência Artificial automatiza com alta eficiência.

O que a Engenharia de Software resolve de fato é a **complexidade essencial**:
* **Modelagem e Entendimento do Negócio:** Traduzir requisitos humanos frequentemente ambíguos ou contraditórios em regras de negócio rigorosas.
* **Arquitetura e Design de Sistemas:** Projetar como diferentes microsserviços, bancos de dados, APIs e mecanismos de segurança se integram de forma escalável e resiliente.
* **Gerência e Evolução de Software:** Manter a rastreabilidade, o controle de versões, a gestão de dependências e a integridade contínua do sistema ao longo do tempo (foco central da Gerência de Configuração).

Em contraste com a visão de Welsh (2023) de que a programação clássica acabará, sustentamos que o que acaba é a escrita manual de código repetitivo. A engenharia focada em arquitetura e solução de problemas permanece essencialmente humana.

**Evidência Empírica:** O estudo *The SWE-Bench Illusion* (2026) demonstra empiricamente que o alto desempenho de LLMs em testes de código ocorre majoritariamente por **memorização** de soluções contidas em seus dados de treinamento, e não por raciocínio arquitetural sobre problemas inéditos. Portanto, a IA atua como assistente de produtividade, mas falha em substituir o raciocínio sistêmico.

---

### 2. Outras tecnologias já prometeram acabar com a programação antes? O que aconteceu?
**Responsável:** Leonardo dos Anjos 

A promessa de "acabar com a programação" acompanha a área de tecnologia há décadas. Historicamente, todas as inovações que prometeram eliminar a necessidade de programadores apenas elevaram o nível de abstração do trabalho, alterando como a programação é feita, mas não eliminando a profissão.

**1. Linguagens de Alto Nível (década de 1950):**
* **A Promessa:** O surgimento de linguagens como COBOL e Fortran prometia que executivos de negócios e cientistas poderiam instruir computadores escrevendo em um inglês quase natural ou com equações, eliminando a necessidade de programadores de linguagem de máquina (Assembly).
* **O que Aconteceu:** A abstração permitiu construir softwares muito maiores e mais complexos. Em vez de dispensar programadores, isso gerou uma explosão na demanda por profissionais dedicados a estruturar sistemas cada vez mais robustos.

**2. Ferramentas CASE e Modelagem Visual (décadas de 1980 e 1990):**
* **A Promessa:** A premissa do CASE (*Computer-Aided Software Engineering*) era a geração automática de software. Acreditava-se que bastaria desenhar diagramas lógicos (como UML) e a ferramenta escreveria todo o código.
* **O que Aconteceu:** Essas ferramentas funcionavam apenas para gerar o esqueleto básico do sistema, mas não conseguiam capturar exceções, integrações complexas e regras de negócio específicas. A engenharia de software tradicional continuou sendo necessária para fazer o sistema funcionar na prática.

**3. Plataformas Low-Code e No-Code (década de 2010 até hoje):**
* **A Promessa:** Prometem empoderar os "desenvolvedores cidadãos", permitindo que qualquer pessoa crie aplicativos apenas arrastando e soltando blocos visuais.
* **O que Aconteceu:** Elas são excelentes para automatizar processos internos simples, mas rapidamente encontram limites técnicos. Quando o sistema precisa de escalabilidade, segurança e integração customizada, as empresas precisam chamar engenheiros de software tradicionais.

---

### 3. Como se avalia se uma previsão sobre o futuro de uma profissão merece ser levada a sério?
**Responsável:** Lucas Didoné Oliveira

**1. Clareza da mudança:** 
Dizer que "a IA vai acabar com uma profissão" é muito vago. No cenário atual, podemos dizer que a tecnologia automatiza as tarefas chatas e repetitivas, mas raramente elimina a necessidade de resolver o problema final. Na programação, por exemplo, a IA gera a estrutura rápida do código, mas ainda é preciso um profissional para entender quais são os objetivos e o funcionamento correto do sistema, uma vez que a essência da profissão nunca foi só o código, mas sim entender as necessidades, os problemas e garantir a entrega final.

**2. A ilusão de velocidade:** 
A IA é impressionante para entregar resultados rápidos em diversas áreas, como análises de textos, ajustar a formalidade de uma escrita ou explicar e dar uma aula de conceitos. Porém, na nossa profissão tem um diferencial, a funcionalidade principal precisa estar correta, e então entra o “Fardo da Revisão”, o sistema entrega um código aparentemente pronto, mas repleto de erros ocultos que fazem com que o profissional gaste mais tempo revisando do que gastaria para criar o programa do zero. E, como diz Bertrand Meyer (2023), a IA adora pedir desculpas.

**3. Confiabilidade e responsabilidade final:** 
Depois de impressionar com o fornecimento de uma aula de código e teoria, ao ser analisado percebe-se que o que era impressionante não tem muita utilidade para problemas complexos do dia a dia e pode até ser prejudicial. Em setores onde erros custam caro e quando houver risco de vida, prejuízo financeiro ou decisões éticas, uma máquina não pode assumir a culpa. A responsabilidade final e a tomada de decisão continuam sendo exigências humanas.

---

## 📚 Referências Bibliográficas
* BROOKS, F. P. **No Silver Bullet: Essence and Accidents of Software Engineering**. IEEE Computer, v. 20, n. 4, 1987.
* CAO, X. **The End of Software Engineering**. IEEE Software, 2026.
* JIMENEZ, C. et al. **SWE-bench: Can Language Models Resolve Real-World GitHub Issues?** ICLR, 2024.
* KARPATHY, A. **Software 2.0**. Medium, 2017.
* MEYER, B. **AI Does Not Help Programmers**. Blog CACM, 2023.
* MONTANO, Lucas. **Lucas Montano: dev que recusa IA vai ficar pra trás**. Entrevista concedida ao canal GringaNews, YouTube, 30 set. 2026.
* **The SWE-Bench Illusion: When State-of-the-Art LLMs Remember Instead of Reason**. ICSE-SEIP, 2026.
* WELSH, M. **The End of Programming**. Communications of the ACM, v. 66, n. 1, 2023.
