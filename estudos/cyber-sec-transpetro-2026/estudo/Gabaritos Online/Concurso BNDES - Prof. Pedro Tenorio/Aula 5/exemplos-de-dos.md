## Jolt2
É um ataque do tipo Denial of Service que envia fragmentos de pacotes IP maliciosos e inválidos para um servidor. O sistema alvo consome todos os seus recursos de processamento (CPU) tentando remontar esses pacotes impossíveis, o que acaba travando ou reiniciando a máquina.
## Smurf
É um ataque de amplificação de rede. O atacante envia uma grande quantidade de pacotes de dados ICMP (como um teste de "ping") para um endereço de broadcast da rede, fingindo ser a vítima (usando IP falsificado). Todos os dispositivos daquela rede respondem à vítima ao mesmo tempo, congestionando completamente a sua conexão.
## UDP Storm
Explora o protocolo UDP (que não exige confirmação de recebimento). O atacante conecta duas portas ou serviços de rede de forma que eles fiquem enviando respostas automatizadas um para o outro infinitamente. Isso cria um loop que consome toda a largura de banda da rede.
## SYN Flood
Explora o processo de conexão do protocolo TCP (conhecido como Three-Way Handshake). O atacante envia milhares de solicitações de conexão (SYN), mas ignora as respostas do servidor (SYN-ACK). O servidor fica esperando a confirmação final de braços abertos, esgotando sua memória com conexões pela metade até parar de responder.
## Teardrop
Envia fragmentos de pacotes IP sobrepostos e com tamanhos falsificados para o alvo. Quando o sistema operacional da vítima tenta juntar esses pedaços para ler a mensagem original, ele se confunde devido a um bug no código de remontagem, gerando falhas graves no sistema (como a famosa tela azul).
