# react-course-project
Proyecto para el curso de React.js

## Cómo correrlo en desarrollo:
1. Instalar dependencias con `npm install`
2. Correr Webpack con `npm run watch`
3. Correr (en otra terminal) el servidor de render con `npm run bff`
4. Correr (en otra terminal) el servidor de estáticos con `npm run sfs`

## Hacer a produccíon
1. Instalar [now](https://now.sh)
2. Correr `npm run deploy:statics`
3. Cambiar en [`source/server.jsx#L15`](https://github.com/cgarcesgo/react-course-project/blob/master/source/server.jsx#L15) la URL por la obtenida al correr el comando anterior (o al definir un alias usando now)
4. Correr `npm run deploy`
