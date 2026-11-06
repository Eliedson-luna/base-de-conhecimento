# Ataque ao Fator Humano

## Phishing e Spear Phishing

O phishing é um ataque cibernético em massa que envia mensagens genéricas para milhares de pessoas com o objetivo de fisgar qualquer vítima descuidada, enquanto o spear phishing é um ataque altamente direcionado e personalizado contra um indivíduo ou empresa específica.

### Principais Diferenças

#### Phishing Tradicional:
- **Alvo:** Em massa (qualquer pessoa que receber a mensagem).
- **Mensagem:** Genérica, sem personalização profunda.
- **Estratégia:** Volume elevado; aposta na porcentagem baixa de pessoas que vão cair no golpe.
- **Exemplo:** Um e-mail falso de "atualização de senha de banco" enviado aleatoriamente para milhões de endereços.
#### Spear Phishing:
- **Alvo:** Específico (um funcionário, um executivo ou um departamento de uma organização).
- **Mensagem:** Altamente personalizada, baseada em pesquisas prévias sobre a rotina, cargo, colegas ou projetos da vítima.
- **Estratégia:** Menor volume, mas com taxa de sucesso muito maior (frequentemente usando técnicas como Whaling para CEOs ou BEC — Comprometimento de E-mail Corporativo).
- **Exemplo:** Um e-mail fingindo ser do Diretor Financeiro da empresa pedindo uma transferência bancária urgente para um funcionário específico do setor de contas a pagar.
---
>
></br>O **whaling** (também chamado de whale phishing) é uma tática avançada de engenharia social e spear phishing focada em alvos de alto escalão, como executivos sênior (CEOs, CFOs, diretores) ou líderes políticos.
• *Como funciona:* Os criminosos pesquisam extensivamente o alvo para criar e-mails, mensagens ou ligações extremamente convincentes.
• *Objetivo:* Enganar a vítima para que ela autorize transferências bancárias fraudulentas, revele dados sigilosos da empresa ou instale malware.
• *Diferença para BEC (Business Email Compromise):* No whaling, o executivo é a vítima direta do golpe; já na fraude do CEO (BEC), o golpista usa uma identidade falsificada do executivo para enganar um funcionário do setor financeiro a fazer um pagamento.</br></br>

### Como se Proteger

- **Verificação Independente:** Sempre confirme pedidos urgentes de dinheiro ou alteração de dados por outro canal confiável (como telefonar para o colega ou ramal interno).
- **Autenticação Multifator (MFA):** Ative a verificação em duas etapas em todas as contas corporativas e pessoais.
- **Atenção a Links e Anexos:** Nunca clique em links suspeitos ou baixe arquivos de remetentes desconhecidos ou com pequenos erros no domínio de e-mail.
- **Treinamento:** Eduque equipes para reconhecer gatilhos de urgência e pressão psicológica.

## Vishing

O vishing (junção de voice + phishing) é um golpe de engenharia social praticado por chamadas telefônicas ou mensagens de voz, no qual criminosos se passam por representantes de empresas confiáveis — como bancos, operadoras, centrais de atendimento ou órgãos oficiais — para manipular a vítima e roubar dados ou dinheiro.

### O que caracteriza o vishing

- **Abordagem verbal:** Diferente do phishing tradicional (que usa e-mails ou sites falsos), o vishing aposta na conversa ao vivo para gerar maior urgência e persuasão.
- **Falsa autoridade e urgência:** Os golpistas costumam alegar bloqueios urgentes na conta, compras suspeitas ou problemas técnicos, pressionando a vítima a agir sem pensar.
- **Falsificação de número (Spoofing):** Eles conseguem manipular o identificador de chamadas para que o visor do seu celular mostre o número real do banco ou da empresa.
- **No Brasil:** É um dos tipos de estelionato que mais cresce; dados apontam valores médios perdidos significativos por vítima em fraudes do tipo.

## Skimming

O skimming é uma técnica fraudulenta em que criminosos capturam dados de cartões de crédito ou débito e informações pessoais.
Ele é dividido principalmente em duas categorias:

### 1. Skimming Físico (Presencial)

