# lab-redes-01

![GitHub License](https://img.shields.io/github/license/alesantosasr/lab-redes-01)

Aluno: Alexandre Santos de Araujo

#laboratorio de redes 01 projeto de rede local

Data: 09/03/2026

---

##1. Objetivo
Implementar uma rede local simples conectando 3 notebooks a um roteador wireless com switch e um impressora de rede.

O projeto será dividido em duas etapas:

1. Simulação da rede no Cisco Packet Tracer
2. Implementaçãoi da rede no laborátorio real.

---

## 2. Equipamentos utilizados neste laboratorio:

- 3 notebooks
- 1 roteador wireless com 1 porta Wan e 4 portas Lan
- 1 impressora de rede
- cabos de rede

  ---

## 3. Topologia da rede 

Diagrama lógico da rede usada neste laborátorio

```mermaid
grafh TD

WAN[Internet / WAN do Provedor

Router[Roteador Wireless<br>1 Porta WAN<Porta>4 Portas LAN

PC1[Notebook 1]
PC2[Notebook 2]
PC3[Notebook 3]

Printer[Impressora de Rede]

WAN --> | Porta WAN | Router

Router --> |LAN 1| PC1
Router --> |LAN 2| PC2
Router --> |LAN 3| PC3
Router --> |LAN 4| Printer


```
