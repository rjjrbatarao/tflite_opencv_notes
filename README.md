# tflite_opencv_notes
gotchas

## Package.js
```json
{
  "name": "tract",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "dependencies": {
    "@tensorflow/tfjs": "^4.22.0",
    "@tensorflow/tfjs-core": "^4.22.0",
    "@tensorflow/tfjs-node": "^4.22.0",
    "@u4/opencv4nodejs": "^7.1.2",
    "jimp": "^1.6.0",
    "tfjs-tflite-node": "^0.0.2"
  }
}
```
```
Run console in Admin mode, remove any spaces on the directories
choco install OpenCV -y
SET OPENCV4NODEJS_DISABLE_AUTOBUILD = 1
pnpm install @u4/opencv4nodejs
npm rebuild @tensorflow/tfjs-node --build-addon-from-source
npm rebuild tfjs-tflite-node --build-addon-from-source
```
