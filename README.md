# lista_tarefa

Aplicação feita em flutter de uma lista de tarefas.

As tarefas são armazenadas no dispositivo, desta forma mantendo o status ao fechar.

Conceitos aprendidos:

* _initState (Sobrescrever método no carregamento do App para carregar os dados do App)
* Expanded (Container usado para preencher o espaço da tela/widget)
* RefreshIndicator (Arrastar para baixo para atualizar lista)
* ListView.builder (Lista de tarefas) - CheckboxListTile Lista com checkbox
* Dismissible (usado para arrastar para direita na ação de apagar item da lista)
* SnackBar (Usado para desfazer a ação, mas também para mensagens ao usuário)
* Manipulação de arquivo usando (File, path_provider)

## Sobre o App

Tela inicial do App
<img src="https://github.com/tiagomartinscc/flutter-lista-tarefa/raw/master/doc/Screenshot_1594341690.png" />

Digita uma tarefa e aperta em ADD
<img src="https://github.com/tiagomartinscc/flutter-lista-tarefa/raw/master/doc/Screenshot_1594341700.png" />

Adiciona na lista como não feito (checkbox desmarcado e com icone !)
<img src="https://github.com/tiagomartinscc/flutter-lista-tarefa/raw/master/doc/Screenshot_1594341702.png" />

Ao marcar ele muda o icone para checked.
<img src="https://github.com/tiagomartinscc/flutter-lista-tarefa/raw/master/doc/Screenshot_1594341706.png" />

Arrastando para direita ele apaga a tarefa
<img src="https://github.com/tiagomartinscc/flutter-lista-tarefa/raw/master/doc/Screenshot_1594341741.png" />

Lista de tarefas intercaladas entre realizadas e a fazer.
<img src="https://github.com/tiagomartinscc/flutter-lista-tarefa/raw/master/doc/Screenshot_1594341780.png" />

Arrastando para baixo ele ordena deixando primeiro as tarefas a fazer.
<img src="https://github.com/tiagomartinscc/flutter-lista-tarefa/raw/master/doc/Screenshot_1594341784.png" />

Arrastando para baixo ele ordena deixando primeiro as tarefas a fazer.
<img src="https://github.com/tiagomartinscc/flutter-lista-tarefa/raw/master/doc/Screenshot_1594341786.png" />

Ao excluir um item o nome dele é exibido no inferior da tela com a opção de desfazer.
<img src="https://github.com/tiagomartinscc/flutter-lista-tarefa/raw/master/doc/Screenshot_1594341792.png" />

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
