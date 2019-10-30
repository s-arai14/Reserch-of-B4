
# VHDL学習メモ
---
## プログラム構成  
- ライブラリインポート  
  
      library ieee;  
      use ieee.std_logic_ 1164.all;  
  
      use <em>ライブラリ名</em>;  

- entity(入出力ポート定義)  
  
      entity <em>コンポート名</em>  
      	port(	A, B:	in	std_logic;
	        X, Y	out	std_logic	);  
      end	<em>コンポート名</em>;  
  
      port (<em>ポート名: 入/出力区別　データ型</em>);  

- architecture(内部回路の定義)  
  
      architecture  RTL  of  <em>コンポート名</em>  
      begin  
	  X <= A and B;  
    	  Y <= A or B;  
      end RTL;  

---

