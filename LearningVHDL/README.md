
# VHDL�w�K����
---
## �v���O�����\��  
### ���C�u�����C���|�[�g  
  
    library ieee;  
    use ieee.std_logic_ 1164.all;  
  
library�͈ȉ��̂悤�ɃC���|�[�g����B  
    use _���C�u������_ ;  

### entity(���o�̓|�[�g��`)  
  
    entity SAMPLE(�R���|�[�g��)  is 
    	port(	A, B:	in	std_logic;  
    		X, Y	out	std_logic	);  
    end	SAMPLE;  
  
entity�͈ȉ��̂悤�ɒ�`����B  
    port (�|�[�g��: ��/�o�͋�ʁ@�f�[�^�^);  
���o�̓|�[�g�́A
 - �p���i�啶���Ə������͋�ʂ���Ȃ��j
 - �����i0�`9�j
 - �L�� :_(�A���_�[���C��)�̂�

### architecture(������H�̒�`)  
  
    architecture  RTL  of  SAMPLE(�R���|�[�g��)  
    begin  
    	X <= A and B;  
    	Y <= A or B;  
    end RTL;  

---

