### S.O.L.I.D
 - Single Responsabolity Principle(SRP): é um padrão de desenvolvimento onde uma classe deve fazer somente uma coisa.
 Escrevemos classes e métodos todos os dias, a tendencia que fazermos classes gigante com muitas responsabilidades, oque torna a manutenção desse código custosa.
 Para tornar o código mais legivel e semples de receber manutenção preciamos aplicar o principio SRP.
 
 Como identificar um código que possa ser contruido ou refatorado com SRP?
 ``` CSharp
  public class Read
  {
    public int Id { get; set; }
  }
 ```
