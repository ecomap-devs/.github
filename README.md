# .github da organização EcoMapBrasil

O que o GitHub mostra na página da organização mora em [`profile/README.md`](profile/README.md).

O banner em `profile/arte/banner.svg` é o do repositório [`semestre-4-flutter`](https://github.com/ecomap-devs/semestre-4-flutter),
gerado por `node .github/arte/gerar.mjs` a partir dos alertas do DETER, com o subtítulo
trocado. Se o de lá mudar, copie de novo e troque a segunda linha.

## Versões e releases

Cada repositório ativo tem o próprio guia, com o passo a passo e o que fazer em cada erro:

| Repositório | Guia | O que uma release faz |
|---|---|---|
| `semestre-4-flutter` | [RELEASES.md](https://github.com/ecomap-devs/semestre-4-flutter/blob/main/RELEASES.md) | Publica o APK assinado, que é como o app chega a quem usa |
| `semestre-4-nextjs` | [RELEASES.md](https://github.com/ecomap-devs/semestre-4-nextjs/blob/main/RELEASES.md) | Só registra a versão: o site vai ao ar a cada merge |

Nos dois, a release sai de uma tag `vX.Y.Z` na `main`, e os números são independentes. Os
repositórios dos semestres 1 a 3 são versões congeladas: cada um tem uma única release, feita à
mão, e não recebe outras. Este repositório não tem releases.

## Licença

[MIT](LICENSE).
