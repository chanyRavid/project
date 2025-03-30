package com.example.traveltremp.bl;
import com.example.traveltremp.bl.Node;  

public class Edge {
    private final Node source;//צומת מקור
    private final Node destination;//צומת יעד
    private final double weight;//משקל
    public Edge(Node source, Node destination, double weight) {
        this.source = source;
        this.destination = destination;
        this.weight = weight;
    }
    public Node getSource() {
        return source;
    }
    public Node getDestination() {
        return destination;
    }
    public double getWeight() {
        return weight;
    }
    public String toString() {
        return "Edge{" +
                "source=" + source +
                ", destination=" + destination +
                ", weight=" + weight +
                '}';
    }

}
