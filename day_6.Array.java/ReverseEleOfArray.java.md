class Main {
    public static void main(String[] args) {
        String original = "Hello";
        
        char[] chars = original.toCharArray();
        System.out.println("Original String:");
        for (char c : chars) {
            System.out.println(c);
        }
        
        int left = 0;
        int right = chars.length - 1;
        
        while (left < right) {
            char temp = chars[left];
            chars[left] = chars[right];
            chars[right] = temp;
            left++;
            right--;
        }
        
        String reversedString = new String(chars);
        System.out.println("Reversed String:");
        System.out.println(reversedString);
    }
}
