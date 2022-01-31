# primeiro-projeto-

package aulapratica1;

public class Pessoa {

   private int codigo;
   private String nome;

    public Pessoa(int codigo, String nome){
       this.codigo=codigo;
       this.nome=nome;

    }

      public String getName() {
        return nome;

      }


}

package aulapratica1;

public class PessoaApp {

    public static void main(String[]  args){
        Pessoa pessoa1 = new Pessoa(1,"Helder");

        Pessoa pessoa2 = new Pessoa(2,"Ana");

        System.out.println("o nome do objeto pessoa1 e " +pessoa1.getName());
        System.out.println("o nome do objeto pessoa2 e " +pessoa2.getName());



    }



}
