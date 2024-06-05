# Gerenciador de Downloads Automático

Desenvolvi essa ferramenta para ajudar meus colegas, que estavam perdendo muito tempo fazendo downloads repetidos de várias planilhas ao longo do dia. Pensei: "Por que não criar um gerenciador de downloads automático?"

Então, criei em Python um gerenciador onde o usuário pode inserir o nome da planilha, o link de download e a pasta de destino desejada. Com isso, é possível fazer o download imediato ou deixar programado para baixar automaticamente a cada 15, 30 ou 60 minutos.

## Bibliotecas Utilizadas
- **PyQt5**: Para a criação da interface gráfica.
- **requests**: Para realizar os downloads das planilhas.
- **logging**: Para registrar as atividades do aplicativo.
- **os**: Para manipulação de caminhos e diretórios.
- **sys**: Para a integração com o sistema operacional.

