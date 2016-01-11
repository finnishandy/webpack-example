https://webpack.github.io/docs/tutorials/getting-started/

npm install webpack -g
npm install css-loader style-loader
npm install webpack-dev-server -g

webpack ./entry.js bundle.js --module-bind "css=style!css"