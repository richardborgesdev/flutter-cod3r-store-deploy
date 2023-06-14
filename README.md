# flutter-cod3r-store-deploy
Publicando a Aplicação nas Lojas de Aplicativos

## comandos
```bash
flutter pub add -d flutter_launcher_icons
flutter pub run flutter_launcher_icons:main
```

## Icones e cor no ios
1. foram utilizadas as ferramentas do xcode para adicionar os icones, splash e cores de fundo
    1. Acessar lauchImage, adicionar imagem, trocar cor de fundo

## Publicar app no android
1. gerar chave
    ```bash
    keytool -genkey -v -keystore ~/upload-keystore.jks -keyalg RSA \
              -keysize 2048 -validity 10000 -alias upload
    ```
2. seguir documentação https://docs.flutter.dev/deployment/android
