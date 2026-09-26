# Horas Daniel — APK de teste

## GitHub
Coloque **todo o conteúdo desta pasta** na raiz do repositório GitHub.
Não coloque esta pasta dentro de outra pasta e não use `project.zip`.

A raiz deve mostrar:
- `settings.gradle`
- `build.gradle`
- `gradle.properties`
- `codemagic.yaml`
- `app/`

## Codemagic
Selecione o repositório e o workflow **Horas Daniel - APK de Teste**.
O build gera `app/build/outputs/apk/debug/app-debug.apk`.

Esta versão remove a dependência AndroidX/AppCompat do projeto de teste para evitar o erro de classes Kotlin duplicadas observado no Codemagic.
