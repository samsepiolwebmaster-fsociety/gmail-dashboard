# Gmail Dashboard — Contexte Projet

## Objectif
Dashboard Gmail interactif pour visualiser et gérer la boîte mail samsepiolwebmaster@gmail.com. Evolution progressive vers un système multi-comptes pilotée par IA.

## État Actuel (2026-05-06)

### V1 — Dashboard statique (EN COURS)
- **Status**: ✅ Code livré, 📦 prêt à deployer
- **Tech**: HTML + CSS vanilla (dark theme Syne + DM Mono)
- **Contenu**: 
  - 4 metrics (non lus, GitHub, à traiter, newsletters)
  - Alerte GitHub 2FA urgente
  - 2 panneaux: emails + labels suggérés
  - 6 tips d'optimisation Gmail
- **URLs**: 
  - GitHub: https://github.com/samsepiolwebmaster-fsociety/gmail-dashboard
  - Netlify: https://gmail-dashboard-sam.netlify.app
  - siteId: `b4adec13-960b-4e01-9703-0da13e51380e`

### V2 — Dashboard multi-comptes + Claude Agent (BACKLOG)
- **Concept**: Node.js/Express + Gmail API (OAuth2) + Claude API
- **Principe**: Claude reçoit des tools Gmail (lire, chercher, répondre, labeler, archiver) et agit sur instruction
- **Prérequis**: Google Cloud Console project + OAuth2 credentials (15 min setup)
- **Scope**: ~2 sessions Claude Code si démarré depuis zéro
- **Priority**: Moyenne (V1 doit être live d'abord)

## Prochaines étapes
1. ✅ Organiser dans 1-projets/gmail-dashboard
2. → Push GitHub (git init + commit + push)
3. → Deploy Netlify (netlify deploy --prod)
4. → Ajouter bloc "V2 — Coming soon" dans le dashboard
5. → Archiver cette session dans 4-archives/

## Files
- `index.html` — Dashboard principal (V1)
- `netlify.toml` — Config Netlify (publish = ".")
- `contexte-session-precedente.md` — Full context de la découverte
- `contexte.md` — Ce fichier

## Credentials
```
GitHub:   samsepiolwebmaster-fsociety
Netlify:  accountId: 67a4dc92f8ab34353d42be8d
          siteId: b4adec13-960b-4e01-9703-0da13e51380e
Gmail:    samsepiolwebmaster@gmail.com
```

---

**Dernière mise à jour**: 2026-05-06 (organisation + rangement IPCRA)
