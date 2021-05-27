Almost minimal EEZ-Flow typescript extension

EEZ-Flow javascript extension sample

https://github.com/eez-open/eez-flow-ext-sample-js

EEZ-Flow PostgresSQL extension

https://github.com/eez-open/eez-flow-ext-postgres

To create your own

clone repo 

```
git clone https://github.com/goran-mahovlic/eez-flow-ext-typescript-template.git
cd eez-flow-ext-typescript-template
```

Replaced all typescript-template with custom-template

```
find . -type f -exec sed -i 's/typescript-template/custom-template/g' {} +
```

```
npm install
npm install typescript
npm run build
cd ~/.config/eezstudio/extensions
npm install "path to custom-template folder"
```

start studio

