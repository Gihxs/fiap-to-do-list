# Evidências — Fluxo de confirmação de exclusão

Este arquivo documenta o comportamento do novo fluxo de exclusão
com diálogo de confirmação (Jetpack Compose Material 3).

## 1. Lista antes da exclusão

Mostra a lista de tarefas com a tarefa que será excluída ainda presente.

<table>
  <tr>
    <td><img src="docs/images/exclusao/lista-antes.png" width="300"></td>
    <td><img src="docs/images/exclusao/dialogo-aberto.png" width="300"></td>
  </tr>
</table>

## 2. Resultado ao cancelar e nova abertura

Ao tocar em "Cancelar", o diálogo é fechado e a lista permanece inalterada.
O diálogo é aberto novamente para confirmar que o fluxo pode ser repetido.

<table>
  <tr>
    <td><img src="docs/images/exclusao/apos-cancelar.png" width="300"></td>
    <td><img src="docs/images/exclusao/dialogo-reaberto.png" width="300"></td>
  </tr>
</table>

## 3. Resultado após confirmar a exclusão

Ao tocar em "Excluir", somente a tarefa selecionada é removida da lista.

<img src="docs/images/exclusao/apos-confirmar.png" width="300">
