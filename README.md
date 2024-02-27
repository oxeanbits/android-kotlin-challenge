**Desafio para vaga Android - Kotlin**

**Objetivo do Desafio**

O objetivo deste desafio é avaliar suas habilidades no desenvolvimento com o framework nativo para desenvolvimento [Android](https://developer.android.com/), a sua familiaridade com o uso de tecnologias reativas como [REDUX](https://redux.js.org/) (versão [Android](https://github.com/oxeanbits/redukt)), a integração de uma API externa, a implementação de componentes baseados no [Material Design 3](https://m3.material.io/), a escrita de testes usando [JUnit](https://junit.org/junit5/), [Roboletric](https://robolectric.org/) e a criação de uma documentação clara.

**Tarefas:**

1. **Requisitos do projeto**
- Escolha 1 dentre os 3 exemplos de projeto no qual você deseje trabalhar:
  - [Crie uma aplicação de Trivia](https://github.com/oxeanbits/android-kotlin-challenge/blob/main/trivia.md)
  - [Crie uma aplicação que informe a previsão do tempo de determinada localização](https://github.com/oxeanbits/android-kotlin-challenge/blob/main/weather.md)
  - Proponha uma aplicação de sua preferência sem esquecer de definir seu escopo (use os 2 exemplos anteriores como exemplo de documentação de requisitos)
    
2.**Criação de um Projeto**
- Crie um novo projeto Android (utilize [Android Studio](https://developer.android.com/studio) e [Kotlin](https://developer.android.com/kotlin) no projeto)

3.**Estrutura da Aplicação**
- A aplicação deverá seguir a [Arquitetura REDUX](https://redux.js.org/), utilizando a versão [Android Kotlin](https://github.com/oxeanbits/redukt)
- A aplicação deverá conectar a uma API REST externa. Poderá ser utilizado um framework que auxilie nessa conexão, como por exemplo, [Retrofit](https://square.github.io/retrofit/).
- A UI da aplicação deverá utilizar um framework reativo como [Jetpack Compose](https://developer.android.com/jetpack/compose) ou [Anvil](https://zserge.com/posts/anvil-1/)

4.**Critérios técnicos a serem avaliados no código**
- O desenvolvedor deverá através do projeto demonstrar familiaridade com a [arquitetura](https://developer.android.com/topic/architecture/intro) de uma aplicação Android, por exemplo, sobre conceitos como *Activities*, *Services*, *Permissões*, *Lifecycle*, dentre outros.
- O desenvolvedor deverá orientar seu código sobre o Príncípio da Separação de Responsibilidades ([Separation of Concerns](https://developer.android.com/topic/architecture)), definindo a responsabilidade de cada camada da arquitetura da aplicação.
- Durante todo o desenvolvimento do código é interessante que a [unidirecionalidade](https://developer.android.com/topic/architecture/ui-layer) do fluxo de dados seja garantida e a imutabilidade dos mesmos também seja garantida.
- Todo o design da aplicação deverá seguir diretrizes do [Material Design 3](https://m3.material.io/)

3. **Documentação no README**
- No README.md descreva:
  - O projeto em detalhes (não exite em utilizar imagens da aplicação, vídeos, em dizer o que sua aplicação faz com riqueza de detalhes).
  - As instruções sobre como executar o projeto, configurar variáveis de ambiente (se existirem).
  - Como executar os testes (se existirem).
  - Qualquer outra informação que julgar pertinente.

**Observações:**
- Adote boas práticas de codificação, use comentários só quando extremamente necessário, prefira código mais limpo que dispense comentários para explicar.
- Ao finalizar, forneça um link para o repositório do GitHub contendo o código-fonte e a documentação, enviado para o email vagas{at}oxeanbits{dot}com

**Pontos Extras:**
- Implemente testes unitários usando [JUnit](https://junit.org/junit5/), [Roboletric](https://robolectric.org/) para pelo menos uma funcionalidade crítica da aplicação.
- Faça a aplicação ser responsiva/adaptável para a maioria dos dispositivos Android.
