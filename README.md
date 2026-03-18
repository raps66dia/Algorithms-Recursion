# Algorithms-Recursion
Ilya Yermakov
IT-2503
# Task 1
public class Test {
    public static void main(String[] args) {
        sepNum(5481);
    }
    public static void sepNum(int n) {
        if (n > 9) sepNum(n / 10);
        System.out.println(n % 10);
    }
}
<img width="1090" height="239" alt="изображение" src="https://github.com/user-attachments/assets/bcfdd534-1bfb-477c-9e7f-a68bba194c3a" />
