# Projeto-da-disciplina-de-LFAC---Simulador-de-Automatos

<p align="center">
  <img src="https://user-images.githubusercontent.com/91018438/204195385-acc6fcd4-05a7-4f25-87d1-cb7d5cc5c852.png" alt="animated" />
</p>

<center>
Equipe:

    Leonardo Lucca | Victoria Jullya | Robson de Paula

</center>

## O que é o Simulador de Automatos?

O Simulador de Autômatos é uma aplicação interativa desenvolvida para criar, visualizar e testar o funcionamento de autômatos finitos. Este projeto tem como objetivo facilitar o aprendizado e a análise de conceitos fundamentais de Teoria da Computação.

---

## Instalação do programa

<p>

> Clone esse projeto em seu computador com o comando:
>
>     git clone https://github.com/LeoLucc/Projeto-da-disciplina-de-LFAC---Simulador-de-Aut-matos.git
>
> Acesse o VSCODE e navegue até o diretório do projeto:
>
> Ao abrir o código do projeto, inicialize selecionando o botão **RUN**:

</p>

---

## Instruções sobre a interface:

A interface utiliza a biblioteca **pygame**, portanto é necessário instalá-la (caso ainda não tenha) através do comando:

```bash
pip install pygame

Funcionalidades principais:
Definição de Transições

Para definir uma transição:
Digite o símbolo de transição.
Clique no estado de origem.
Clique no estado de destino.
(Para loops, basta clicar no mesmo estado duas vezes).
Marcação de Estados

As marcações de estado inicial e estado final devem ser feitas após definir as transições.
Uma vez marcado o estado inicial, não é possível desmarcá-lo para escolher outro estado, a menos que o exclua.
Botões de Testes

Os botões de testes ("Teste" e "Step Test") não funcionam enquanto um botão de construção do autômato estiver ativado.
É necessário desativar os botões de construção antes de iniciar os testes.
Tipos de Testes:
Teste Rápido:
Clique no botão Teste.
Digite a entrada desejada.
Pressione a tecla Enter para realizar o teste.
O resultado será exibido na borda inferior da tela:
Aceita (verde) ou Rejeitada (vermelho).
Teste Passo a Passo:
Clique no botão Step Test.
Digite a entrada desejada.
Clique novamente no botão Step Test para iniciar a simulação.
Os estados serão destacados durante a execução:
Verde: Entrada aceita.
Vermelho: Entrada rejeitada.
Obrigado!
```
