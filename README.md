import java.util.*;
public class Main
{
	public static void main(String[] args) {
		Set<String> set = new HashSet<>();
        set.add("Apple");
        set.add("Banana");
        set.add("Orange");
        set.add("Apple");
        System.out.println("Set Elements:");
        for(String fruit : set){
            System.out.println(fruit);
        }
        List<Integer> list = new ArrayList<>();
        list.add(10);
        list.add(20);
        list.add(30);

        System.out.println("\nList Elements:");
        for (Integer number : list) {
            System.out.println(number);
        }
        Map<String, Integer> map = new HashMap<>();
        map.put("One", 1);
        map.put("Two", 2);
        map.put("Three", 3);

        System.out.println("\nMap Elements:");
        for (Map.Entry en : map.entrySet()) {
            System.out.println(en.getKey() + " => " + en.getValue());
        }
	}
}
