# Compile javascript
Usar o webpack para minificar o arquivo javascript para web e tornar ele legível para a maioria dos navegadores. Além disso, ele constrói um mapa de dependências do projeto, e gera um ou mais bundles.

## Configuração básica

    const path = require('path')
    module.exports = {
        entry: './src/index.js'
        output:{
            filename:'bundler.js',
            path:path.resolve(__dirname,'dist'),
        }
    }