# Airplan

[ChatGPT](#chatgpt) · [Claude](#claude) · [Claude Code](#claude-code) · [Codex](#codex)

Connectez votre assistant IA à votre compte Airplan pour consulter et modifier
vos projets de permis et études de faisabilité. Airplan vous aide à préparer
les dossiers administratifs de permis d’urbanisme en Wallonie.

Le plugin connecte votre assistant au serveur MCP Airplan.

## Installation

### ChatGPT

#### ChatGPT (l'application)

Dans l’application **ChatGPT Desktop** :

1. Ouvrez **Plugins**, puis **Ajouter → Ajouter une marketplace**.
2. Dans le formulaire **Ajouter une marketplace de plug-in**, renseignez :

   | Champ | Valeur |
   | --- | --- |
   | **Source** | `airplan-tech/ai` |
   | **Réf. Git** | Laisser vide |
   | **Chemins partiels** | Laissez vide. |

3. Cliquez sur **Ajouter une marketplace**.
4. Dans l’onglet **Personnel**, sélectionnez le plugin **Airplan** du catalogue
   **Airplan**, puis cliquez sur le bouton **+** pour l’installer.
5. Suivez les étapes de connexion proposées, connectez-vous à votre compte
   Airplan et autorisez l’accès.
6. Ouvrez une nouvelle conversation de travail et sélectionnez
   **Airplan** en saisissant **@Airplan**.

#### ChatGPT (chatgpt.com)

Si vous utilisez ChatGPT sur le web plutôt que via l’application :

1. Ouvrez la page [Plugins de ChatGPT](https://chatgpt.com/plugins), puis
   **Ajouter → Ajouter un serveur MCP personnalisé**.
2. Renseignez les champs suivants :

   | Champ | Valeur |
   | --- | --- |
   | **Nom** | `Airplan` |
   | **Description** (facultatif) | Consultez et modifiez vos projets de permis et études de faisabilité Airplan. |
   | **URL du serveur** | `https://workspace.airplan.be/mcp/workspace` |
   | **Authentification** | **OAuth** |

3. Prenez connaissance de l’avertissement, cochez la case de confirmation,
   puis cliquez sur **Créer en tant que plugin**.
4. Suivez les étapes de connexion proposées, connectez-vous à votre compte
   Airplan et autorisez l’accès. Installez le plugin si ChatGPT vous le propose.
5. Ouvrez une nouvelle conversation et sélectionnez **Airplan** en saisissant
   **@Airplan**.

### Claude

Dans l’application **Claude Desktop** ou sur **Claude.ai** :

1. Ouvrez **Paramètres → Plug-ins**.
2. Cliquez sur **Ajouter → Ajouter une marketplace**, puis sur
   **Ajouter depuis un dépôt**.
3. Dans le champ **URL**, saisissez :

   ```text
   airplan-tech/ai
   ```

4. Pour recevoir les mises à jour du catalogue, laissez l’option
   **Synchroniser automatiquement** activée, puis cliquez sur **Synchro**.
5. Sélectionnez **Airplan** dans le catalogue et installez le plugin.
6. Ouvrez son onglet **Connecteurs**, ajoutez le connecteur Airplan si nécessaire,
   puis cliquez sur **Connecter**.
7. Connectez-vous à votre compte Airplan et autorisez l’accès.

### Claude Code

Dans votre terminal, avec une version récente de Claude Code, ajoutez le
catalogue puis installez le plugin :

```bash
claude plugin marketplace add airplan-tech/ai
claude plugin install airplan@airplan
```

Lancez ensuite la connexion à Airplan :

```bash
claude mcp login plugin:airplan:airplan
```

Connectez-vous à votre compte Airplan dans le navigateur et autorisez l’accès.
Démarrez ensuite une nouvelle session pour utiliser le plugin :

```bash
claude
```

### Codex

Dans votre terminal, ajoutez le catalogue puis installez le plugin :

```bash
codex plugin marketplace add airplan-tech/ai
codex plugin add airplan@airplan
```

Connectez-vous à votre compte Airplan dans le navigateur et autorisez l’accès.
Démarrez ensuite une nouvelle session Codex pour utiliser le plugin.

## Assistance et licence

[Guide de connexion](https://airplan.be/aide/connecter-agent-ia-mcp) ·
[Centre d’aide](https://airplan.be/aide) ·
[Protection des données](https://airplan.be/rgpd) ·
[Conditions d’utilisation](https://airplan.be/cgu) ·
[bonjour@airplan.be](mailto:bonjour@airplan.be)

Copyright © 2026 Airplan SRL.

Ce dépôt est distribué sous licence Apache-2.0. Voir [LICENSE](LICENSE).
