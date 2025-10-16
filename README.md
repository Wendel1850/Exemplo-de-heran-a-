# Exemplo-de-heran-a-
// Classe pai
class Veiculo {
    private String cor;
    private int velocidade;

    public Veiculo(String cor, int velocidade) {
        this.cor = cor;
        this.velocidade = velocidade;
    }

    public void acelerar() {
        System.out.println("Acelerando...");
    }

    public void frear() {
        System.out.println("Freando...");
    }

    public String getCor() {
        return cor;
    }

    public int getVelocidade() {
        return velocidade;
    }
}

// Classe filha
class Carro extends Veiculo {
    private int numeroDePortas;

    public Carro(String cor
