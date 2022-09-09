<h1 align="center">Uso de Strings em Java</h1>

<p>A classe <strong>String</strong> é utilizada em Java para texto e outros caracteres. Vamos ver na prática. Crie uma nova Java Class no IntelliJ clicando com o botão direito em src > new > Java Class e coloque seu nome como MinhaString.</p>
<p>Você percebeu que foi criada a seguinte linha automaticamente:</p>
<blockquote>
public class MinhaString {<br>
}
</blockquote>
<p>Nossa aplicação ficará entre as chaves de abertura { e fechamento } do programa. Para que ele possa ser executado, será necessário chamar o método <i>Main</i>. Comece a digitar main que o programa vai sugerir o texto completo.</p>
<p>Deve aparecer o seguinte dentro das chaves:</p>
<blockquote>
public static void main(String[] args) <br>
        <br>
    }
</blockquote>
<p>Novamente vamos criar nossa aplicação dentro das chaves do método <i>main</i>.</p>
<p>Digite agora em uma nova linha: String texto = "Meu novo texto";</p>
<p>Lembre-se sempre de usar ; nos fechamentos!</p>
<p>Pule uma linha e agora chame a impressão com <i>sout</i>, novamente ele vai sugerir o preenchimento automático.</p>
<p>Dentro dos parênteses, escreva <strong>texto</strong>. Execute o programa. O que saiu impresso?</p>
<br>
<p>Caso tenha acontecido algum erro, o código deveria ter ficado assim:</p>
<blockquote>
public class MinhaString {<br>
    public static void main(String[] args) {<br>
        String texto = "Meu novo texto";<br>
        System.out.println(texto);<br>
<br>
    }<br>
}<br>
</blockquote>
<p>Em breve vamos aprender a chamar o Scanner, onde o usuário vai inserir um nome e o programa vai imprimir o nome junto com alguma outra coisa adicional.</p>
