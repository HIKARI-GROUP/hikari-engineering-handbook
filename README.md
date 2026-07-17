# HIKARI Engineering Handbook

<p align="center">
  <strong>Guide d'ingénierie & bonnes pratiques</strong>
</p>

## Sommaire

1. [Standards de code](#standards)
2. [Architecture](#architecture)
3. [Review checklist](#review)
4. [Déploiement](#déploiement)
5. [Sécurité](#sécurité)
6. [Onboarding](#onboarding)

## Standards

- TypeScript / JavaScript ESM
- ESLint + Prettier
- Tests unitaires (Vitest)
- Commits conventionnels
- Pas de secrets dans le code

## Architecture

```
Frontend (React + Tailwind)
  ↓
Backend (Base44 functions — Deno)
  ↓
Database (Base44 entities)
  ↓
Integrations (OAuth connectors, Stripe, LLM)
```

## Review checklist

- [ ] Tests passent
- [ ] Pas de secrets
- [ ] Documentation à jour
- [ ] Accessibility (AA)
- [ ] Responsive
- [ ] Performance acceptable

## Sécurité

- Secrets via variables d'environnement
- Validation des entrées
- Authentification requise pour actions sensibles
- Audit de dépendances régulier

## Onboarding

1. Lire ce handbook
2. Cloner un repo
3. Lancer le projet en local
4. Prendre une `good first issue`
5. Ouvrir une PR

## Licence

CC BY-SA 4.0 © HIKARI GROUP