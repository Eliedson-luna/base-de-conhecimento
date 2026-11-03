# CODIGOS MALICIOSOS

## 1 - Trojan Horse (Cavalo de Troia)

Um Trojan (ou Cavalo de Troia) é um tipo de malware (software malicioso) que se disfarça de um programa, arquivo ou aplicativo legítimo e útil para enganar o usuário.
Diferente de vírus ou worms, o Cavalo de Troia não se replica sozinho; ele depende de técnicas de engenharia social (como um anexo de e-mail falso ou um download gratuito) para fazer com que a própria vítima o execute.

### Qual é o objetivo?

O principal objetivo de um Trojan é dar aos cibercriminosos acesso não autorizado ao sistema da vítima. Uma vez instalado e executado em segundo plano, ele pode realizar diversas ações prejudiciais, tais como:

- **Criar uma "porta dos fundos" (backdoor):** Permitir que o invasor entre no computador ou celular remotamente a qualquer momento.
- **Roubar dados confidenciais:** Capturar senhas, dados de cartões de crédito, informações bancárias ou documentos pessoais.
- **Espionar o usuário:** Monitorar teclas digitadas (keyloggers), tirar prints da tela ou acessar a câmera e o microfone.
- **Instalar outros malwares:** Servir como "ponte" para baixar e executar vírus adicionais, ransomwares ou programas de negação de serviço.
- **Usar o dispositivo para golpes:** Redirecionar o usuário para sites falsos ou transformar a máquina em parte de uma rede botnet


## 2 - Worms

Um worm (ou verme de computador) é um tipo de malware (software malicioso) autônomo que consegue se replicar e se espalhar automaticamente por redes de computadores sem precisar de intervenção humana ou de um arquivo hospedeiro.

Diferente de um vírus comum, que precisa que você abra um arquivo ou execute um programa para funcionar, o worm é um programa completo que age sozinho, buscando falhas de segurança para pular de uma máquina para outra.

### Qual é o objetivo de um worm?

O objetivo principal de um worm varia conforme o criador, mas geralmente envolve:
- **Propagação em massa:** Infectar o maior número possível de dispositivos, servidores ou redes.
- **Consumo de recursos:** Multiplicar-se tanto que esgota a memória RAM, o processador e a largura de banda da rede, deixando sistemas lentos ou totalmente travados ("derrubados").
- **Instalação de outras ameaças (Payloads):** Abrir "portas dos fundos" (backdoors), roubar dados confidenciais ou instalar malwares mais perigosos, como ransomwares (que sequestram os dados com cobrança de resgate)

## 3 - Exploit

Um exploit é um programa, script ou trecho de código criado para aproveitar uma falha de segurança ou vulnerabilidade em um software, sistema operacional ou hardware.

### O objetivo principal

O objetivo de um exploit é manipular o sistema de forma não intencional para atingir um resultado específico:
- **Em contextos maliciosos (cibercriminosos):** Obter acesso não autorizado a um computador ou rede, roubar dados sensíveis, derrubar serviços (ataques de negação de serviço - DoS) ou instalar malwares (como vírus, ransomware ou spyware).
- **Em contextos éticos (pesquisadores de segurança e hackers do bem):** Criar uma "prova de conceito" (PoC) para demonstrar a existência da falha e permitir que os desenvolvedores corrijam o problema (patch de segurança) antes que criminosos o descubram.

### Componentes de um Exploit

Geralmente, um exploit funciona em conjunto com outros elementos:
- **Vulnerabilidade:** A falha original no código do programa.
- **Exploit:** O veículo ou método que "abre a porta" usando essa falha.
- **Payload:** A ação ou o código malicioso que é executado após a invasão bem-sucedida (por exemplo, abrir um terminal de comando remoto para o invasor)

## 4 - Flooders

Flooders (ou inundadores) são ferramentas, scripts ou agentes maliciosos projetados para sobrecarregar um sistema, rede ou serviço enviando um volume massivo e incessante de tráfego ou requisições legítimas.

