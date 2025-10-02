# Conversor de Moedas Flutter

App simples de conversão de moedas (Real, Dólar, Euro) usando API de câmbio da HG Brasil.  
O app possui **tema escuro**, campos de texto estilizados, teclado numérico e **ícone personalizado**.

---

## Funcionalidades

- Conversão instantânea entre Real, Dólar e Euro
- Busca de cotações em tempo real via API
- Interface intuitiva com cores personalizadas
- Tema escuro consistente (`ThemeData`)
- Ícone do app atualizado para identidade visual
- Rolagem para dispositivos menores (SingleChildScrollView)
- Entrada numérica com teclado especializado (`TextInputType.numberWithOptions(decimal: true)`)

---

## Técnicas Utilizadas

- Consumo de **API REST** com `http` e `Future<Map>` para requisições assíncronas
- Widgets do **Flutter**:
  - `StatefulWidget` para atualização dinâmica dos campos
  - `FutureBuilder` para tratamento assíncrono
  - `TextField` com `TextEditingController` para capturar entradas
  - `SingleChildScrollView` para rolagem
  - `Icon` para representatividade visual
- Aplicação de **tema global** com `ThemeData` e `InputDecorationTheme`:
  - Define cores de label, hint, borda ativa e inativa
- Conversão numérica e formatação com `toStringAsFixed(2)`
- Estrutura modular (função helper `buildTextField`) para manutenção e reutilização
- Boa prática de UX: limpeza de campos (`_clearAll`) quando input vazio

---

## Estrutura do Projeto

lib/
├── main.dart

> O projeto é simples e direto, mantendo a arquitetura limpa e fácil de entender.

---

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/conversor-flutter.git

   ---

   
## Como Executar

1. Clone o repositório
```bash
   git clone https://github.com/seu-usuario/conversor-flutter.git
```
2. Entre na pasta do projeto
```bash
cd conversor-flutter
```
3. Instale as dependências:
```bash
flutter pub get
```
4. Rode o app em um emulador ou dispositivo real:
```bash
flutter run
```
---

## Observações Importantes

- É necessário conexão com a internet para buscar os valores de câmbio.
- O app foi testado em Android, mas é compatível com iOS.
- O ícone do app foi personalizado, reforçando a identidade visual e profissionalizando o projeto.
- Todos os campos possuem teclado numérico com suporte a casas decimais.
- Tema escuro consistente, aplicando cores nos TextFields, bordas e labels globalmente.

---

## Demonstração Visual

Ícone atualizado do app:

<img width="1024" height="1024" alt="icon" src="https://github.com/user-attachments/assets/d0658413-b2eb-4a68-8131-75a373a9ccb5" />

Tela principal:
<img width="720" height="1280" alt="Screenshot_20251002_171747" src="https://github.com/user-attachments/assets/80f6b328-0997-43a0-b33e-a03744861f1a" />

<img width="720" height="1280" alt="Screenshot_20251002_171823" src="https://github.com/user-attachments/assets/1f0f9c55-e0ef-4883-901a-582abce7e448" />

<img width="720" height="1280" alt="Screenshot_20251002_171900" src="https://github.com/user-attachments/assets/b87f55aa-5ef8-4110-8213-96d700ee30d8" />

---


[GitHub](https://github.com/marcos-devmob) | [LinkedIn](https://www.linkedin.com/in/marcosaurelioalves/)    

