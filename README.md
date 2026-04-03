# SolNow Workspace

Monorepo padre con submodules para desarrollo full-stack.

## Setup

```bash
git clone --recurse-submodules git@github.com:lucastomic/solnow.git
```

## Estructura

```
solnow/
├── back/    → solnow-back (API / backend)
└── front/   → solnow-front (Next.js / frontend)
```

## Actualizar submodules

```bash
git submodule update --remote --merge
```

