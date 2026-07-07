# Loop-Harness

Loop-Harness is a desktop agent workspace for local automation, project workflows, artifacts, scheduled tasks, and tool integrations.

## Development

Requirements:

- Node.js `>=24.15.0 <25`
- npm

```bash
npm install
npm run electron:dev:openclaw
```

After the local runtime has been built once, daily development can usually use:

```bash
npm run electron:dev
```

## Project Notes

Loop-Harness keeps upstream tracking information locally. Do not publish local upstream snapshot branches or private sync branches to the public remote.

For local repository posture checks:

```bash
node scripts/loop-harness/upstream-status.cjs
```

