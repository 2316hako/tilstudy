# Javaの画面表示方法
public class Main {
  public stutic void main(String[] args) {
    System.out.println("Hello World");
  }
}
実行結果
Hello World
と表示表示されます。なので"Hello World"の記載を書き換えてあげることで、実行結果を好きな英文、日本語に変更することができます。

# 計算をしよう
public class Main {
  public static void main(String[] args) {
    System.out.println("じゃがいも200円と人参150円の合計金額");
    System.out.println(200 + 150);
  }
}
実行結果
じゃがいも200円と人参150円の合計金額
350
と表示をされます。+の他にも、-や*(掛け算)や/(割り算)などの記号も使用できます。
例
System.out.println(35 - 10);         --- 25
System.out.println(-5 * 2);          --- -10
System.out.println(10 / 5);          --- 2
System.out.println("こたえは" + 50); ---こたは50

# 変数を使ってみよう
