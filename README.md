# jossehallen

Modern full-stack setup using:

- [ElysiaJS](https://elysiajs.com/) – backend (Bun)
- [Vite](https://vite.dev/) – frontend
- [shadcn/ui](https://ui.shadcn.com/) – design system
- [TanStack Query](https://tanstack.com/query/latest) – server state
- [TanStack Table](https://tanstack.com/table/latest) – table logic
- TypeScript, Prettier, Railway, relational database
- React Hook Form for forms

Everything is typesafe and predictable.  
Backend prepares data. Frontend presents it.

---

## Branches

```
feat/descriptive-branch-name   → new features
fix/descriptive-branch-name    → bug fixes
```

Examples:

```
feat/add-auth
fix/null-response
```

---

## Commits

Keep git history clean and easy to read.

- Use `git commit -p` to review what you commit  
- Use `--amend` to adjust the last commit  
- Push with `--force-with-lease` when amending  
- Split commits for backend and frontend if needed  
- One commit for smaller changes  
- Never push half-done work

---

## Pull Requests

- Always create a branch from `main`  
- Open a PR when the work is ready  
- Let someone else review the code  
- Always **rebase**, never merge

```
git fetch origin
git rebase origin/main
```

---

## Code style

- Strict TypeScript  
- Prettier and ESLint handle formatting  
- Use shadcn/ui components for layout and inputs  
- Use React Hook Form for form handling  
- Use TanStack Query for API calls and caching  
- Use TanStack Table for table logic  
- Backend returns structured, validated data  
- Frontend just renders it

---

## Principle

Backend prepares.  
Frontend presents.
