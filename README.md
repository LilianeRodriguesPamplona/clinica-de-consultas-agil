🔗 Clínica de Consultas Ágil
Desenvolvi a Clínica de Consultas Ágil através do desafio que recebi ao participar do processo seletivo do Programa Aceleradora Ágil .

📝 Sobre o Desafio - Descrição
Você foi contratado para desenvolver um sistema de consulta clínica no seu bairro.

Seus vizinhos não estão se sentindo muito bem e gostariam de agendar consultas. Para isso, você deve desenvolver as seguintes funcionalidades, que devem ser apresentadas para o usuário através de um menu via terminal:

Cadastrar Paciente
O programa solicita o nome e o telefone do usuário. Após o cadastro, exibe a mensagem "Paciente cadastrado com sucesso" e adicione o paciente à lista de Pacientes Cadastrados. Em seguida, retorna ao menu principal.

Marcações de Consulta
Ao selecionar essa opção, o programa exibe uma lista numerada dos pacientes cadastrados. Ao escolher o número correspondente a um paciente, solicite o dia, a hora e a especialidade desejada para uma consulta. Após o envio desses dados, o agendamento é adicionado à lista de agendamentos e o programa retorna ao menu principal.

Cancelamento de Consultas
Ao selecionar essa opção, o programa exibe uma lista numerada dos agendamentos existentes. Ao escolher o número correspondente ao agendamento que deseja marcar, é exibida uma mensagem informando os dados, a hora e a especialidade da consulta agendada. Nesse momento, o usuário pode optar por cancelar a consulta. Ao confirmar o cancelamento, o agendamento é removido da lista e o programa retorna ao menu principal.

Sair
O programa encerra a execução.

Tratamento de Erros
✔️ O paciente não pode ser cadastrado mais de uma vez. Para evitar duplicidade, garanta que o número de telefone seja diferente para cada cadastro. Caso ocorra uma tentativa de cadastro duplicado, será exibida a mensagem "Paciente já cadastrado!" e retorne ao menu principal.

✔️ Pacientes não podem marcar consultas em dias e horários já agendados. Verifique se os dados e a hora selecionada estão disponíveis antes de realizar o agendamento.

✔️ Consultas não podem ser marcadas antes da data atual. -se de que o usuário certifique-se de não poder agendar consultas retroativas.

Extra
Seria muito legal se você conseguisse implementar uma maneira de armazenar as informações dos pacientes de forma que eles continuassem existindo mesmo após o usuário sair do sistema. Que funciona como uma espécie de “banco de dados”.

Funcionalidades do Projeto
Funcionalidade 1: cadastrar pacientes.
Funcionalidade 2: marcações de consultas.
Funcionalidade 3: cancelamento de consultas.
Funcionalidade 4: sair/finalizar o programa.
Funcionalidade 5: armazenamento de dados.
🚀 Começando
Essas instruções permitirão que você tenha uma cópia do projeto em execução em sua máquina local para desenvolvimento e testes.

📋 Pré-requisitos
Antes de começar, comprove-se que você está instalado em seu sistema operacional:

Navegador Web para visualizar o projeto localmente.
Visual Studio Code para acessar e editar os códigos.
🔧 Instalação
Clone este repositório para o seu computador.
Abra o Visual Studio Code.
Clique em "Arquivo" (ou "Arquivo") no canto superior esquerdo da janela.
Selecione "Abrir Pasta" (ou "Abrir Pasta").
Após selecionar a pasta, ela será aberta no VSCode.
Você verá a estrutura de pastas e arquivos do projeto no painel lateral esquerdo.
A partir daqui, você pode explorar, editar e trabalhar com os arquivos da pasta aberta diretamente no VSCode.

⚙️ Executando os Testes
Próximos passos...

🛠️ Construído com

html5

🔨Tomada de Decisões
Python : Escolhi a linguagem de programação Python para fazer esse desafio porque é uma linguagem de alto nível, o que significa que ela abstrai muitos detalhes técnicos e permite que o programador se concentre na lógica do problema. É uma linguagem multiparadigma, o que significa que ela suporta diferentes estilos de programação conforme orientado a objetos por exemplo. Isso dá ao programador mais flexibilidade e expressividade para resolver o problema da forma que achar mais adequado. E por ser uma linguagem com uma sintaxe simples e clara, o que significa que ela é fácil de ler e escrever. Isso ajuda a evitar erros e tornar o código mais legível e manutenível.
Dados: Para armazenar os dados feitos através de um arquivo de texto porque seria uma forma simples e rápida de armazenar as informações dos pacientes, sem necessidade de instalar ou configurar um sistema de gerenciamento de banco de dados (SGBD) externo. Além disso, um arquivo de texto é fácil de ler e editar manualmente, se necessário, e pode ser usado por outras aplicações ou linguagens que aprendam a manipular arquivos. Um arquivo de texto também ocupa pouco espaço no disco e pode ser facilmente copiado ou transferido.
👨🏽‍💻 Versão das Tecnologias
Pitão 3
✒️ Autor
Liliane Rodrigues 🖥️
