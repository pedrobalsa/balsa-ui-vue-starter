# Balsa UI Vue starter

A forkable Vue 3, strict TypeScript, Vite, Tailwind CSS 4, and Balsa UI starting point for users and coding agents.

[Create a repository from this template](https://github.com/new?template_name=balsa-ui-vue-starter&template_owner=pedrobalsa), then:

```sh
npm install
npm run dev
npm run check
```

The starter includes Balsa's adaptive foundation, palette, themes, representative editable components, validation, and local agent context. Agents search by intent first, then read only the selected component specification and install the matching editable source before implementation.

Add more editable components with:

```sh
npx balsa-ui@latest search "settings form"
npx balsa-ui@latest info input --markdown
npx balsa-ui@latest add input
```

Installed Balsa files are application source. Preserve local changes when adding or updating components.

## License

MIT
