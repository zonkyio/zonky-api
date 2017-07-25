# Zonky REST API

This is repository for Zonky REST API documentation. The latest version of the documentation is also publicly available on Apiary (http://docs.zonky.apiary.io).

## Local development
You can build and export the documentation locally outside Apiary with a few simple steps. All you need is working Node.js environment on your machine.

1. Clone this repository
```bash
git clone git@github.com:zonkyio/zonky-api.git
cd zonky-api
```

2. Install project dependencies
```bash
npm install
```

3. Run development server
```bash
npm run dev
```
Server will start on `http://localhost:3000` and will listen for changes in `apiary.apib` file.

4. Export documentation
```bash
npm run build
```
The documentation will be exported to a single `output.html` file
