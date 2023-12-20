# script-envio-mensagens-chat

Este repositório contém um script JavaScript que automatiza o processo de envio de mensagens em uma interface de chat. A função `enviarScript` aceita um texto de script como entrada e simula a digitação e envio de mensagens por meio de elementos HTML na página.

## Como Usar

1. **Copie o Código:** Copie o conteúdo da função `enviarScript` presente no arquivo JavaScript.

2. **Cole no Console do Navegador:** Abra o console do desenvolvedor no navegador da web enquanto estiver na página do chat e cole o código.

3. **Execute o Script:** Execute o script para automatizar o envio de mensagens. Certifique-se de ter uma conversa aberta na página.

## Exemplo de Uso

```javascript
// Chama a função 'enviarScript' com um script de exemplo.
enviarScript(`SUA MENSAGEM`)
    .then(e => console.log(`Código finalizado, ${e} mensagens enviadas`))
    .catch(console.error);
