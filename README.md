Padrão de projeto OBSERVER: Quando um conjunto de objetos tem que serem notificados e atualizados, sendo objetos de classes distintas, mas que possuem uma CLASSE ABSTRATA em comum.

Utilizado para quando quiser notificar grande quantidade de objetos que são de CLASSES diferentes, sendo que eles são notificados quando um estado comum entre eles é alterado.

Quando for notificar seguidores de um tópico em comum, assim a classe notificadora notifica todos eles sempre que houver uma atualização, sendo que os objetos não dependem um do outro.

Senha de fila de banco, por exemplo, a pessoa recebe uma senha, onde um monitor está notificando a senha que está em atendimento, até chegar na senha correspondente.
