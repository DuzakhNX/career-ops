# Custom Instructions -- career-ops

<!-- ============================================================
     THIS FILE IS YOURS. It will NEVER be auto-updated.

     Put your own house rules, custom workflows, and automations
     here -- anything you want the agent to ALWAYS do (or never do).

     This is for PROCEDURAL rules ("HOW I want things done").
     For WHO you are (archetypes, narrative, comp, negotiation),
     use modes/_profile.md instead. Keeping the two separate keeps
     each one readable.

     The agent reads this file alongside the system instructions;
     your rules here take precedence over the defaults, as long as
     they don't break the Data Contract (your files are never
     touched, and we never auto-submit an application for you).

     Because this is a user-layer file, anything you write here
     survives `node update-system.mjs`. Put customizations HERE,
     not in CLAUDE.md / modes/_shared.md / other system files --
     those get overwritten on update.
     ============================================================ -->

## House Rules

- **Fraîcheur des offres (OBLIGATOIRE) :** Ne sélectionner et n'évaluer que les offres publiées ou mises à jour il y a au maximum 14 jours à compter de la date de vérification. Toute offre plus ancienne doit être écartée avec le statut `skipped_expired` dans `scan-history.tsv`. Si la date de publication n'est pas disponible, vérifier la page de l'offre avant d'inclure — une offre sans date visible passe uniquement si le contenu confirme qu'elle est active et récente.

## Custom Workflows

(aucun pour l'instant)

## Output Preferences

(aucune pour l'instant)

## Off-Limits

(aucun pour l'instant)
