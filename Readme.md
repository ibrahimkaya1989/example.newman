
## Requirments

Node version must be v16+.

```bash
node --version
```

## Dependencies

```bash
npm install -g newman
npm install -g newman-reporter-html
npm install -g newman-reporter-htmlextra
```

## Running

```bash
newman run DemoPhotoGallery.postman_collection.json --reporters=cli,htmlextra
```

Example:
```bash
newman run my_collection.json -e my_environment.json --reporters=cli,htmlextra
```