
# VHDL学習メモ
---
## プログラム構成  
### ライブラリインポート  
  
    library ieee;  
    use ieee.std_logic_ 1164.all;  
  
libraryは以下のようにインポートする。  
    use _ライブラリ名_ ;  

### entity(入出力ポート定義)  
  
    entity SAMPLE(コンポート名)  is 
    	port(	A, B:	in	std_logic;  
    		X, Y	out	std_logic	);  
    end	SAMPLE;  
  
entityは以下のように定義する。  
  
    port (ポート名: 入出力区別　データ型);  
#### ポート名  
 - 英字（大文字と小文字は区別されない）  
 - 数字（0～9）  
 - 記号 :_(アンダーライン)のみ  
  
#### 入出力区別  
 - in		→　入力専用  
 - out		→　出力専用  
 - inout	→　入出力両用（双方向）  
  
#### データ型  
 - std_logic		→　一本の信号線  
 - std_logic_vector ()	→　信号線の束  

### architecture(内部回路の定義)  
  
    architecture  RTL  of  SAMPLE(コンポート名)  
    begin  
    	X <= A and B;  
    	Y <= A or B;  
    end RTL;  

---

