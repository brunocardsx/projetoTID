# projetoTID

# Requisitos

Certifique-se de ter as seguintes bibliotecas Node.js instaladas no seu ambiente:

    serialport: Para comunicação com a porta serial.
    socket.io: Para habilitar a comunicação WebSocket.
    express: Para configurar um servidor web.
    cors: Para habilitar o Cross-Origin Resource Sharing (CORS).
    @serialport/parser-readline: Um parser para dados em série no formato de linha.

Você pode instalá-las com o seguinte comando:

npm install serialport socket.io express cors @serialport/parser-readline

# Uso
Servidor WebSocket

O servidor WebSocket captura dados de sensores de uma porta serial e transmite esses dados para clientes WebSocket. Para configurar e executar o servidor, siga estas etapas:

    Conecte seus sensores à porta serial especificada no código (no exemplo, 'COM3').

    No arquivo script.js, defina os sensores que deseja monitorar. Por padrão, o código está configurado para monitorar cinco sensores: sensor1, sensor2, sensor3, sensor4, sensor5.

    Execute o servidor:
    executando o seguinte codigo no console: node server.js
