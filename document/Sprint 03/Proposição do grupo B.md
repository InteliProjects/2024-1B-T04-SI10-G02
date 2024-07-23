# Documentação Preliminar para Teste A/B na Landing Page da Wizard On

## Introdução

&emsp;&emsp; O presente documento tem como objetivo detalhar a proposta de um teste A/B para a landing page da Wizard On, curso de inglês online. A Wizard On é uma plataforma que oferece aulas de inglês ao vivo com professores dedicados e materiais didáticos de alta qualidade. Com o intuito de melhorar a experiência do usuário e aumentar a taxa de conversão da página, foram propostas várias mudanças no design e na arquitetura da informação. Este documento descreve o design experimental, a justificação das propostas, a viabilidade e logística da implementação, além de uma análise de riscos. Vale ressaltar que esta é uma documentação preliminar, uma vez que os dados dos resultados serão coletados após a página ser colocada em produção.


## Seleção dos Grupos:
Para um teste A/B temos dois grupos, o grupo de controle que é a versão atual da página e o grupo experimental, que é a nossa proposta B.

> [!CAUTION]
> O GIF abaixo pode demorar cerca de alguns segundos para carregar

```diff
- Lembrando que de acordo com a sua internet o GIF pode demorar mais tempo para o carregamento, ou até mesmo não renderizar. Devido a esse fato, estamos disponibilizando o link do figma para visualizar nossa proposta B
```
[Design da Proposta B](https://www.figma.com/design/iBvH6y5aXeD3SEToqbMGv8/Wizard-LP---Grupo-2?node-id=0-1&t=xpOz1NBAx6cPOwPl-0)

- **Grupo A (Controle):** Utiliza o layout atual da landing page, com o botão do WhatsApp no formato original, formulário com texto detalhado e a disposição atual dos elementos.

<i>**Versão Desktop**</i>

![Imagem da Página Atual](https://github.com/Inteli-College/2024-1B-T04-SI10-G02/blob/feature/sprint3-create-documentation-UX/document/Sprint%2003/assets/desktop_grupo%20de%20controle.gif)

<i>**Versão Mobile**</i>

![Imagem da Página Atual](https://github.com/Inteli-College/2024-1B-T04-SI10-G02/blob/feature/sprint3-create-documentation-UX/document/Sprint%2003/assets/mobile_grupo%20de%20controle.gif)

- **Grupo B (Experimento):** Proposta de layout revisada com as seguintes mudanças:

<i>**Versão Desktop**</i>

![Imagem da Página Atual](https://github.com/Inteli-College/2024-1B-T04-SI10-G02/blob/feature/sprint3-create-documentation-UX/document/Sprint%2003/assets/desktop_grupo%20experimental.gif)

<i>**Versão Mobile**</i>

![Imagem da Página Atual](https://github.com/Inteli-College/2024-1B-T04-SI10-G02/blob/feature/sprint3-create-documentation-UX/document/Sprint%2003/assets/mobile_grupo%20experimental.gif)

### Principais mudanças
  1. Botão do WhatsApp minimalista e reposicionado.

     ![Imagem do WhatsApp da Proposta B](https://github.com/Inteli-College/2024-1B-T04-SI10-G02/blob/feature/sprint3-create-documentation-UX/document/Sprint%2003/assets/Imagem%20do%20WhatsApp%20da%20Proposta%20B.png)

  2. Formulário com texto simplificado e direto.

     ![Imagem do Formulário da Proposta B](https://github.com/Inteli-College/2024-1B-T04-SI10-G02/blob/feature/sprint3-create-documentation-UX/document/Sprint%2003/assets/Imagem%20do%20Formul%C3%A1rio%20da%20Proposta%20B.png)

  3. Alteração na ordem dos elementos, destacando o WIZ.me mais acima.

     ![Imagem do WIZ.me da Proposta B](https://github.com/Inteli-College/2024-1B-T04-SI10-G02/blob/feature/sprint3-create-documentation-UX/document/Sprint%2003/assets/Imagem%20do%20WIZ.me%20da%20Proposta%20B.png)

  4. Vídeo explicativo posicionado abaixo do WIZ.me.

     ![Imagem do Vídeo Explicativo da Proposta B](https://github.com/Inteli-College/2024-1B-T04-SI10-G02/blob/feature/sprint3-create-documentation-UX/document/Sprint%2003/assets/Imagem%20do%20V%C3%ADdeo%20Explicativo%20da%20Proposta%20B.png)

  5. Texto do Compromisso de Aprendizagem em bullet points.

     ![Imagem do Compromisso de Aprendizagem da Proposta B](https://github.com/Inteli-College/2024-1B-T04-SI10-G02/blob/feature/sprint3-create-documentation-UX/document/Sprint%2003/assets/Imagem%20do%20Compromisso%20de%20Aprendizagem%20da%20Proposta%20B.png)

## Métricas-Chave:

- **Taxa de Conversão:** Percentual de visitantes que preenchem o formulário de contato.
- **Tempo na Página:** Duração média da visita na landing page.
- **Interação com WhatsApp:** Diminuição de cliques no botão do WhatsApp.
- **Visualização do Vídeo:** Percentual de visitantes que scrollam a página até o vídeo.

**Duração do Teste:**

- O período de teste será de aproximadamente uma semana e meia, de acordo com a disponibilidade da Pearson.

## Estratégias

**Arquitetura de Informação:**

- **Reestruturação da Página:** Mudança na ordem dos elementos para priorizar a visibilidade das vantagens do curso online e do WIZ.me.

  ![Imagem do Novo Layout da Proposta B](https://github.com/Inteli-College/2024-1B-T04-SI10-G02/blob/feature/sprint3-create-documentation-UX/document/Sprint%2003/assets/Imagem%20do%20Novo%20Layout%20da%20Proposta%20B.png)

**Design de Interface:**

- **Botão de WhatsApp:** Reposicionamento e redesign para uma abordagem mais minimalista, evitando sobreposições e melhorando a usabilidade.

  ![Imagem do Novo Botão WhatsApp](https://github.com/Inteli-College/2024-1B-T04-SI10-G02/blob/feature/sprint3-create-documentation-UX/document/Sprint%2003/assets/Imagem%20do%20Novo%20Bot%C3%A3o%20WhatsApp.png)
- **Formulário de Contato:** Design limpo com texto claro e campos organizados para rápida compreensão e preenchimento.

  ![Imagem do Novo Formulário](https://github.com/Inteli-College/2024-1B-T04-SI10-G02/blob/feature/sprint3-create-documentation-UX/document/Sprint%2003/assets/Imagem%20do%20Novo%20Formul%C3%A1rio.png)
- **Elementos de Destaque:** WIZ.me destacado acima do vídeo, facilitando a visibilidade e atraindo a atenção do usuário.

  ![Imagem do WIZ.me e Vídeo](https://github.com/Inteli-College/2024-1B-T04-SI10-G02/blob/feature/sprint3-create-documentation-UX/document/Sprint%2003/assets/Imagem%20do%20WIZ.me%20e%20V%C3%ADdeo.png)

**Redação Estratégica (UX Writing):**

- **CTA (Call to Action):** Textos claros e diretos que incentivam a ação, como “Preencha e Entenda Melhor sobre o Curso”.

  ![Imagem do CTA](https://github.com/Inteli-College/2024-1B-T04-SI10-G02/blob/feature/sprint3-create-documentation-UX/document/Sprint%2003/assets/Imagem%20do%20CTA.png)
  
  ![Imagem do CTA](https://github.com/Inteli-College/2024-1B-T04-SI10-G02/blob/feature/sprint3-create-documentation-UX/document/Sprint%2003/assets/Imagem%20do%20CTA(1).png)
  
  ![Imagem do CTA](https://github.com/Inteli-College/2024-1B-T04-SI10-G02/blob/feature/sprint3-create-documentation-UX/document/Sprint%2003/assets/Imagem%20do%20CTA(2).png)
- **Texto do Compromisso de Aprendizagem:** Transformado em bullet points para facilitar a leitura e compreensão rápida.

  ![Vantagens do Curso da Wizard On](https://github.com/Inteli-College/2024-1B-T04-SI10-G02/blob/feature/sprint3-create-documentation-UX/document/Sprint%2003/assets/Vantagens%20do%20Curso%20da%20Wizard%20On.png)
- **Texto de Vantagens do Curso da Wizard On:** 

  ![Imagem do Texto do Compromisso de Aprendizagem](https://github.com/Inteli-College/2024-1B-T04-SI10-G02/blob/feature/sprint3-create-documentation-UX/document/Sprint%2003/assets/Imagem%20do%20Texto%20do%20Compromisso%20de%20Aprendizagem.png)
- **Mensagens Persuasivas:** Frases que enfatizam os benefícios imediatos e tangíveis do curso.

## Justificação da Proposta

**Escolha do Teste A/B:**

- **Base em Resultados de Simulação de Monte Carlo:** Apesar da simulação não ter indicado mudanças significativas entre as mudanças, estamos partindo da entrevista com os usuários para melhorar o design e informar que muitas pessoas chegam até a página por ver vantagem em um curso de inglês do que própriamente em uma campanha específica.
- **Fundamentos de Design:** As propostas foram baseadas em princípios de UX Writing e design de interface, visando melhorar a experiência do usuário e aumentar as interações.

**Consideração de Fatores Críticos:**

- **Usabilidade:** Foco em melhorar a navegabilidade e acessibilidade da página.
- **Engajamento do Usuário:** Aumento da visibilidade de elementos chave como o WIZ.me e o vantagens do curso da WizardOn.

## Viabilidade e Logística

**Avaliação da Viabilidade:**

- **Implementação Simples:** As mudanças propostas são de fácil implementação e não requerem alterações no backend. Apenas no layout da página.

**Logística:**

- **Testes e Ajustes:** Realização de testes iniciais para ajustes finos antes do lançamento do teste A/B completo.
- **Recursos Necessários:** Há a necessidade de auxílio na configuração do ambiente de homologação da Pearson. Além dos acessos necessários.

## Análise de Riscos

**Identificação de Riscos:**

O objetivo dessa análise de riscos é identificar e avaliar os possíveis riscos associados à implementação da tela B (teste) no site da Wizard On e, diante disso, desenvolver estratégias e propostas para mitigar ou lidar com os riscos identificados. Esse fator de risco está intimamente associado aos testes A/B (como o próprio nome diz, um teste), pois todas as mudanças propostas são apenas hipóteses, que mesmo embasadas em dados quantitativos e/ou qualitativos, ainda sofrem da possibilidade de serem falsas.

### Identificação e Avaliação de Possíveis Riscos

&emsp;&emsp; Nessa seção será identificado as mudanças feitas na página e os possíveis riscos associados à elas. As mudanças da versão mobile e desktop são de extrema semelhança, assim, os riscos associados foram os mesmos.

### Remoção do Número de Telefone 
**Tela A:**

![image](https://github.com/joaomtm/Rascunho/assets/99208815/de705c61-41bc-44fe-b27e-b0b74142c029)

**Tela B:**

![image](https://github.com/joaomtm/Rascunho/assets/99208815/704a0802-9923-4670-a4ef-b24a78f82b9b)

&emsp;&emsp; Assumimos em nossas hipóteses de que o número de telefone não é mais essencial e não contribui para a conversão de inscrições e leads. Essa hipótese se baseia principalmente na informação que temos da persona, que são mulheres jovens na faixa de 25 a 35 anos. Contudo, mesmo a persona utilizada sendo a pessoa média que usa o serviço, ainda existem os usuários atípicos, que tanto podem ser pessoas bem mais velhas que ainda possuem o costume de ligar para o estabelecimento ou até mesmo pessoas jovens que fortemente preferem fazer ligações quando desejam contratar um serviço. Assim, existe o risco da nova tela B ter menos inscrições e gerar menos leads por excluir um meio de comunicação e inscrição. Contudo, esse cenário é altamente improvável (conforme a "We Social" 93,4% dos brasileiros com acesso à internet usam WhatsApp) e de baixo impacto (estamos considerando um usuário que está fora da persona).

- **Ação de Mitigação:**

&emsp;&emsp;Implementação futura: Adicionar uma mensagem no WhatsApp que inclua o número de telefone para aqueles que preferirem ligar. Desta forma, a função de ligar não é totalmente removida e ainda pode ser acessada pelo WhatsApp.

### Alteração de Texto no Botão de Envio do Formulário 
**Tela A:** 

![image](https://github.com/joaomtm/Rascunho/assets/99208815/000832d6-a889-431a-918b-b4719b8c3161)

**Tela B:**

![image](https://github.com/joaomtm/Rascunho/assets/99208815/b6148190-f6df-4485-8f8a-b65272971f4a)

&emsp;&emsp; O risco dessa mudança de textos nos botões envolve a perda do valor de urgência. O texto "enviar" agrega valor no aspecto técnico, na clareza das ações que o usuário deve tomar para enviar o formulário. Porém, "aproveite!" agrega um apelo emocional e de urgência, incentivando a ação imediata, mas muito ligado a campanha de vinculação. Assim, é possível que essa mudança provoque a diminuição de cliques no envio de formulário e, por consequência, a taxa de conversão e inscrições diminuia. A probabilidade desse risco pode ser baixa ou média, mesmo tendo esse aspecto emocional e de urgência, o texto "aproveite!" perde parte do seu apelo por ser usado de forma massiva nas publicidades, contudo, talvez seja subestimar demais essa fórmula. O impacto deste risco seria médio, se esse ele se concretizasse, um pequeno número de potenciais clientes poderia ser perdido.

**- Ação de Mitigação:**

&emsp;&emsp; Implementação futura: Realizar testes adicionais A/B com variações do texto do botão para determinar o impacto específico de cada variação e encontrar um equilíbrio entre urgência e clareza técnica.

### Alteração Visual e de Localização do Botão Whatsapp  
**Tela A:** 

![image](https://github.com/joaomtm/Rascunho/assets/99208815/95708ade-c9c9-4dec-93d9-23ebf4d88495)

**Tela B:**

![image](https://github.com/joaomtm/Rascunho/assets/99208815/1f0b56f2-e117-4a56-8930-58d091939b33)

&emsp;&emsp; Sendo uma das alterações mais críticas do teste B, a diminuição, redesign e nova localização do botão do WhatsApp pode provocar uma diminuição significativa da conversão de cliques. Segundo os gestores da Wizard, hoje o botão do WhatsApp é o principal meio de conversão de cliques e inscrições. Nossa hipótese é que esse botão está demasiadamente grande, atrapalhando a leitura de outras informações na página, interação com o formulário e gerando até "miss clicks" (cliques falsos) na versão mobile. O risco está no equilíbrio dessas alterações do botão, existe a possibilidade dele ficar muito discreto (pouco chamativo, que não gera a iniciativa de interação), perdendo esse grande número de usuários que se convertem a partir desse meio. Portanto, essa alteração contém um risco médio com impactos altos. 

**- Ação de Mitigação:**

&emsp;&emsp;Implementação futura: Monitorar a taxa de cliques no botão do WhatsApp e ajustar sua visibilidade e posicionamento com base nos dados de interação. Se necessário, aumentar ligeiramente o tamanho ou alterar a cor para destacá-lo melhor, ou até mesmo voltar a ancoragem dele em toda a página (quando o usuário 'scrollar', o whatsapp acompanha o scroll).

### Alteração do Texto Referente às Vantagens Associadas ao Curso
**Tela A:**

![image](https://github.com/joaomtm/Rascunho/assets/99208815/8699604f-8182-44e3-8308-a634c8a87b6f)

**Tela B:**

![image](https://github.com/Inteli-College/2024-1B-T04-SI10-G02/blob/feature/sprint3-create-documentation-UX/document/Sprint%2003/assets/Imagem%20do%20CTA(2).png)


&emsp;&emsp; A alteração feita está diretamente associada ao UX Writing da página. O risco associado é muito baixo, sendo um texto informativo e persuasivo que não sofre na questão de conteúdo, apenas da forma. O texto da tela A, ressalta um pouco mais o ponto do desenvolvimento e aprendizado, como se esses fossem fatores propostos pelo acompanhamento dos professores, dando uma maior impressão que o aluno de fato irá se desenvolver durante esse acompanhamento. Essa alteração pode diminuir a persuasão de inscrição ao curso, contudo, seu risco é baixo, visto que a mudança no texto é pouca e a massividade de outros textos informativos presentes na página. O impacto previsto também seria baixo.

**- Ação de Mitigação:**

&emsp;&emsp;Implementação futura: Realizar pesquisas de usabilidade e testes com usuários para entender melhor quais mensagens são mais persuasivas e ajustar o texto com base no feedback dos usuários.

## Estratégias para Mitigar ou Lidar com os Riscos Identificados

&emsp;&emsp; Como explicado na seção "Objetivo", os riscos estão diretamente associados à prática do teste A/B, especialmente os testes A/Bs multivariados (cenário do atual projeto, em que estamos testando cinco telas Bs). Existem algumas formas de mitigar os riscos, mas nunca exclui-los totalmente.

### Dados, Propostas Feitas a Partir de Testes

&emsp;&emsp; A primeira estratégia é o forte embasamento das hipóteses desenvolvidas, caso nossas sugestões fossem aleatórias ou puramente intuitivas, o risco de termos resultados negativos seria muito maior, assim, todas as mudanças propostas foram construídas a partir de hipóteses desenvolvidas por meio de testes qualitativos. Assim, utilizamos os dados coletados para construir a proposta da tela B.

### Controle do Número de Telas B

&emsp;&emsp; A segunda forma de mitigar os riscos associados à implementação da tela B é limitar o número de usuários expostos a ela inicialmente. Isso nos permite avaliar seu impacto em um grupo menor e realizar ajustes antes de uma implementação em escala. De forma geral, recomenda-se que 60% das telas sejam destinadas à tela A e 40% à tela B. Em nosso projeto, essa porcentagem é ainda mais controlada, 94% destinado à tela A e 6% destinados à tela B, uma redução de cerca de 10 vezes do recomendado. Esse alto controle diminui de forma drástica as consequências e riscos associados à implementação das novas telas.

### Mudança Gradual, Limitação de Riscos

&emsp;&emsp; A terceira forma de mitigar é evitar mudanças drásticas na página. Além de ser difícil identificar quais fatores contribuíram para o sucesso ou falha da página, manter outros aspectos do site inalterados garante que o nível de sucesso permanecerá semelhante às propostas anteriores, que ainda mantêm várias características das outras páginas. Assim, a variação de resultados não será tão grande, algo que não passa ou diminui dos 10%. Esse é um bom número que permite trabalhar sem tanto receio de comprometer ou perder os resultados alcançados até o momento.

## Conclusão

&emsp;&emsp; A proposta de teste A/B visa otimizar a landing page da Wizard On, focando na melhoria da experiência do usuário e na maximização das taxas de conversão. As mudanças sugeridas baseiam-se em princípios sólidos de UX e design de interface, além de insights obtidos por meio de simulações de Monte Carlo. A implementação das alterações é viável e logisticamente simples, com estratégias claras para mitigação de riscos. Esta documentação preliminar servirá como guia para a execução do teste e para futuras análises dos resultados obtidos.