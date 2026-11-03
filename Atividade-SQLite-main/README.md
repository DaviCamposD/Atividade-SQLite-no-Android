# Agenda de Contatos - SQLiteOpenHelper

Projeto Android em Kotlin + Jetpack Compose para a missão de CRUD local.

## Tema
Agenda de Contatos.

## Funcionalidades
- Cadastrar contato
- Listar contatos
- Editar contato
- Excluir contato
- Persistência local com SQLite
- Dados permanecem após fechar e abrir o aplicativo

## Arquitetura
- model: modelo `Contato`
- database: `BancoHelper`, usando `SQLiteOpenHelper`
- repository: operações SQLite, `ContentValues` e `Cursor`
- viewmodel: estado da tela e coroutines
- ui: interface Jetpack Compose

## Requisitos da atividade
Não utiliza Room, SQLDelight ou outra biblioteca de persistência.

As operações de banco são executadas com `Dispatchers.IO`.

## Como executar
Abra a pasta no Android Studio, aguarde a sincronização do Gradle e execute o aplicativo em um emulador ou dispositivo Android.
