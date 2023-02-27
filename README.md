## Install steps
Put the `index.html` in the `docs` folder
- `npm install openapi-generator-cli`
- `openapi-generator-cli version-manager set 5.4.0`
- `openapi-generator-cli generate -i ./docs/api.yaml -g html2 -o ./docs -t ./htmlDocs2 `
