package com.java.List;

import java.util.LinkedList;

public class Linkedlist {
    public static void main(String[] args) {
        LinkedList<String> house= new LinkedList<>();
        house.add("1bhk");
        house.add("2bhk");
        house.add("3bhk");
        house.add("4bhk");
        System.out.println(house);
        house.addFirst("Houses for sale");
        house.add(5,"bhk");
        house.addLast("closed sales");
        System.out.println(house);
        house.removeFirst();
        System.out.println(house);
        house.removeLast();
        System.out.println(house);
        house.getFirst();
        System.out.println(house.getFirst());
        house.getLast();
        System.out.println(house.getLast());
    }
}
