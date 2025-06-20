+++
title = "Este mês no Fedora (junho 2025)"
date = 2025-06-13T20:58:49-03:00
description = "Atualização sobre o que eu fiz no Projeto Fedora em junho de 2025."
tags = ["fedora"]
draft = true
+++

## Resultado das eleições

Em 3 de junho, os [resultados das eleições][f42-elections] no Projeto Fedora foram divulgados. Fiquei feliz, pois todos os meus candidatos favoritos foram eleitos. Aqui estão os resultados:

+ **Council**: Miro Hrončok e Aleksandra Fedorova
+ **FESCo**: Neal Gompa, Stephen Gallagher, Fabio Valentini e Michel Lind
+ **Mindshare Committee**: Emma Kidney, Sumantro Mukherjee, Akashdeep Dhar e Luis Bazan
+ **EPEL Steering Committee**: Davide Cavalca, Robbie Callicotte e Neal Gompa

## Manutenção de pacotes

A atualização do bfs foi simples. Já o pdfmixtool teve grandes mudanças, incluindo a troca de Qt5 para Qt6. Aproveitei para remover os patches e começar a usar [rpmautospec][rpmautospec-doc].

### Novos pacotes

Um [usuário pediu][bfs-epel10-request] se eu também poderia manter o bfs para EPEL 10.

| Pacote         | Versão | Lançamento                                     |
|----------------|--------|------------------------------------------------|
| [bfs][bfs-src] | 4.0.6  | [1.el10_1][bfs-el10_1], [1.el10_0][bfs-el10_0] |

### Atualizações

| Pacote                       | Versão | Lançamento                             |
|------------------------------|--------|----------------------------------------|
| [bfs][bfs-src]               | 4.0.7  | [1.fc43][bfs-fc43], [1.fc42][bfs-fc42] |
| [pdfmixtool][pdfmixtool-src] | 1.2.0  | [1.fc43][pdfmixtool-fc43]              |

## Mudança na página da Wiki

Atualizei [minha página da Wiki][xfgusta-wiki]. Alterei a seção sobre mim e de contatos. A página está disponível em Inglês somente.

[f42-elections]: https://communityblog.fedoraproject.org/f42-elections-results/
[bfs-src]: https://src.fedoraproject.org/rpms/bfs
[pdfmixtool-src]: https://src.fedoraproject.org/rpms/pdfmixtool
[bfs-epel10-request]: https://bugzilla.redhat.com/show_bug.cgi?id=2371050
[bfs-el10_1]: https://bodhi.fedoraproject.org/updates/FEDORA-EPEL-2025-7e71075e97
[bfs-el10_0]: https://bodhi.fedoraproject.org/updates/FEDORA-EPEL-2025-0984fb1c8d
[rpmautospec-doc]: https://docs.pagure.org/fedora-infra.rpmautospec/index.html
[bfs-fc43]: https://bodhi.fedoraproject.org/updates/FEDORA-2025-a9d3b24d09
[bfs-fc42]: https://bodhi.fedoraproject.org/updates/FEDORA-2025-3abca4b043
[pdfmixtool-fc43]: https://bodhi.fedoraproject.org/updates/FEDORA-2025-2e3988d450
[xfgusta-wiki]: https://fedoraproject.org/wiki/User:Xfgusta
