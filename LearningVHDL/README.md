
# VHDL�w�K����
---
## �v���O�����\��  
---
### ���C�u�����C���|�[�g  
��G  
  
    library ieee;  
    use ieee.std_logic_ 1164.all;  
  
library�͈ȉ��̂悤�ɃC���|�[�g����B  
  
    use _���C�u������_ ;  
---
### entity(���o�̓|�[�g��`)  
��G  
  
    entity SAMPLE(�R���|�[�g��)  is 
    	port(	A, B:	in	std_logic;  
    		X, Y	out	std_logic	);  
    end	SAMPLE;  
  
entity�͈ȉ��̂悤�ɒ�`����B  
  
    port (�|�[�g��: ���o�͋�ʁ@�f�[�^�^);  
#### �|�[�g��  
 - �p���i�啶���Ə������͋�ʂ���Ȃ��j  
 - �����i0�`9�j  
 - �L�� :_(�A���_�[���C��)�̂�  
  
#### ���o�͋��  
 - in		���@���͐�p  
 - out		���@�o�͐�p  
 - inout	���@���o�͗��p�i�o�����j  
  
#### �f�[�^�^  
 - std_logic		���@��{�̐M����  
 - std_logic_vector ()	���@�M�����̑�  
---
### architecture(������H�̒�`)  
��G  
  
    architecture  RTL(�L�q����)  of  SAMPLE(�R���|�[�g��)  
    begin  
    	X <= A and B;  
    	Y <= A or B;  
    end (RTL �ȗ���);  
  
#### ����������(�R���J�����g�E�X�e�[�g�����g)  
 - when else �\��  
�g�p�@  
  
    �o��  <=	�������̒l when ������1 else  
    		�������̒l when ������2 else  
    		.......  
    		�s�������̒l;  
  
 - with select �\��  
 - port map�@�Ȃǂ̃C���X�^���V�G�[�V����  
---

