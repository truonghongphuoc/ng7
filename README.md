# NG Book Tutorial

## Requirement
Node JS version >= v8 `(recommend use version v10.13)`

## Installation
1. Clone source code: `https://github.com/truonghongphuoc/ng7.git`
2. Go to project root and run command `npm install` for install node modules
3. Config `apiRoot` in /path-to-project/src/environment/environment.prod.ts
4. Build app: `npm run build`
5. Build docker image with image name is 'ngbook': `docker build -t ngbook .`
6. Run docker container from image 'ngbook': `docker run -d -p 4444:80 ngbook`
