1.~~C~~ **E**
    配列は、値を扱うインスタンス ≠ 値そのもの
    ・同じ型，互換性のある型の値しか扱えない。
    ・扱える要素数はインスタンス時に決める。のちに変更不可。
    
    インスタンスなので、生成にはnewを使う。

    int[] array = new int[0];
    を出力した際は，ハッシュコードが出力される。


2.~~E~~ **G**
    配列の宣言の[]は、データ型の後ろにも変数名の後ろにも記述できる。

    int[] array;
    int array[];           は両方とも使える。

    ※多次元配列でも、[]の位置は不問。分割してもエラーはコンパイルできる。


3.~~A~~ **E**
    int[] array = new int[0];
    配列型変数（左辺）では、配列の要素数は指定しない。
    ※ただ、配列インスタンス（右辺）への参照を代入しているだけ
    

4.**A,B,F**
    配列のインスタンスには，必ず扱える要素数を指定する。
    ・整数値（int型）でなくてはならない。
    ※int型の値を戻す式でも可。
    ・多次元配列でも1次元目と2次元目の要素数を指定する。

    ☆先に1次元目の配列インスタンスを生成することは可能。（2次元目は後から）
    
    int[][] array = new int[3][];
    int[0] = new int[3];
    int[1] = new int[3];
    int[2] = new int[3];
    
    このように，1次元目と2次元目のインスタンスを別々に生成することができる。
    ※この時，1次元目の要素数を省略することはできない。


    