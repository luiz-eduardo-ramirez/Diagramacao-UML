# 📱 Projeto: Modelagem UML do iPhone - Desafio

Este projeto é uma representação UML e implementação em Java das funcionalidades principais do iPhone apresentadas no vídeo de lançamento de 2007 por Steve Jobs.

## 🎯 Objetivo

Modelar o componente `iPhone` com base em três funcionalidades distintas:

- 🎵 **Reprodutor Musical**
- 📞 **Aparelho Telefônico**
- 🌐 **Navegador na Internet**

## 🧱 Estrutura UML

O projeto utiliza interfaces para representar funcionalidades específicas, e uma classe `Iphone` que implementa todas elas.

### Interfaces

- `ReprodutorMusical`

  - `tocar()`
  - `pausar()`
  - `selecionarMusica(String musica)`

- `AparelhoTelefonico`

  - `ligar(String numero)`
  - `atender()`
  - `iniciarCorreioVoz()`

- `NavegadorInternet`
  - `exibirPagina(String url)`
  - `adicionarNovaAba()`
  - `atualizarPagina()`

### Classe Principal

- `Iphone`
  - Implementa todas as interfaces acima e seus métodos.

## 💻 Estrutura de Arquivos

```
📁 src/
├── AparelhoTelefonico.java
├── NavegadorInternet.java
├── ReprodutorMusical.java
└── Iphone.java
```

## ✅ Como Executar

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/nome-do-repo.git
   cd nome-do-repo
   ```

2. Compile os arquivos:

   ```bash
   javac src/*.java
   ```

3. Crie uma classe de teste (opcional) e execute:

   ```java
   public class Main {
       public static void main(String[] args) {
           Iphone iphone = new Iphone();
           iphone.tocar();
           iphone.ligar("123456789");
           iphone.exibirPagina("https://apple.com");
       }
   }
   ```

4. Compile e execute:
   ```bash
   javac src/Main.java
   java -cp src Main
   ```

## 📸 Diagrama UML

O diagrama UML foi desenvolvido com base em três interfaces distintas. (Adicione a imagem aqui se desejar)

## 📽 Referência

- Vídeo de lançamento do iPhone 2007 (minuto 00:15 até 00:55)

## 📄 Licença

Este projeto é apenas educacional. Sinta-se livre para adaptar.

---

Desenvolvido com 💙 para fins de estudo.
