import java.util.*;
class Sort{
    public static void bubble(ArrayList<Integer> numbers){
      for (int i = 0; i < numbers.size() - 1; i++) {
        for (int x = 0; x < numbers.size() - 1; x++) {
          if (numbers.get(x + 1) < numbers.get(x)) {
            numbers.add(x, numbers.get(x + 1));
            numbers.remove(x + 2);
          }
        }
      }
    }
    
    public static void selection(ArrayList<Integer> numbers){
      int min;
      for (int i = 0; i < numbers.size() - 1; i++) {
        min = i;
        for (int x = i; x < numbers.size(); x++) {
          if (numbers.get(x) < numbers.get(min)) {
            min = x;
          }
        }
        numbers.add(i, numbers.get(min));
        numbers.remove(min + 1);
      }
    }

    public static void insertion(ArrayList<Integer> numbers){
      for (int i = 1; i < numbers.size(); i++) {
        int idx = 0;
        for (int x = 0; numbers.get(i) > numbers.get(x); x++) {
          idx++;
        }
        numbers.add(idx, numbers.get(i));
        numbers.remove(i + 1);
      }
    }
}
