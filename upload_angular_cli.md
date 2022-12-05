# Actualizar ANGULAR CLI
## 1. Desinstalar e instalar NODE.JS
## 2. Actualizar NPM
```
npm install -g npm@1.0.0
```
## 3. Borrar la cache de NPM
```
npm cache clean --force
```
## 4. Desinstalar los paquetes anteriores de Angular CLI
```
npm uninstall -g angular-cli
npm uninstall -g @angular/cli
```
## 5. Borrar la cache de NPM de nuevo:
```
npm cache clean --force
```
## 6. Instalar la última versión de Angular CLI
```
npm install -g @angular/cli@latest
```
## 7. Comprobar instalación
```
ng v
```
