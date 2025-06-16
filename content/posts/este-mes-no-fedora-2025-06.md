+++
title = "Este Mês no Fedora (junho 2025)"
date = 2025-06-13T20:58:49-03:00
description = "Atualização sobre o que eu fiz no Projeto Fedora em junho de 2025."
tags = ["fedora"]
draft = true
+++

## Resultado das Eleições

Em 3 de junho, os [resultados das eleições][f42-elections] no Projeto Fedora foram divulgados. Fiquei feliz, pois todos os meus candidatos favoritos foram eleitos. Aqui estão os resultados:

+ **Council**: Miro Hrončok e Aleksandra Fedorova
+ **FESCo**: Neal Gompa, Stephen Gallagher, Fabio Valentini e Michel Lind
+ **Mindshare Committee**: Emma Kidney, Sumantro Mukherjee, Akashdeep Dhar e Luis Bazan
+ **EPEL Steering Committee**: Davide Cavalca, Robbie Callicotte e Neal Gompa

## Manutenção de Pacotes

Manutenção somente do pacote [bfs][bfs-src].

### Novos Pacotes

Um [usuário pediu][bfs-epel10-request] se eu também poderia manter o bfs para EPEL 10.

| Pacote         | Versão | Lançamento             |
|----------------|--------|------------------------|
| [bfs][bfs-src] | 4.0.6  | [1.el10_1][bfs-epel10] |

### Atualizações

| Pacote         | Versão | Lançamento                             |
|----------------|--------|----------------------------------------|
| [bfs][bfs-src] | 4.0.7  | [1.fc43][bfs-fc43], [1.fc42][bfs-fc42] |

[f42-elections]: https://communityblog.fedoraproject.org/f42-elections-results/
[bfs-src]: https://src.fedoraproject.org/rpms/bfs
[bfs-epel10-request]: https://bugzilla.redhat.com/show_bug.cgi?id=2371050
[bfs-epel10]: https://bodhi.fedoraproject.org/updates/FEDORA-EPEL-2025-7e71075e97
[bfs-fc43]: https://bodhi.fedoraproject.org/updates/FEDORA-2025-a9d3b24d09
[bfs-fc42]: https://bodhi.fedoraproject.org/updates/FEDORA-2025-3abca4b043
