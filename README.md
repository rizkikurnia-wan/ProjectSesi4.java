public class Pola1 {
    public static void main(String[] args) {
        for (int i = 1; i <= 4; i++) {
            for (int j = 1; j <= i; j++) {
                System.out.print("* ");
            }
            System.out.println();
        }
    }
}



public class Pola2 {
    public static void main(String[] args) {
        int num = 1;
        int count = 0;

        for (int i = 1; i <= 4; i++) {
            count = 0;

            int batas = (i == 3) ? 4 : 5;

            while (count < batas) {

                if (num != 6 && num != 12 && num != 17 && num != 23) {
                    System.out.print(num + " ");
                    count++;
                }
                num++;
            }
            System.out.println();
        }
    }
}


public class Pola3 {
    public static void main(String[] args) {
        int[][] array = {
            {1, 2, 3, 4, 5},
            {20, 19, 18, 17, 16},
            {6, 7, 8, 9, 10},
            {15, 14, 13, 12, 11}
        };

        for (int i = 0; i < 4; i++) {
            for (int j = 0; j < 5; j++) {
                System.out.print(array[i][j] + " ");
            }
            System.out.println();
        }
    }
}




public class Pola4 {
    public static void main(String[] args) {
        int[][] array = {
            {-1, 0, -1, 0, -1},
            {0, -1, 0, -1, 0},
            {-1, 0, -1, 0, -1},
            {0, -1, 0, -1, 0}
        };

        for (int i = 0; i < 4; i++) {
            for (int j = 0; j < 5; j++) {
                System.out.print(array[i][j] + " ");
            }
            System.out.println();
        }
    }
}




public class Pola5 {
    public static void main(String[] args) {
        char[][] array = {
            {'*'},
            {'0'},
            {'*', '*'},
            {'0', '1'},
            {'*', '*', '*'},
            {'0', '1', '2'}
        };

        for (int i = 0; i < array.length; i++) {
            for (int j = 0; j < array[i].length; j++) {
                System.out.print(array[i][j] + " ");
            }
            System.out.println();
        }
    }
}
