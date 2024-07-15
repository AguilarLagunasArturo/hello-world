# Setup

## Dependencies
```bash
sudo apt install nodejs npm
sudo npm install -g @angular/cli
```
## Init
```bash
ng new
ng serve
```

## Run
```bash
npm install
ng build
ng serve
```
## Build image
```
docker build -t angular-docker .
docker images
docker run -p 4200:4200 angular-docker
```
