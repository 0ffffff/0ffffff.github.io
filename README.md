## wi

my website
built in astro

### Setup

- Run `corepack enable` if pnpm is not already available on your machine
- Run `pnpm install` to install dependencies

### Scripts

- `pnpm dev` starts the local dev server
- `pnpm build` creates the production build
- `pnpm preview` previews the built site

### Structure

- `src/pages/` contains the main routes
- `src/content/blog/` contains blog posts in Markdown
- `src/layouts/BaseLayout.astro` provides the shared page frame
- `src/styles/global.css` contains the only global styling

### Editing

- Update the text content in the route files under `src/pages/`
- Add new blog posts as Markdown files in `src/content/blog/`
- Keep styling minimal and centered around the single-column layout
