Respostas:


1- A JVM é responsável por interpretar e rodar um código JAVA em qualquer plataforma!


2- O JDK compila o código e o transmite em bytes para o JRE e o JRE contém bibliotecas de classes, arquivos de suporte e a JVM. 


3-     public class Aula1{
        public static void main(String[] args){
            System.out.println ("Terminei a primeira aula com um programa Java!");
            }
        }

    
4- Quando o arquivo .class é apagado, no blueJ não aparece mais a opção para rodar o código, teria que compilar novamente, para o arquivo .class ser         criado novamente para que possa ser executado.


5- Compila mas na hora da execução acontece o seguinte erro:

    Erro: o método main não foi encontrado na classe Main; defina o método main como:
       public static void main(String[] args)
    ou uma classe de aplicativo JavaFX deve expandir javafx.application.Application

    
7-

        PUBLIC CLASS EX6{
            PUBLIC STATIC VOID MAIN (STRING[] ARGS){
                SYSTEM.OUT.PRINTLN("WESLEY");
                SYSTEM.OUT.PRINTLN("PALMEIRAS");
            }
        }


O código acima gera o seguinte erro de compilação:


        EX6.java:1: error: class, interface, enum, or record expected
        PUBLIC CLASS EX6{
        ^
        EX6.java:4: error: class, interface, enum, or record expected
                SYSTEM.OUT.PRINTLN("PALMEIRAS");
                ^
        EX6.java:5: error: class, interface, enum, or record expected
            }
            ^
        3 errors
        

8- Acontece o seguinte erro na hora da compilação:


Main.java:1: error: class Start is public, should be declared in a file named Start.java
public class Start{
       ^
1 error
