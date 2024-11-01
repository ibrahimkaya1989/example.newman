
## Requirments

Node version must be v16+.

```bash
node --version
```

## Dependencies

More information: https://github.com/postmanlabs/newman

```bash
npm install

npm install --save-dev newman
npm install --save-dev newman-reporter-json
npm install --save-dev newman-reporter-html
npm install --save-dev newman-reporter-htmlextra
npm install --save-dev newman-reporter-allure
```

## Running

```bash
newman run DemoPhotoGallery.postman_collection.json --reporters="cli,junit,json,junit,htmlextra"
```

Example:
```bash
newman run my_collection.json -e my_environment.json --reporters="cli,htmlextra"
```