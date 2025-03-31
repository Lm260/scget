## Simple Curl Get

**Requisição simples com curl usando nodeJS**

```Example
const scget = require('scget');

async function main() {
    const body = await scget('https://example.com');
    
    if (!body.success) {
        console.log('Falha!');
        process.exit();
    }
    
    console.log(body.data);
}

main();
```

## Aviso
 
 - Módulo não recomendado para projetos que requerem mais informações. ( statuscode, headers e etc... )


### LICENSE

Projeto criado por Lm Only, todos os direitos reservados.