O termo vem do inglês flood (enchente/inundação), o que ilustra perfeitamente o comportamento do ataque: afogar o alvo em dados até que ele não consiga mais operar.

### O objetivo dos Flooders em Cybersecurity

No contexto de segurança da informação, o uso de flooders está quase sempre atrelado a ataques de Negação de Serviço (DoS - Denial of Service) ou Negação de Serviço Distribuída (DDoS).

Os principais objetivos por trás desse tipo de ataque incluem:

- **Interrupção de Serviços:** Derrubar sites, servidores de jogos, sistemas bancários ou plataformas corporativas, tornando-os inacessíveis para usuários legítimos.
- **Exaustão de Recursos:** Esgotar a capacidade de processamento (CPU), memória RAM ou a largura de banda (Internet) do servidor alvo.
- **Cortina de Fumaça (Distração):** Inundar os sistemas de monitoramento de segurança com milhares de alertas falsos. Enquanto a equipe de TI corre para conter o "congestionamento", os atacantes aproveitam a distração para realizar invasões mais sofisticadas, como roubo de dados ou instalação de malware.
- **Extorsão e Ativismo:** Exigir pagamento em dinheiro (resgate) para parar o ataque ou protestar contra uma entidade governamental/corporativa (hacktivismo).

### Tipos comuns de Flooding

Os flooders atuam em diferentes camadas da rede. Os métodos mais conhecidos são:

- **HTTP Flood:** Envia milhares de requisições de páginas web (como comandos GET ou POST) simulando acessos de usuários reais até que o servidor web trave.
- **SYN Flood:** Explora o processo de conexão do protocolo TCP. O flooder envia requisições de conexão de forma repetida, mas nunca as finaliza, deixando o servidor esperando e consumindo todas as suas conexões disponíveis.
- **UDP Flood:** Envia uma quantidade massiva de pacotes UDP para portas aleatórias do alvo, forçando o sistema a verificar e responder a cada pacote, o que esgota a capacidade da rede.

## 5 - Injectors

Injectors (ou injetores) em cybersecurity são programas ou técnicas utilizadas para inserir código malicioso (malware) dentro de um processo legítimo que já está em execução no sistema operacional.

O principal objetivo dessa prática é a evasão de defesas, permitindo que o atacante execute comandos disfarçados como se fossem um software confiável do próprio sistema.

### Como funcionam?

Em vez de iniciar um arquivo .exe suspeito diretamente — o que chamaria a atenção imediata de antivírus e sistemas EDR (Endpoint Detection and Response) —, o injector atua nos bastidores:

1. Ele alveja um processo legítimo e confiável (como o explorer.exe, svchost.exe ou um navegador de internet).
2. Aloca um espaço na memória desse processo alvo.
3. Copia o código malicioso (geralmente em formato de DLL ou Shellcode) para esse espaço.
4. Força o processo legítimo a executar o código inserido.

### Principais Objetivos

Os atacantes e profissionais de segurança (em testes de invasão) utilizam injectors com os seguintes propósitos:

- **Burlar Antivírus (Evasão):** Como o malware "se esconde" dentro de um processo seguro, muitas ferramentas de segurança tradicionais monitoram apenas o processo pai e não detectam a atividade maliciosa ocorrendo na memória dele.
- **Segmentação de Privilégios:** Se um injector conseguir injetar código em um processo que roda com privilégios de Administrador ou de Sistema (SYSTEM), o código malicioso herdará esses privilégios mais altos.
- **Persistência Discreta:** Permite que o atacante mantenha acesso ao sistema infectado sem deixar rastros óbvios no disco rígido, operando diretamente na memória RAM (Fileless Malware).
- **Acesso a Dados Sensíveis:** Injetar código em navegadores ou processos de login permite capturar chaves de criptografia, cookies de sessão e senhas digitadas pelo usuário diretamente da memória.

