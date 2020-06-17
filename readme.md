# yarn audit dev dep repro

1. Install: `yarn install`
2. Run audit `yarn audit --summary --json | jq .data`
3. Output should list 16 devDependencies



