<h1 align="center">Segurança e Auditoria de SI</h1>

<h1 align="center">Sensor de Enchentes</h1>
<h2>Descrição do projeto</h2>
Aplicação com Arduino para identificar possíveis enchentes

<h2>Como funciona</h2>
Os dados da aplicação são enviados através de uma API e estão organizados da seguinte forma:

  - diaSemana;
  - horario;
  - nivelRio;

A aplicação irá executar um script toda vez que a boia emitir o sinal de que o nível da água subiu.
Com esses dados, gerar um arquivo (txt/CSV) com as informações coletadas.
Estrutura do arquivo:

| diaSemana | horario | nivelRio | alertaEnviado |
|:---------:|:-------:|:--------:|:-------------:|
|           |         |          |               |
  
Se a boia emitir sinais 3x no dia, a mesma envia um alerta de segurança 

<h1 align="center">Autores</h1>

  - Álvaro C. Rumpel
  - Luan V. da Costa
  - Irakitã Luan Soares da Rosa