### Técnicas Comuns de Injeção

- **DLL Injection:** Força um processo a carregar uma biblioteca (.dll) maliciosa.
- **Process Hollowing:** Cria um processo legítimo em estado suspenso, esvazia o seu código original e o substitui por um código malicioso antes de retomá-lo.
- **Reflective DLL Injection:** Carrega uma DLL da memória diretamente para o processo alvo, sem a necessidade de salvá-la no disco.
  

## 6 - Spyware

Spyware (software espião) é um tipo de malware projetado para monitorar secretamente as atividades do usuário e enviar as informações coletadas para um terceiro, sem o conhecimento ou o consentimento da vítima.

Diferente de um vírus ou worm, o spyware não costuma se replicar nem causar danos visíveis ao sistema. Seu "sucesso" depende de passar despercebido pelo maior tempo possível. Geralmente chega embutido em outros programas (como um trojan ou software gratuito), por anexos de e-mail maliciosos ou por sites comprometidos.

### Qual é o objetivo de um spyware?

O objetivo principal é a coleta silenciosa de informações. Entre as ações mais comuns:

- **Roubar credenciais e dados financeiros:** Capturar logins, senhas, números de cartão e dados bancários.
- **Monitorar hábitos de navegação:** Registrar sites visitados, buscas e downloads para fins de espionagem ou venda de perfis.
- **Capturar conteúdo da tela e de comunicações:** Tirar prints, gravar conversas, ler mensagens e e-mails.
- **Acessar câmera, microfone e localização:** Principalmente em dispositivos móveis.
- **Vender os dados coletados:** Informações pessoais alimentam fraudes, roubo de identidade e publicidade abusiva.

### Tipos comuns de Spyware

- **Keylogger:** Registra tudo o que é digitado no teclado (detalhado no item 10).
- **Infostealer:** Vasculha o sistema atrás de senhas salvas, cookies de sessão, carteiras de criptomoedas e arquivos específicos.
- **Stalkerware:** Spyware instalado por alguém que conhece a vítima (parceiro, familiar etc.) para monitorar mensagens, ligações e localização em tempo real, quase sempre em celulares.
- **Tracking cookies e trackers:** Rastreiam a navegação entre sites para montar um perfil do usuário (a zona cinzenta entre spyware e publicidade).
- **Screen scraper / screen recorder:** Captura imagens ou vídeos da tela em intervalos.

### Como se proteger

- Instalar aplicativos apenas de fontes oficiais.
- Manter sistema e antivírus atualizados.
- Revisar as permissões concedidas a aplicativos (câmera, microfone, acessibilidade).
- Desconfiar de anexos e links inesperados.

## 7 - Rootkit

Um rootkit é um conjunto de ferramentas ou programas maliciosos criado para ocultar a presença de um invasor (e de outros malwares) no sistema e manter acesso privilegiado (nível root/administrador) de forma contínua e discreta.

O nome vem de "root" (a conta de maior privilégio em sistemas Unix/Linux) + "kit" (conjunto de ferramentas). Importante: o rootkit em si não é o meio de invasão. Ele normalmente é instalado depois que o atacante já conseguiu acesso (via exploit, trojan, phishing etc.), com a função de esconder e perpetuar esse acesso.

### Qual é o objetivo de um rootkit?

- **Ocultação (stealth):** Esconder processos, arquivos, chaves de registro, conexões de rede e até o próprio malware das ferramentas do sistema e do antivírus.
- **Persistência:** Garantir que o malware sobreviva a reinicializações e até a tentativas de limpeza.
- **Manter privilégios elevados:** Dar ao atacante controle total sobre a máquina, de forma duradoura.
- **Abrir backdoors:** Permitir o retorno do invasor a qualquer momento.
- **Desativar defesas:** Neutralizar antivírus, firewalls e mecanismos de log para apagar rastros.

