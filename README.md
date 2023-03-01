# Code-for-Class-file-Main.java-
    public static void main(String[] arg) {

    Dog bengie = new Dog("bengie.png", "Bengie", 7);
    Dog gracie = new Dog("gracie.png", "Gracie", 5);

    Cat rami = new Cat("rami.png", "Rami", 12);
    rami.birthday();
    System.out.println("Birthday of Rami:" + rami.getAge() + "th February");
    rami.madeSound();
    bengie.madeSound();

    List<Animal> animals = new ArrayList<>();
    animals.add(bengie);
    animals.add(rami);
    animals.add(gracie);

        animals.get(1).madeSound();

      // Animal a = new Animal("x.png", "X", 10);
        rami.pet();


    }

}
