# Trab4
Trabalho 4 - Supermercado Online

→Para compilar:
  make
  ou
  javac -cp dependencies/\* -d . *.java

→Para executar:
   make run
   ou
   java -cp ":dependencies/mail.jar:dependencies/activation.jar:dependencies/itextpdf-5.5.6.jar" br.usp.icmc.supermercado.Main

Obs: O programa é melhor vizualizado em tela maximizada.(Opcional)

→ Pontos extras:
  -Relatorios diario e mensal em PDF: iText
  -Envio de e-mails: JavaMail API
  -Design pattern: Observer (class Requisitado). 
	Descrição: todos os clientes que desejam um produto que não esta mais disponivel(fora de 	estoque ou vencido), são alertados quando este produto é atualizado no sistema.
