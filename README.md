# Maestro-Projects

## fix:
- Currently you need to use this command to open the emulator: .\emulator.exe android34 -accel off

## to do:
- 

## Useful commands:
- Record a video:
- maestro record YourFlow.yaml
- maestro record --local YourFlow.yaml
- Install an .apk on an emulator or physical device: adb install sample.apk
- Use the command maestro test fileName.yaml to run the test
- Open the selector: maestro studio
- Check which devices are connected: adb devices
- Check all installed apps: adb shell pm list packages
-


## corrigir:
- Atualmente é necessário usar esse comando para abrir o emulador: .\emulator.exe android34 -accel off

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
- 