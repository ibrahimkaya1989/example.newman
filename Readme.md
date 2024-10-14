
## Requirments

Node version must be v16+.

```bash
node --version
```

## Dependencies

More information: https://github.com/postmanlabs/newman

```bash
npm install

npm install newman
npm install newman-reporter-json
npm install newman-reporter-html
npm install newman-reporter-htmlextra
```

## Running

```bash
newman run DemoPhotoGallery.postman_collection.json --reporters=cli,junit,json,junit,htmlextra
```

Example:
```bash
newman run my_collection.json -e my_environment.json --reporters=cli,htmlextra
```