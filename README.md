# Java8Predict

Java Predicate

Java Predicate tutorial shows how to use predicates in Java. With predicates, we can create code that is more clean and readable. 

Predicate in general meaning is a statement about something that is either true or false.

List<Integer> nums = List.of(2, 3, 1, 5, 6, 7, 8, 9, 12);

Predicate<Integer> btf = n -> n > 5;

nums.stream().filter(btf).forEach(System.out::println);
