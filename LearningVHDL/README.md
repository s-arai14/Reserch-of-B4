
# VHDL�w�K����
---
## �v���O�����\��  
### ���C�u�����C���|�[�g  
  
    library ieee;  
    use ieee.std_logic_ 1164.all;  
  
    use _���C�u������_ ;  

### entity(���o�̓|�[�g��`)  
  
    entity *�R���|�[�g��*  
    	port(	A, B:	in	std_logic;  
    		X, Y	out	std_logic	);  
    end	*�R���|�[�g��*;  
  
    port (*�|�[�g��: ��/�o�͋�ʁ@�f�[�^�^*);  

### architecture(������H�̒�`)  
  
    architecture  RTL  of  *�R���|�[�g��*  
    begin  
    	X <= A and B;  
    	Y <= A or B;  
    end RTL;  

---

