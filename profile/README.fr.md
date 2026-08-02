# aubia-dev

[English](README.md) | **Français**

**Aubia fait se relire vos agents IA.**

[Rejoindre la liste d'attente →](https://aubia.dev) | [Journal de bord →](https://aubia.dev/fr/blog) | [Discussions communautaires →](https://github.com/aubia-dev/community) | [@aubia_dev](https://x.com/aubia_dev) | [LinkedIn](https://www.linkedin.com/company/aubia-dev)

![Phase 0 liste d'attente](https://img.shields.io/badge/Phase%200-Liste%20d%27attente-8839ef?style=flat-square&labelColor=1e1e2e)
![Beta 0.1 troisième trimestre 2026](https://img.shields.io/badge/Beta%200.1-T3%202026-1e66f5?style=flat-square&labelColor=1e1e2e&logo=apple&logoColor=cdd6f4)
![Conçu à Paris](https://img.shields.io/badge/Con%C3%A7u%20%C3%A0-Paris%20FR-45475a?style=flat-square&labelColor=1e1e2e)
[![X @aubia_dev](https://img.shields.io/badge/%40aubia__dev-1e1e2e?style=flat-square&logo=x&logoColor=cdd6f4)](https://x.com/aubia_dev)

---

Le moyen le plus simple de ne pas voir une erreur, c'est d'être celui qui l'a écrite. C'est tout aussi vrai pour un agent : Claude rate des détails que Codex voit du premier coup, et Codex pousse une implémentation là où Claude aurait challengé l'approche. Aubia est la couche au-dessus de Claude Code, Codex CLI et Mistral qui leur passe le diff jusqu'à l'accord, et vous laisse arbitrer.

## Ce qu'Aubia ajoute à vos agents IA

- **Cross-review automatique** : un agent implémente, un agent d'une autre famille de modèles relit. Ils s'échangent le diff jusqu'à convergence, sur le nombre d'itérations que vous fixez.
- **Mode Opinions vers Plan exécutable** : soumettez une décision technique à plusieurs modèles simultanément. Chacun argumente sa position, Aubia synthétise les convergences, isole les désaccords, et génère un plan arbitré que vous éditez et exécutez.
- **BYOK** : vos contrats Anthropic, OpenAI et Mistral restent les vôtres. Clés chiffrées dans le keychain de votre OS, aucune revente de tokens, aucune dépendance vendor.
- **Desktop local-first** : les agents tournent en local, chacun dans son propre git worktree isolé. Vos sources ne quittent jamais votre machine.

## Roadmap publique

| Jalon | Quand | Livrable |
|---|---|---|
| Phase 0 | Maintenant | Liste d'attente publique, ce profil, l'espace communautaire, le journal de bord sur aubia.dev |
| Beta 0.1 | Troisième trimestre 2026 | macOS Apple Silicon : cross-review, Mode Opinions vers Plan exécutable, cockpit local. Premières invitations de la liste d'attente |
| Beta 0.2 et suivantes | Après la 0.1 | Gemini via Antigravity CLI, inférence locale Ollama, cross-review en DAG multi-étapes, CI auto-fix, companion mobile |
| 1.0 | Sortie de beta | Support Linux et Windows |

## Ressources

- **Liste d'attente** : <https://aubia.dev>
- **Journal de bord** : <https://aubia.dev/fr/blog>
- **Communauté** : [aubia-dev/community](https://github.com/aubia-dev/community)
- **X** : [@aubia_dev](https://x.com/aubia_dev)
- **LinkedIn** : [Aubia](https://www.linkedin.com/company/aubia-dev)
- **Presse, partenariats** : `contact@aubia.dev`
- **Vie privée, RGPD** : `dpo@aubia.dev`

Aubia est conçu et écrit par Mike EL GHALI, depuis Paris. Les décisions qui le façonnent se racontent sur le journal de bord, article après article.
