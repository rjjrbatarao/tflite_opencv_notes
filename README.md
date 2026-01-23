# tflite_opencv_notes
gotchas

## Tutorials
```
https://mrousavy.com/blog/Reinventing-Camera-Processing
```

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
npm install @u4/opencv4nodejs
npm rebuild @tensorflow/tfjs-node --build-addon-from-source
npm rebuild tfjs-tflite-node --build-addon-from-source

choco list --lo -e OpenCV
set OPENCV_INCLUDE_DIR=C:\tools\opencv\build\include
set OPENCV_LIB_DIR="C:\\tools\\opencv\\build\\x64\\vc16\\lib"
set OPENCV_BIN_DIR=C:\tools\opencv\build\x64\vc16\bin
set PATH=%PATH%;%OPENCV_BIN_DIR%;
set OPENCV4NODEJS_AUTOBUILD_OPENCV_VERSION=4.13.0

npm i -g --save opencv4nodejs
```

https://github.com/justadudewhohacks/opencv4nodejs/issues/733<br>
https://github.com/UrielCh/opencv4nodejs/issues/174

