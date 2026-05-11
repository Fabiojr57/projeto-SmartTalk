README - SmartTask
Descrição
O SmartTask é um aplicativo Android desenvolvido em Kotlin para gerenciamento de tarefas. O usuário pode adicionar, concluir e excluir tarefas de forma simples e intuitiva.
Funcionalidades
- Adicionar tarefas
- Marcar tarefas como concluídas
- Excluir tarefas
- Persistência de dados utilizando SharedPreferences
- Interface moderna utilizando RecyclerView
Tecnologias Utilizadas
- Kotlin
- Android Studio
- RecyclerView
- Gson
- SharedPreferences
Estrutura do Projeto
Model: Tarefa.kt
Adapter: TarefaAdapter.kt
Utils: Prefs.kt
Activity: MainActivity.kt
Dependências
implementation("androidx.recyclerview:recyclerview:1.3.2")
implementation("com.google.code.gson:gson:2.10.1")
Layouts
activity_main.xml: Tela principal do aplicativo.
item_tarefa.xml: Item de cada tarefa exibida no RecyclerView.
Como Executar
1. Abra o projeto no Android Studio.
2. Aguarde o Gradle sincronizar.
3. Execute em um emulador ou dispositivo físico.
Funcionamento
Ao adicionar uma tarefa, ela é salva automaticamente utilizando SharedPreferences. O usuário pode concluir ou excluir tarefas.
Autor
Fabio  junior  Felix  Dias 
