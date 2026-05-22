# Comandos CLI WiNG 5.8 e 5.9

Este diretorio reune procedimentos e referencias operacionais para redes wireless Extreme WiNG, APs e controladoras/RFS. A pasta `DOCS PDF` nao foi analisada para este indice, conforme solicitado.

## Documentos

| Documento | Para que serve |
| --- | --- |
| `ATUALIZAR FIRMWARE VIA U-BOOT.txt` | Procedimento de recuperacao/atualizacao de firmware via U-Boot para APs como AP650 e AP6532, incluindo modo diagnostico, configuracao TFTP, `progfw`, `tftpboot`, gravacao em flash e comandos de boot. |
| `BOAS PRATICAS PARA UMA REDE WIRELESS.txt` | Lista de boas praticas para WiNG: politicas de firewall, Smart-RF, potencia do radio 2.4 GHz, canais recomendados, remocao de DFS em 5 GHz, largura de canal, LDPC, compatibilidade com 802.11ax e direcao de banda. |
| `C0NFIGURAÇÃO DE REDE WIRELES POR CLI.txt` | Roteiro inicial via CLI para criar uma WLAN, definir SSID, VLAN, criptografia, PSK, aplicar a rede nos radios e configurar RF-Domain. |
| `COMANDOS CLI IMPORTANTES.txt` | Referencia principal de comandos WiNG. Cobre login/reset de fabrica, acesso ao dispositivo, IP de gerenciamento, upgrade de firmware, adocao de APs, radios, firmware primario/secundario, upgrade de APs pela RFS, logs, backup/restauracao, cluster, DHCP, gateway, DNS, RF-Domain, conversao de OS e bloqueio de MAC. |
| `CONECTAR NO AP VIA PUTTY.txt` | Instrucao curta para acesso por console serial usando PuTTY, porta COM e taxas de bit comuns, como 115200 ou 19200. |
| `CONFIGURAÇÃO PARA CRIAÇÃO DE UMA REDE INICIAL.txt` | Checklist de alto nivel para criar uma rede inicial: RF Domain, perfil de controller, WLAN, VLAN, interface GE, perfil de AP, politica DHCP e teste do status da WLAN. |
| `CONFIGURAR DHCP SERVER WING CLI.txt` | Passo a passo para criar uma politica DHCP Server no WiNG, configurar pool, rede, faixa de enderecos, gateway, DNS e aplicar a politica ao dispositivo. |
| `LICENCIAMENTO.txt` | Link de referencia da Extreme Networks sobre licenciamento. |
| `PADRAO DE CONFIGURAÇÃO PARA IMPLANTAÇÃO AP CONTROLLER.txt` | Padrao de implantacao para AP/controller, com sequencia de configuracao de VLANs, interfaces Ethernet, IP, RF-Domain, SSIDs, radios, gateway, DNS, antena externa e virtual controller. |
| `REDE WIRELESS BASICA DO ZERO.txt` | Receita rapida para criar uma rede wireless basica do zero via CLI, incluindo criacao da WLAN, associacao aos radios e configuracao de RF-Domain. |

## Arquivo auxiliar

| Arquivo | Para que serve |
| --- | --- |
| `automação git final.bat` | Menu de automacao Git/GitHub para iniciar repositorio com ou sem Git LFS, autenticar no GitHub CLI, atualizar repositorio com pull/commit/push, configurar nome/e-mail do Git e consultar o remoto atual. Nao e um documento tecnico de WiNG. |

## Sugestao de uso

- Use `COMANDOS CLI IMPORTANTES.txt` como consulta geral.
- Use `CONFIGURAÇÃO PARA CRIAÇÃO DE UMA REDE INICIAL.txt`, `C0NFIGURAÇÃO DE REDE WIRELES POR CLI.txt` ou `REDE WIRELESS BASICA DO ZERO.txt` quando estiver montando uma rede nova.
- Use `BOAS PRATICAS PARA UMA REDE WIRELESS.txt` para ajustes de estabilidade, radiofrequencia e compatibilidade.
- Use `ATUALIZAR FIRMWARE VIA U-BOOT.txt` apenas em cenarios de firmware, recuperacao ou boot via U-Boot.
