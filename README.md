# Redux-Saga Testing

An AI agent skill for writing tests for Redux Sagas using redux-saga-test-plan, runSaga, and manual generator testing. Works with Jest and Vitest.

## Install

```bash
npx skills add anivar/redux-saga-testing -g
```

## What's Inside

- **expectSaga** (integration testing) — preferred approach, order-independent
- **testSaga** (unit testing) — for when effect ordering matters
- **Providers** — static and dynamic mocking with partial matchers
- **Reducer integration** — test saga + reducer pipeline with `withReducer` + `hasFinalState`
- **Anti-patterns** — 12 common testing mistakes with BAD/GOOD examples
- **Jest and Vitest** setup and patterns

## Baseline

- redux-saga-test-plan ^5.x
- redux-saga ^1.4.2
- Jest or Vitest

## Structure

```
├── SKILL.md                      # Entry point for AI agents
└── references/
    ├── api-reference.md          # Complete expectSaga, testSaga, providers, matchers API
    └── anti-patterns.md          # Common testing mistakes to avoid
```

## Related

- [redux-saga-skill](https://github.com/anivar/redux-saga-skill) — Full redux-saga best practices skill

## License

MIT
