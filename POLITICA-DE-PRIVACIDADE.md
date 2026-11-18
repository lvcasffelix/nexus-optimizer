# Política de Privacidade

> Versão 1.1 — em vigor a partir de 17/11/2026. Ao usar o NEXUS Optimizer, você concorda com este documento.

**Responsável pelo Software:** Equipe NEXUS Optimizer · **Contato:** pelo canal oficial onde o NEXUS Optimizer é disponibilizado

## 1. Resumo
O NEXUS Optimizer funciona no seu computador e **não envia dados pessoais nem dados de uso ao desenvolvedor**.
Não há telemetria, conta de usuário, publicidade ou rastreamento.

## 2. O que o Software lê no seu computador
Para diagnosticar e otimizar, o Software lê localmente: modelo de processador, placa de vídeo, memória e discos;
uso de CPU/GPU/RAM; lista de programas em execução e de inicialização; configurações do Windows relacionadas a
jogos, energia, segurança e privacidade; nome do computador e versão do Windows. Essas leituras ficam no seu PC.

## 3. O que fica salvo e onde
Somente no seu computador, na pasta `%LOCALAPPDATA%\NexusOptimizer`:
- histórico de alterações (valores originais das configurações alteradas, para permitir a reversão);
- resultados de benchmark, perfis por jogo (incluindo o caminho do executável escolhido) e preferências;
- registros de funcionamento (logs), que podem conter caminhos de pastas — e, portanto, o nome do seu usuário do Windows.

## 4. Comunicação pela internet
O Software só usa a rede quando você inicia o **teste de latência**: envia pings ao seu roteador, a 1.1.1.1
(Cloudflare), a 8.8.8.8 (Google) e a um servidor que você digitar, e faz uma consulta de DNS. Esses serviços
recebem apenas o que qualquer ping recebe (seu endereço IP). Links de ajuda abrem no seu navegador.

## 5. Como apagar seus dados
Feche o NEXUS e apague a pasta `%LOCALAPPDATA%\NexusOptimizer`. Atenção: apagar o histórico de alterações impede
reverter pelo NEXUS as alterações ainda ativas — reverta-as antes em "Histórico & Restauração".

## 6. Segurança
Os arquivos são gravados de forma atômica para evitar corrupção. O Software roda sem privilégios de administrador
e só pede elevação para a operação específica que precisar, após sua confirmação.

## 7. Mudanças futuras
Se, no futuro, houver qualquer coleta de dados (por exemplo, relatórios de erro, conta ou atualização on-line),
esta política será atualizada **antes**, informando finalidade, base legal (LGPD), prazo de guarda, compartilhamento
e como exercer seus direitos (LGPD, art. 18), e a coleta será opcional quando a lei exigir.
