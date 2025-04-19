#

- para gerenciar o estado: pacote [Provider](https://pub.dev/packages/provider)
- para teste de integração: biblioteca `integration_test` 


--

## 2. Configuração do ambiente de desenvolvimento do Flutter
- SDK do Flutter
- IDE

## 3. Para começar
### 3.1 Criação de novo app do Flutter e atualizar as dependências
- Criar um novo app do Flutter
```bash
flutter create testing_app
```

- Adicionar dependências de pub na linha de comando
```bash
cd testing_app

flutter pub add provider
```

- para testes de direção autônoma do código do Flutter em dispositivos e emuladores
```bash
flutter pub add --dev --sdk=flutter integration_test
```

-
```bash
flutter pub add --dev --sdk=flutter flutter_driver
```

- para ferramentas gerais de teste
```bash
flutter pub add --dev test
```

- para processar a navegação no app: `go_router`
```bash
flutter pub add go_router
```

---

## 4. Criar o app
