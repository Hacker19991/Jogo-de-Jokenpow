# **AppJokenpo (Jogo de Jokenpow)**

> Um aplicativo Android desenvolvido para os usuários poderem se distrair jogando contra a IA desenvolvida do código.

## Descrição
O **AppJokenpo** permite ao usuário ter uma partida de Jokenpow com uma IA simples a base de codigo que consiste em o usuário poder escolher entre, pedra, papel, ou tesoura, com uma pontução e possiblidade de empate, e se quiser pode apertar o de reiniciar para zerar a tabela de pontos e começar uma nova partida.

## Funcionalidades
- [x] Entrada de dados de consumo
- [x] Cálculo e exibição de estatísticas de consumo
- [x] Gráficos interativos para visualização dos dados
- [x] Interface intuitiva e amigável
- [ ] Suporte para diferentes tipos de recursos (planejado para futuras versões)

## Tecnologias Utilizadas
- [x] **Android Studio** (versão recomendada: Bumblebee | 2021.1.1)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [x] **TextView**, **EditText** para entrada e exibição de dados

## Como Rodar o Projeto
Siga os passos abaixo para rodar o projeto localmente:

1. Clone este repositório:
   ```bash
   https://github.com/Hacker19991/Jogo-de-Jokenpow
   
2. Abra o projeto no Android Studio.
   
3. Compile e execute o projeto em um emulador ou dispositivo físico.

## Estrutura do Projeto

```
── app
   ├── src
   │   ├── main
   │   │   ├── java/com/example/appconsumo
   │   │   │   ├── MainActivity.java # Atividade principal para monitoramento de consumo
   │   │   ├── res
   │   │   │   ├── drawable
   │   │   │   │   ├── padrao # Imagem quando você começa uma nova partida
   │   │   │   │   ├── papel # Imagem de papel quando selecionado
   │   │   │   │   ├── pedra # Imagem de pedra quando selecionado
   │   │   │   │   ├── tesoura # Imagem de tesoura quando selecionado
   │   │   │   ├── layout
   │   │   │   │   ├── activity_main.xml # Layout da tela principal
   │   │   │   └── values
   │   │   │       ├── strings.xml # Strings usadas no app
   │   │   │       ├── colors.xml # Cores definidas no projeto
   └── build.gradle # Configuração do Gradle
```

## Design e Prototipage
A interface do app foi criada usando ConstraintLayout no modelo Design para ser mais simples e facil de se usar e para ser mais compacto ao android e mais simples e pratico assim podendo se acostumar com o tempo.

## Telas do Aplicativo 

> Tela Principal

![image](https://github.com/user-attachments/assets/2c88a156-faaf-4379-af97-a5fd748096d9)

Uma tela simples, a imagem que será usada para representar os gestos selecionados pelo botão (Sugiro que coloque a imagem "padrao" para ser colocada), 4 botões para cada gesto ser ocorrido e para poder reiciciar o jogo e no final dois TextView para mostrar a pontuação do usuário e dai IA e o outro para dar mais detalhe ao jogo e dizer quando deu empate em cada turno diferente.

## Desenvolvedores
**Gabriel Henrique** - Desenvolvedor - [GitHub](https://github.com/Hacker19991).

## Licença
Este projeto está licenciado sob os termos da licença MIT. Para mais detalhes, veja o arquivo
[LICENSE](LICENSE).
