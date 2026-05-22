# Contexto do projeto

## 2026-05-22

- Este diretorio e uma base de manuais e procedimentos para redes wireless Extreme WiNG 5.8/5.9, APs e controladoras/RFS. O conteudo principal esta em arquivos `.txt` com comandos CLI e roteiros operacionais.
- O usuario pediu a criacao de um `README.md` explicando para que serve cada documento, sem necessidade de analisar a pasta `DOCS PDF`. Por isso, os PDFs foram ignorados na montagem do indice.
- O `README.md` existente tinha apenas o titulo generico `# Novo Projeto`; ele foi substituido por um indice descritivo dos documentos do diretorio raiz.
- Documentos mapeados:
  - `COMANDOS CLI IMPORTANTES.txt`: referencia central de comandos WiNG, incluindo login/reset, IP de gerencia, firmware, adocao de APs, radios, upgrade, logs, backup/restauracao, cluster, DHCP, gateway/DNS, RF-Domain, conversao de OS e bloqueio de MAC.
  - `BOAS PRATICAS PARA UMA REDE WIRELESS.txt`: boas praticas de firewall, Smart-RF, canais, potencia, DFS, largura de canal, LDPC, 802.11ax e direcao de banda.
  - `ATUALIZAR FIRMWARE VIA U-BOOT.txt`: recuperacao/atualizacao de firmware via U-Boot/TFTP para APs como AP650 e AP6532.
  - `CONFIGURAR DHCP SERVER WING CLI.txt`: criacao e aplicacao de politica DHCP Server no WiNG.
  - `CONECTAR NO AP VIA PUTTY.txt`: acesso serial via PuTTY, porta COM e baud rate.
  - `C0NFIGURAÇÃO DE REDE WIRELES POR CLI.txt` e `REDE WIRELESS BASICA DO ZERO.txt`: roteiros parecidos para criar WLAN, SSID, VLAN/PSK, associar aos radios e configurar RF-Domain.
  - `CONFIGURAÇÃO PARA CRIAÇÃO DE UMA REDE INICIAL.txt`: checklist resumido para criar rede inicial com RF Domain, perfis, WLAN/VLAN/GE, DHCP e teste.
  - `PADRAO DE CONFIGURAÇÃO PARA IMPLANTAÇÃO AP CONTROLLER.txt`: checklist de implantacao AP/controller com VLANs, interface Ethernet, IP, RF-Domain, SSIDs, radios, gateway, DNS, antena externa e virtual controller.
  - `LICENCIAMENTO.txt`: link de referencia da Extreme Networks sobre licenciamento.
- `automação git final.bat` foi identificado como arquivo auxiliar para automacao Git/GitHub, nao como documento tecnico de WiNG.
- Nao houve alteracao de codigo nem qualquer necessidade de migracao Supabase/banco de dados nesta tarefa.
