# Java-Design-Pattern
This is a document with examples of java code based on Design 

Plain Old Java Objects - Velhos Objetos Java Plenos

Na verdade são objetos com design simples. Um bean é um tipo de POJO.

Segue um exemplo de um bean:

```java
public class Carro implements java.io.Serializable {  
	private String nome;
	private String cor;
	public Carro() {
	}
	public Carro(String nome, String cor) {
	     this.nome = nome;
	     this.cor = cor;
	}
	public String getCor() {
	     return cor;
	}
	public void setCor(String cor) {
	     this.cor = cor;
	}
	public String getNome() {
	     return nome;
	}
	public void setNome(String nome) {
	     this.nome = nome;
	}
}
```
