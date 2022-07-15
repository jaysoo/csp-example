# CSP example

This demo shows using `<meta http-equiv="Content-Security-Policy" content="default-src: 'self'" />` to disallow inline styles/scripts from executing.

```bash
nx build demo
npx http-server dist/apps/demo
```

Open up the server and see that the app renders correctly.
