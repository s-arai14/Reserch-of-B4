
# VHDL�w�K����
---
## �v���O�����\��  
- ���C�u�����C���|�[�g  
  
      library ieee;  
      use ieee.std_logic_ 1164.all;  
  
      use <em>���C�u������</em>;  

- entity(���o�̓|�[�g��`)  
  
      entity <em>�R���|�[�g��</em>  
      	port(	A, B:	in	std_logic;
	        X, Y	out	std_logic	);  
      end	<em>�R���|�[�g��</em>;  
  
      port (<em>�|�[�g��: ��/�o�͋�ʁ@�f�[�^�^</em>);  

- architecture(������H�̒�`)  
  
      architecture  RTL  of  <em>�R���|�[�g��</em>  
      begin  
	  X <= A and B;  
    	  Y <= A or B;  
      end RTL;  

---

