# claude-toolbox

Inventaire visuel et factuel de **tout ce que Claude Code peut actionner sur ce poste** : skills `.md`, commandes intégrées, serveurs MCP connectés et sous-agents.

Page statique unique (HTML + Tailwind via CDN, **aucun build**), recherche + filtres par catégorie, design dark « dev-tool » généré via la skill **ui-ux-pro-max** (JetBrains Mono / IBM Plex Sans, accent `#22C55E`).

## Contenu recensé

| Catégorie | Nombre | Exemples |
|---|---|---|
| Skills `.md` actifs | 15 | `ui-ux-pro-max`, `all-skills`, `stop-slop`, 9× `threejs-*`, `new-odoo-project`, `odoo-theme-fix` |
| Commandes intégrées | 14 | `deep-research`, `code-review`, `verify`, `run`, `schedule`, `loop`, `claude-api`… |
| Serveurs MCP | 9 (~200 outils) | Figma, Canva, Adobe Firefly, After Effects, Shopify, Gmail, Calendar, Drive, 21st.dev |
| Sous-agents | 6 | `general-purpose`, `Explore`, `Plan`, `claude-code-guide`… |

⚠️ **52 skills orphelins** : des symlinks dans `~/.claude/skills` pointent vers `VAIN-PARTAGE/.agents/skills/`, un dossier qui n'existe plus → cassés et inutilisables tant que la cible n'est pas restaurée.

## Développement

Aucune dépendance. Ouvrir `index.html` dans un navigateur.

## Déploiement

Site statique déployé sur Vercel (framework « Other », pas de build step).
