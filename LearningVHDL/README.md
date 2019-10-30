
# VHDL学習メモ
---
## プログラム構成  
### ライブラリインポート  
  
    library ieee;  
    use ieee.std_logic_ 1164.all;  
  
    use _ライブラリ名_ ;  

### entity(入出力ポート定義)  
  
    entity *コンポート名*  
    	port(	A, B:	in	std_logic;  
    		X, Y	out	std_logic	);  
    end	*コンポート名*;  
  
    port (*ポート名: 入/出力区別　データ型*);  

### architecture(内部回路の定義)  
  
    architecture  RTL  of  *コンポート名*  
    begin  
    	X <= A and B;  
    	Y <= A or B;  
    end RTL;  

---

