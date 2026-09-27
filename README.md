### Fabrice Faucheux — sécurité et administration Google Workspace

[Français](#français) · [English](#english)

<a name="français"></a>

Responsable applicatif sur la plateforme Google Workspace depuis 15 ans, parc de 8 500 comptes.
**Google Product Expert Platine.**

Je rends visible ce que la console d'administration Google Workspace montre mal : les
applications tierces branchées sur les comptes, les partages Drive qui débordent, les
écarts au référentiel CIS, l'usurpation de domaine. Puis j'outille la correction, sans
serveur, en Google Apps Script.

#### Projets

| Projet | Ce qu'il fait |
|---|---|
| [cis-benchmarks](https://github.com/FabriceFx/cis-benchmarks) | Audit automatisé et registre de conformité au CIS Google Workspace Foundations Benchmark v1.4 |
| [workspace-oauth-audit](https://github.com/FabriceFx/workspace-oauth-audit) | Inventaire des applications tierces et de l'IA fantôme : portées, qui les a autorisées, volume réellement extrait |
| [gdrive-shares-audit](https://github.com/FabriceFx/gdrive-shares-audit) | Vue de chaque utilisateur sur ses partages Drive, Mon Drive et Drives partagés |
| [dmarc-sheets](https://github.com/FabriceFx/dmarc-sheets) | Sonde et tableau de bord DMARC dans Google Sheets, sans serveur |
| [jsm-google-workspace-gateway](https://github.com/FabriceFx/jsm-google-workspace-gateway) | Opérations d'administration Workspace déclenchées depuis Jira Service Management |
| [TempoSheet](https://github.com/FabriceFx/TempoSheet) | Feuilles d'heures générées depuis Google Agenda |

#### Ma façon de travailler

| Principe | Pourquoi |
|---|---|
| Moindre privilège | Chaque portée OAuth demandée est justifiée ; quand elle ne se décline pas en lecture seule, la documentation le dit |
| Plan puis application | Toute action irréversible est d'abord écrite dans un plan relu, avec le nombre exact d'objets concernés |
| Testé hors de Google | Un banc d'essai Node rejoue les données réelles des API, avant tout déploiement |
| Rapport honnête | Un fait et une présomption ne partagent jamais une colonne ; une case vide veut dire « non mesuré » |

#### Me trouver

[faucheux.bzh](https://faucheux.bzh) · [LinkedIn](https://www.linkedin.com/in/fabricefaucheux/) · [L'Atelier Informatique](https://atelier-informatique.com/) (blog)

---

<a name="english"></a>

### English

Google Workspace application owner for 15 years, 8,500 accounts.
**Platinum Google Product Expert.**

I make visible what the Google Workspace admin console shows poorly: third-party apps
connected to user accounts, overexposed Drive shares, gaps against the CIS benchmark,
domain spoofing. Then I build the remediation tooling, serverless, in Google Apps Script.

**Projects** — see the table above: CIS compliance audit, third-party app and shadow-AI
audit, Drive shares audit, DMARC dashboard, Jira Service Management gateway, Calendar
timesheets.

**How I work** — least privilege, plan before apply, tested outside Google, honest reporting.

