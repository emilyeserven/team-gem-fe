[Wireframes](https://www.figma.com/design/I8AVWSq3rc1TKa9fFQnECT/Team-GEM-Flow?node-id=8-203&t=C279yDuX6b73eGlF-1)

## External Doc Quick Links
- [Tailwind](https://tailwindcss.com/docs/installation/using-vite)
- [Storybook](https://storybook.js.org/docs)
- [ShadCN](https://ui.shadcn.com/docs/components)
- [Lucide Icons](https://lucide.dev/icons/)

## Important Scripts
- `pnpm run dev` - Run locally
- `pnpm run storybook` - Run [Storybook](https://storybook.js.org/)

## Repo Setup
1. [Install PNPM](https://pnpm.io/installation#using-corepack)
2. Clone the repo
3. Generate a token to use the linter
    1. Copy the `.npmrc.example` file and rename it to `.npmrc`
    2. Go to [Token Page](https://github.com/settings/tokens)
    3. Make a "New personal access token (classic)" token and give it `read:packages` scope, copy it
    4. Paste the token in `.npmrc`,  (line 2, where it says `TOKEN`)
4. At the project root, run `pnpm i`