### Tipos de Rootkit (por nível de atuação)

- **User-mode (modo usuário):** Atua no nível de aplicações, interceptando chamadas de API para esconder informações. É o mais simples e o mais fácil de detectar.
- **Kernel-mode (modo kernel):** Altera o núcleo do sistema operacional (drivers, módulos). Tem poder total e é muito difícil de detectar e remover.
- **Bootkit:** Infecta o setor de inicialização (MBR/VBR ou UEFI), carregando antes do sistema operacional.
- **Firmware / hardware:** Reside em BIOS/UEFI, placas de rede ou outros firmwares, podendo sobreviver até à troca do disco rígido.
- **Hypervisor (virtualizado):** Executa o sistema operacional da vítima dentro de uma camada virtual controlada pelo atacante.
- **Memory rootkit:** Vive apenas na RAM e desaparece ao reiniciar, mas é difícil de detectar enquanto ativo.

### Detecção e remoção

- Como o rootkit engana o próprio sistema, a análise feita de dentro do SO infectado é pouco confiável. O ideal é escanear **de fora** (boot por mídia externa, ferramentas anti-rootkit especializadas, análise de memória).
- Em casos graves (kernel, bootkit, firmware), a solução mais segura costuma ser **reinstalar o sistema** ou reparar o firmware.
- Prevenção: manter sistema atualizado, usar Secure Boot, instalar apenas drivers assinados e aplicar o princípio do menor privilégio.

## 8 - Spoofing

Spoofing (falsificação) é uma técnica em que o atacante se passa por outra entidade confiável (um usuário, dispositivo, site ou serviço) falsificando dados de identificação para enganar pessoas ou sistemas.

Observação: spoofing é uma **técnica**, não um tipo de malware em si. Ela costuma ser usada como etapa de outros ataques (phishing, man-in-the-middle, DoS, invasão).

### Qual é o objetivo do spoofing?

- **Enganar a vítima:** Fazer o usuário acreditar que está interagindo com uma fonte legítima (banco, colega, fornecedor).
- **Roubar informações:** Obter senhas, dados pessoais e financeiros (phishing).
- **Burlar controles de acesso:** Contornar filtros e autenticações baseados em IP, MAC ou domínio.
- **Interceptar comunicações:** Posicionar-se entre dois pontos para espionar ou alterar dados (Man-in-the-Middle).
- **Ocultar a origem do ataque:** Dificultar o rastreamento do atacante, comum em ataques DDoS.

### Tipos comuns de Spoofing

- **IP Spoofing:** Falsifica o endereço IP de origem dos pacotes. Muito usado em ataques DoS/DDoS para esconder o atacante e em ataques de reflexão/amplificação.
- **Email Spoofing:** Forja o remetente de um e-mail para parecer legítimo. Base de muitos golpes de phishing e de fraudes do tipo "falso CEO".
- **DNS Spoofing (DNS Cache Poisoning):** Corrompe o cache de um servidor DNS para redirecionar o usuário a um site falso mesmo digitando o endereço correto.
- **ARP Spoofing:** Em redes locais, associa o MAC do atacante ao IP de outro dispositivo (ex.: o gateway), permitindo interceptar o tráfego (MITM).
- **MAC Spoofing:** Altera o endereço MAC da placa de rede para burlar filtros de acesso ou se passar por outro dispositivo.
- **Website Spoofing:** Cria páginas falsas idênticas às originais para capturar credenciais.
- **Caller ID Spoofing:** Falsifica o número exibido numa ligação, comum em golpes por telefone.

### Como se proteger

- Usar autenticação de e-mail (SPF, DKIM e DMARC).
- Usar DNSSEC e HTTPS, e conferir sempre o endereço e o certificado dos sites.
- Aplicar filtros de pacotes (ex.: ingress/egress filtering) e proteções contra ARP spoofing em switches.
- Habilitar autenticação multifator e desconfiar de pedidos urgentes por e-mail ou telefone.

