# Maestro-Projects
## corrigir:
- Atualmente é necessário usar esse comando para abrir o emulador: .\emulator.exe android34 -accel off
- corrigir criarContatos.yaml e estudar como fazer algo dinâmico

## fazer:
- fazer o setup e o teardown em arquivos separados e estudar como chamar no fluxo em teste
- usar listas para validação de itens
- procurar o comando do botão “Aplicativos Recentes”
- criar uma env
- usar loops

## Comandos úteis:
- Gravar um vídeo: 
    - maestro record YourFlow.yaml 
    - maestro record --local YourFlow.yaml
- Instalar um .apk em um emulador ou dispositivo físico: adb install sample.apk
- Use o comando maestro test fileName.yaml para rodar o teste
- Abrir o seletor: maestro studio
- Verificar quais dispositivos estão conectados: adb devices
- Verificar todos os apps instalados: adb shell pm list packages
- Finalizar validarTelaContatos