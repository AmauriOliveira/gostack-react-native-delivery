### React Native

>Instalando as dependências

  ```bash
  yarn
  ```

>Atualizando os pacotes

  ```bash
  yarn upgrade
  ```

>Em uma console execute primeiro

  ```bash
  yarn start
  ```

> Depois execute

  ```bash
  yarn android
  ```

>Mostra o status de cada dispositivo Android, seja ele físico ou virtual

  ```bash
  adb devices
  ```

>Lista os dispositivos Android virtual, somente os criados via Android Studio

  ```bash
  emulator -list-avds
  ```

>Liga o Android virtual, no exemplo ele chama Pie01, só vale para os criados via Android Studio.

```bash
emulator -avd Pie01
```

> Fake API

```bash
 yarn json-server server.json -p 3333
```
