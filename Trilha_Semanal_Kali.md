# Plano Semanal Interativo - Trilha de Estudos Kali Linux

## Semana 1: Fundamentos e Reconhecimento
**Objetivos:**
- Dominar o terminal e o uso básico do Kali Linux.
- Compreender e configurar repositórios.
- Realizar reconhecimento passivo e ativo.

**Ferramentas:**
- Terminal, `ifconfig`, `ping`, `apt`, `sources.list`
- `whois`, `nslookup`, `theHarvester`
- `Nmap`, `Dnsenum`, `netdiscover`, `Dnsrecon`, `Fierce`, `Sublist3r`

**Prática sugerida:**
- Realize um mapeamento de rede local com Nmap.
- Faça uma enumeração passiva de um domínio de teste com theHarvester.

## Semana 2: Enumeração e Scanning
**Objetivos:**
- Identificar versões de serviços e vulnerabilidades.
- Realizar varreduras de servidores web e capturar pacotes.

**Ferramentas:**
- `Nmap -sV -A`, `Netcat`, `Enum4linux`
- `Nikto`, `WhatWeb`, `Dirb`, `Gobuster`
- `Wireshark`, `tcpdump`, `OpenVAS`, `p0f`

**Prática sugerida:**
- Capturar tráfego HTTP com Wireshark em uma máquina local.
- Rodar varredura completa em VM vulnerável (ex: Metasploitable2).

## Semana 3: Exploração de Falhas
**Objetivos:**
- Aplicar exploits e gerar payloads personalizados.
- Explorar falhas em aplicações web.

**Ferramentas:**
- `Metasploit`, `msfvenom`, `searchsploit`
- `Burp Suite`, `OWASP ZAP`, `sqlmap`
- Cheatsheets de reverse shell, `netcat`, `socat`, `chisel`

**Prática sugerida:**
- Realizar um ataque SQLi simples com sqlmap.
- Obter shell reverso com msfvenom + Metasploit.

## Semana 4: Pós-Exploitation e Persistência
**Objetivos:**
- Escalar privilégios e manter acesso persistente.
- Coletar credenciais e mover-se lateralmente.

**Ferramentas:**
- `linPEAS`, `PowerUp`, `mimikatz`, `laZagne`
- `CrackMapExec`, `Impacket`, `PsExec`, `Veil`, `Shellter`

**Prática sugerida:**
- Executar privesc em uma máquina Linux com linPEAS.
- Criar tarefa agendada no Windows via schtasks para persistência.

## Semana 5: Forense Ofensiva e C2
**Objetivos:**
- Analisar rastros deixados.
- Controlar múltiplos alvos com frameworks de C2.

**Ferramentas:**
- `Volatility`, `Autopsy`, `Empire`, `Covenant`, `Sliver`
- `Kali NetHunter`, `cSploit`, dispositivos IoT

**Prática sugerida:**
- Criar e gerenciar agentes em um lab com Sliver.
- Usar NetHunter em rede local para mapeamento rápido.
