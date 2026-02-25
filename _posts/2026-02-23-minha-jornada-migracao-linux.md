---
layout: post
title: "Minha Jornada de Migração para o Linux: Do Caos do Windows ao CachyOS"
categories: linux nixos bazzite cachyos
author: Marcelo Mogami
modified_date: 2026-02-24
---

Sempre tive vontade de expressar o que ando fazendo, mas sentia que escrever era um processo travado. Resolvi testar um fluxo novo: gravar um audiolog e usar o **Whisper** para transcrever tudo. O resultado é este post, onde conto como foi meu último mês abandonando o Windows e voltando para o ecossistema Linux.

## O Motivo da Mudança

A motivação veio de amigos que já tinham migrado — um por questões de segurança após ser hackeado no Windows e outro porque o hardware dele não aceitava o Windows 11, o que o fez sentir que era melhor migrar. Eu já estava cansado do sistema da Microsoft e decidi que era hora de voltar ao Linux.

## A Saga das Distros: Testes e Frustrações

Minha pesquisa me levou a três caminhos principais, e cada um teve seus altos e baixos:

### 1. NixOS: O Sonho da Reprodutibilidade

O conceito do **NixOS** me fascinou. Ter todo o sistema descrito em um único arquivo de configuração significa que, se eu formatar ou trocar de PC, basta rodar o arquivo e tudo volta a ser como era.

* **O Problema:** A minha placa NVIDIA.
* **O Resultado:** Tentei de tudo — IA, Reddit, rollbacks (que o Nix faz muito bem) — mas os drivers simplesmente não colaboraram com a minha saída HDMI. Tive que abandonar a ideia por enquanto.

### 2. Bazzite: A Experiência "Console" no Desktop

Depois fui para o **Bazzite** (baseado em Fedora), focado em games e sistemas imutáveis.

* **O Problema:** O meu setup de monitores é "esquisito" (Notebook + Monitor HDMI pela GPU NVIDIA + Monitor Vertical USB-C pela GPU Intel).
* **O Conflito:** No KDE, tive problemas com o controle de janelas ao usar o **FreeRDP** para trabalhar. O foco das janelas ficava "maluco", sobrepondo o acesso remoto de um jeito que eu não conseguia clicar em nada.
* **Tentativa com GNOME:** Até instalei a versão com GNOME, onde o RDP funcionou bem, mas não me adaptei à interface. Achei ruim de configurar e nada intuitivo para o meu uso.

## O Porto Seguro: CachyOS

Depois de rodar por NixOS e Bazzite, lembrei do tempo em que usei Arch (via Arco Linux) e gostei bastante. Como o Arco foi descontinuado, decidi testar a distro do momento: o **CachyOS**.

O CachyOS é focado em performance, já vem com drivers otimizados para gamers e, para a minha surpresa, **tudo funcionou de primeira**. Instalei, configurei e o sistema está rodando liso. Até esse esquema de transcrição via GPU que usei para este post deu um pouquinho de trabalho para configurar no começo, mas agora está voando.

## Conclusão

Ainda apanho de algumas coisas, mas estou me divertindo muito no processo. Por enquanto, vou sossegar no CachyOS. O NixOS ainda está nos meus planos para o futuro, talvez quando os repositórios atualizarem os kernels e drivers, mas hoje o que eu precisava era de um sistema que funcionasse e me deixasse ser produtivo.