## 9 - Adware

Adware (de advertising + software) é um programa que exibe propagandas de forma automática e indesejada no dispositivo do usuário, geralmente na forma de pop-ups, banners ou redirecionamentos do navegador.

Nem todo adware é malicioso: existem softwares gratuitos legítimos que se financiam com anúncios e informam isso ao usuário. O problema surge quando o adware é instalado sem consentimento claro (embutido em outro programa, o chamado *bundling*), coleta dados escondido ou degrada o sistema. Nesse caso é classificado como malware ou PUP (Potentially Unwanted Program).

### Qual é o objetivo do adware?

- **Gerar receita com publicidade:** O criador ganha por exibição ou por clique nos anúncios.
- **Rastrear hábitos de navegação:** Coletar dados para direcionar anúncios, o que aproxima o adware do spyware.
- **Redirecionar o tráfego:** Alterar página inicial, mecanismo de busca e favoritos (browser hijacking) para direcionar a sites patrocinados.
- **Servir de porta de entrada:** Anúncios maliciosos (malvertising) podem levar a sites falsos ou ao download de outros malwares.

### Sintomas comuns

- Pop-ups e anúncios aparecendo mesmo sem navegar.
- Página inicial ou buscador alterados sem autorização.
- Lentidão no computador e no navegador.
- Extensões ou programas desconhecidos instalados.

### Como se proteger

- Baixar software apenas de fontes oficiais e, na instalação, recusar "ofertas adicionais" e opções pré-marcadas.
- Revisar extensões do navegador e desinstalar as desconhecidas.
- Usar antivírus/antimalware e bloqueadores de anúncios.
- Manter navegador e sistema atualizados.

## 10 - Keylogger

Keylogger (registrador de teclas) é uma ferramenta, em software ou hardware, que registra tudo o que o usuário digita no teclado, de forma oculta, e envia ou armazena essas informações para que o atacante as acesse depois.

É considerado uma forma de spyware e frequentemente chega por meio de um trojan, e-mail malicioso ou download comprometido. Também existe uso legítimo (monitoramento corporativo autorizado, controle parental), mas o foco aqui é o uso malicioso.

### Qual é o objetivo de um keylogger?

- **Roubar credenciais:** Capturar logins e senhas digitados em sites, aplicativos e sistemas.
- **Obter dados financeiros:** Registrar números de cartão, dados de internet banking e códigos digitados.
- **Espionar comunicações:** Ler mensagens, e-mails e conteúdos escritos pelo usuário.
- **Facilitar outros ataques:** As credenciais roubadas permitem invasão de contas, fraudes e movimentação lateral em redes corporativas.

### Tipos de Keylogger

- **Software (por nível de atuação):**
  - *Nível de aplicação (user-mode):* Usa APIs do sistema ou "hooks" para capturar as teclas. É o mais comum.
  - *Nível de kernel:* Atua no núcleo do sistema, sendo mais difícil de detectar.
  - *Baseado em navegador / formulários:* Captura dados inseridos em páginas web antes de serem enviados (form grabbing).
- **Hardware:** Dispositivo físico instalado entre o teclado e o computador (ex.: adaptador USB) ou dentro do próprio teclado. Não deixa rastro no sistema operacional e não é detectado por antivírus.
- **Acústico / por sensores:** Deduz as teclas digitadas a partir do som ou de sensores de movimento (mais raro e sofisticado).

### Como se proteger

- Usar autenticação multifator, pois a senha capturada sozinha deixa de bastar.
- Usar gerenciador de senhas com preenchimento automático, já que o que não é digitado não é capturado.
- Manter antivírus e sistema atualizados; usar soluções anti-keylogger e EDR.
- Evitar digitar dados sensíveis em computadores públicos ou desconhecidos.
- Inspecionar fisicamente conexões do teclado em ambientes de risco.
