# fresh project

The basic Deno Fresh template, with working Tailwind V3+, through the Twind V1+. Uses the official Deno Fresh Twind v1 plugin. 

The main change is to rename `$fresh/plugins/twind.ts` to `twindv1.ts` in the `main.ts`. And use the `@twind/core`'s `defineConfig` in the twind.config.ts

The other change is that the import map is inside the `deno.json` file.

### Usage

Start the project:

```
deno task start
```

This will watch the project directory and restart as necessary.
