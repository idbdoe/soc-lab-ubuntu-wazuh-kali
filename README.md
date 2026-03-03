# SOC Lab - Ubuntu + Wazuh + Kali

## Objetivo
Simular ataques controlados em um servidor Ubuntu e monitorar os logs utilizando Wazuh para estudos.

## Ambiente
- Ubuntu Server (Vítima)
- Windows 11 (Wazuh)
- Kali Linux (Atacante)

## Arquitetura
[Kali (VM no Windows 11)]
           ↓
  [Ubuntu Server (Notebook)]
           ↓
      Wazuh (Windows 11)


### Instalação do Ubuntu Server

No meu caso, não vou estar usando uma vm. Vou instalar diretamente em uma máquina usando o Ubuntu Server, criando um pendrive bootavel com o rufus. A versão utilizada do Ubuntu Server é a 24.04.4 LTS
