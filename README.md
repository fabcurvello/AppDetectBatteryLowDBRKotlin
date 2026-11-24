# App Detectar Bateria Baixa (DBR, Kotlin)

> Repositório didático: exercício prático de Android nativo com **Kotlin**, desenvolvido e aplicado em sala de aula pelo Prof. Fabricio Curvello.

## Sobre o projeto

Aplicativo que avisa o usuário quando a **bateria está baixa**, usando um Broadcast Receiver registrado dinamicamente (DBR).

## Contexto acadêmico

Exercício aplicado em sala de aula, usado como prática guiada com os alunos.

## Versão em Java

Esta mesma aplicação também foi desenvolvida em **Java**: [AppDetectBatteryLowDBRJava](https://github.com/fabcurvello/AppDetectBatteryLowDBRJava). Comparar as duas versões lado a lado ajuda a entender as diferenças de sintaxe entre Java e Kotlin no Android.

## O que o app faz

- Registra um `BroadcastReceiver` para os eventos `ACTION_BATTERY_LOW` e `ACTION_BATTERY_OKAY`.
- Mostra um `Toast` avisando quando a bateria fica baixa e quando volta a um nível aceitável.
- Cancela o registro do receiver em `onDestroy()`.

## Conceitos trabalhados em aula

- `BroadcastReceiver` registrado dinamicamente (DBR)
- Eventos de sistema relacionados à bateria
- `IntentFilter` com mais de uma ação
- Objetos anônimos (`object :`) em Kotlin

## Tecnologias

- **Kotlin**
- **Android SDK** (Android Studio)
- **Gradle**
- `minSdk 28` / `compileSdk 34`

## Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/fabcurvello/AppDetectBatteryLowDBRKotlin.git
   ```
2. Abra a pasta no **Android Studio** e aguarde a sincronização do Gradle.
3. Execute em um emulador ou dispositivo físico com Android compatível com a API 28 ou superior.

## Veja também

Outros repositórios de aula com o mesmo tema:

- [AppBroadcastReceiversJava](https://github.com/fabcurvello/AppBroadcastReceiversJava)
- [AppDetectBatteryLowDBRJava](https://github.com/fabcurvello/AppDetectBatteryLowDBRJava)
- [AppDetectChargeDBRJava](https://github.com/fabcurvello/AppDetectChargeDBRJava)
- [AppDetectChargeDBRKotlin](https://github.com/fabcurvello/AppDetectChargeDBRKotlin)
- [AppNotifBateryLevelBRDJava](https://github.com/fabcurvello/AppNotifBateryLevelBRDJava)
- [AppNotifBateryLevelBRDKotlin](https://github.com/fabcurvello/AppNotifBateryLevelBRDKotlin)
- [AppNotifBootCompletedBREJAVA](https://github.com/fabcurvello/AppNotifBootCompletedBREJAVA)
- [AppNotifBootCompletedBREKotlin](https://github.com/fabcurvello/AppNotifBootCompletedBREKotlin)

## Autor

**Fabricio Curvello**: professor de desenvolvimento de software no SENAI-RJ (desde 1997) e em faculdades do grupo Ânima Educação (IBMR e UNA).

- GitHub: [github.com/fabcurvello](https://github.com/fabcurvello)
- LinkedIn: [linkedin.com/in/fabriciocurvello](https://www.linkedin.com/in/fabriciocurvello)
- YouTube: [@fabriciocurvello](https://www.youtube.com/@fabriciocurvello)