- **Como funciona:** Dispositivos clandestinos (chamados de skimmers) são instalados ilegalmente sobre ou dentro de leitores de cartões em caixas eletrônicos (ATMs), terminais de ponto de venda (PDV) ou bombas de combustível.
- **Captura:** O aparelho lê e armazena os dados da tarja magnética ou do chip. Frequentemente, os golpistas usam câmeras escondidas ou teclados falsos (overlays) para gravar a senha (PIN) digitada pelo usuário.
- **Objetivo:** Clonar o cartão ou usar os dados para saques e compras.

### 2. Skimming Digital (E-skimming / Web Skimming)

- **Como funciona:** Criminosos injetam códigos maliciosos (geralmente JavaScript, como em ataques do grupo Magecart) em páginas de pagamento de lojas de e-commerce.
- **Captura:** Quando o cliente preenche os dados do cartão no checkout, as informações são capturadas em tempo real e enviadas de forma invisível para um servidor controlado pelo invasor.
- **Objetivo:** Roubar números de cartões, códigos de segurança (CVV), nomes e endereços para fraudes online.

## Tailgating

Um ataque de tailgating (também conhecido como piggybacking) é uma tática de engenharia social focada em segurança física, na qual uma pessoa não autorizada consegue acesso a uma área restrita seguindo de perto um usuário legítimo.

O termo vem do trânsito (o ato de um carro "colar na traseira" de outro) e, no contexto corporativo, baseia-se em explorar a distração ou a cortesia humana.

### Como funciona na prática?

Os invasores se aproveitam da educação ou de disfarces para burlar portarias, catracas ou portas magnéticas:
- **Aproveitar a cortesia:** O funcionário passa o crachá e abre a porta; o golpista vem logo atrás (muitas vezes carregando caixas pesadas ou fingindo pressa) e o funcionário, por pura educação, segura a porta para ele.
- **Disfarces:** O invasor se veste como entregador de comida, técnico de manutenção ou prestador de serviços para se misturar ao ambiente sem levantar suspeitas.
- **Fluxo de horários de pico:** Entrar no meio de um grande grupo de funcionários durante o horário de entrada ou almoço, quando a fiscalização visual fica mais difícil.

### Existe tailgating digital?

Sim. Embora o termo seja majoritariamente físico, o conceito digital se aplica quando um invasor se aproveita de uma sessão já autenticada. Por exemplo: um funcionário se levanta para tomar café e deixa o computador desbloqueado; o invasor assume o teclado para roubar dados ou instalar malwares

## Water-holing

Um ataque de water-holing (watering hole ou "ataque ao bebedouro") é uma estratégia de cibersegurança em que os criminosos comprometem um site legítimo que um grupo específico de pessoas ou funcionários de uma empresa costuma visitar com frequência.

Como funciona

1. **Investigação:** O invasor estuda a rotina de um grupo ou organização para descobrir quais sites (como portais de notícias do setor, blogs, fóruns ou páginas de parceiros) eles acessam com regularidade.
2. **Comprometimento:** O invasor invade esse site de terceiros e injeta códigos maliciosos (como malware, scripts de redirecionamento ou falsas atualizações de software).
3. **Espera:** Assim como um predador que espera a presa no ponto de água da savana, o invasor apenas aguarda os usuários-alvo entrarem na página para infectar seus dispositivos de trabalho.
4. **Acesso:** Uma vez infectado o computador da vítima, o invasor ganha uma porta de entrada para a rede corporativa da empresa.

## Dumbster Diving

Em cibersegurança, dumpster diving (ou "vasculhar o lixo") é uma técnica de engenharia social que consiste em procurar informações confidenciais em materiais descartados incorretamente. Embora pareça um método rudimentar e de baixa tecnologia, ele continua sendo altamente eficaz para criminosos que buscam invadir sistemas ou aplicar golpes.

O ataque se divide principalmente em duas frentes:
- **No plano físico:** O invasor revira lixeiras comuns ou contêineres de descarte de empresas e residências em busca de papéis com senhas anotadas, relatórios financeiros, organogramas, listas de telefones internos ou contratos.
- **No plano digital (Lixo Eletrônico):** Envolve a coleta de dispositivos de armazenamento descartados — como HDs antigos, pen drives, notebooks ou celulares — que não passaram por uma limpeza segura de dados e ainda contêm arquivos recuperáveis.

