public static void main(String[] args) {
        ArrayList<String> dulces = new ArrayList<>();

        dulces.add("Paleta");
        dulces.add("Chocolate");
        dulces.add("Bombon");

        System.out.println("Lista inicial: " + dulces);
        System.out.println("Total de dulces (size): " + dulces.size());

        dulces.remove("Bombon");

        System.out.println("\nLista después de eliminar: " + dulces);
        System.out.println("¿Hay Bombon?: " + dulces.contains("Chocolate"));
        System.out.println("Elemento en posición 0: " + dulces.get(0));
    }