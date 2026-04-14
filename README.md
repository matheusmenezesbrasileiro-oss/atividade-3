public class IMC {

    public static double calcularIMC(double peso, double altura) {
        return peso / (altura * altura);
    }

    public static void main(String[] args) {
        double peso = 70.0;
        double altura = 1.75;

        double imc = calcularIMC(peso, altura);
        System.out.println("IMC: " + imc);
    }
}
