# devops-heros — Session 20: GitOps source repo

Git is the single source of truth for these Argo CD applications (see [NeuralSynth/devops-heros › session20](https://github.com/NeuralSynth/devops-heros/tree/main/session20-monitoring-observability-gitops)).

| Path | Argo CD Application | Namespace |
| :--- | :--- | :--- |
| `app/` | `session20-app` (07-argocd) | `session20` |
| `mini/` | `session20-mini` (08-mini-project) | `session20` |

Change a manifest here → `git push` → Argo CD syncs the cluster automatically (`automated`, `prune`, `selfHeal`).
