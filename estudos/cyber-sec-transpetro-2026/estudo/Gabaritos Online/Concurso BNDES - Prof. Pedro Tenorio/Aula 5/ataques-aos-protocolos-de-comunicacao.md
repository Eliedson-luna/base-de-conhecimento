# Ataques aos Protocolos de Comunicacao


## Sobre

Ataques aos protocolos de comunicação são ações maliciosas que exploram falhas de design, ausência de criptografia ou brechas de implementação em regras de troca de dados (como TCP/IP, HTTP, MQTT) para interceptar, modificar ou interromper informações.

## Principais Tipos de Ataques
- Man-in-the-Middle (MitM): O invasor intercepta a comunicação entre dois dispositivos para roubar ou alterar dados sem que os usuários percebam.
- Negação de Serviço (DoS / DDoS): Sobrecarga de requisições em um protocolo específico (como HTTP/2 Rapid Reset) para derrubar serviços e redes.
- Ataques de Injeção e Spoofing: Falsificação de pacotes de IP ou inserção de comandos maliciosos em protocolos sem autenticação robusta.
- Exploração em IoT (MQTT/CoAP): Desvio de dados ou comandos em dispositivos conectados devido à falta de criptografia nativa em protocolos leves.

## Como se Proteger
- Criptografia ponta a ponta: Uso de TLS/HTTPS e versões seguras de protocolos de transporte e aplicação.
- Autenticação forte: Implementar certificados digitais e autenticação mútua (mTLS).
- Atualizações regulares: Corrigir falhas de implantação e bugs em bibliotecas de software.
- Monitoramento de rede: Empregar firewalls modernos e ferramentas de detecção de anomalias.