### Como os cibercriminosos usam o que encontram?

Raramente o lixo trará uma senha mestra de imediato, mas os atacantes juntam pequenas pistas para:

1. Criar ataques de Phishing direcionados (Spear Phishing): Ao descobrir o nome de um gerente, o modelo de um sistema e uma data de reunião no lixo, o criminoso consegue ligar ou enviar um e-mail para um funcionário fingindo ser um parceiro de negócios legítimo.
2. Adivinhar credenciais: Listas de nomes de funcionários e e-mails ajudam a mapear os padrões de nomes de usuário da empresa.
3. Roubo de identidade e fraude: Documentos com CPFs, CNPJs, dados bancários ou assinaturas são usados para abrir contas falsas ou aplicar golpes financeiros.

## Pharming 

O pharming é um tipo de ataque cibernético em que criminosos redirecionam o tráfego de um site legítimo para uma página falsa e idêntica, com o objetivo de roubar dados confidenciais (como senhas, números de cartão e dados bancários).

### Como funciona

Diferente do phishing tradicional — onde a vítima precisa clicar em um link malicioso enviado por e-mail ou mensagem —, no pharming o usuário pode digitar o endereço correto do site no navegador e, ainda assim, ser levado para a página falsa de forma invisível.

Existem duas formas principais de realizar esse ataque:
- **Baseado em malware:** Um vírus ou trojan infecta o computador ou celular da vítima e altera o arquivo hosts local, forçando o aparelho a abrir o IP do site falso em vez do verdadeiro.
- **Envenenamento de DNS (DNS Cache Poisoning):** O ataque ataca o servidor DNS (o "diretório" da internet que traduz o nome do site em um endereço IP) ou o roteador da vítima ou de uma empresa, corrompendo os dados para redirecionar múltiplos usuários de uma vez. 

## Engenharia Social

A engenharia social é uma técnica de manipulação psicológica usada para enganar pessoas e convencê-las a entregar dados confidenciais, senhas, dinheiro ou a realizar ações que comprometem a segurança.

Em vez de quebrar senhas ou invadir sistemas de computadores com força bruta, o golpista "ataca o elo mais fraco": o fator humano.

Principais características

- **Exploração de emoções:** Os golpistas se aproveitam de sentimentos como medo, urgência, curiosidade, ganância, solidariedade ou respeito à autoridade.
- **Ação voluntária:** A vítima é manipulada a entregar a informação ou realizar a transferência por conta própria.
- **Farsa de identidade:** O criminoso frequentemente se passa por um funcionário de banco, técnico de suporte, parente em apuros ou empresa conhecida.


## Smishing

O smishing é um tipo de golpe de cibersegurança que combina as palavras SMS (Short Message Service) e phishing (fraude eletrônica para roubo de dados).

Nessa técnica, os criminosos usam mensagens de texto (por SMS, WhatsApp ou outros aplicativos de mensagens) se passando por instituições confiáveis — como bancos, Correios, operadoras de celular ou órgãos do governo — para enganar a vítima.

### Como o golpe funciona

- **Senso de urgência:** A mensagem costuma criar pânico ou pressa, dizendo que sua conta foi bloqueada, uma compra foi aprovada indevidamente ou uma encomenda está retida na alfândega.
- **Isca com link malicioso:** Incluem um link encurtado ou falso que leva a uma página clonada muito parecida com a original.
- **Roubo de dados ou dinheiro:** Ao acessar o link, a vítima é induzida a digitar senhas, dados de cartão de crédito, códigos de verificação ou a baixar um aplicativo malicioso (malware) no celular.

### Exemplos comuns no Brasil

- **Falsa taxa dos Correios:** Mensagens avisando que uma encomenda internacional está parada e exige o pagamento imediato de uma taxa via Pix ou link.
- **Bloqueio de conta bancária:** Alertas urgentes de transações suspeitas com um número de telefone ou link para "regularizar" a situação.
- **Falsos prêmios ou ofertas:** Notificações de sorteios ganhos ou vagas de emprego vantajosas que pedem dados pessoais para liberação.