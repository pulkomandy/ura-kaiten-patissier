/*==========================================================================
 *
 *  Copyright (C) 2008 ����ӂ��`�閧��n(Alpha Secret Base). All Rights Reserved.
 *
 *  ���Q�[���^�C�g���F�������Ă�p�e�B�V�G�I
 *  ���W������      �F����y��]�A�N�V�����p�Y��
 *  ���v���C�l��    �F��l
 *  ���o�[�W����    �F1.03
 *  �����J���t      �F2008/06/09
 *  ���X�V���t      �F2008/07/10
 *
 ==========================================================================*/

�E�͂��߂�
  GP2X�I���W�i���Q�[�������Ă�p�e�B�V�G�I�̗��ʃo�[�W�����ł��B
  ���p�e�B�V�G�ł́A�\�ʂł͎g��Ȃ������e�N�j�b�N�A�M�~�b�N�A�����ė����ă~�X�ȂǁA����Փx��50�ʂ��҂��\���Ă��܂��B
  �ȒP�ɃN���A�ł��Ă��܂��͕̂�����Ȃ��I�Ƃ����}�]�Q�[�}�[�ɂ҂�����̂��������ȓ�Փx�ɂȂ��Ă��܂��B

  ���v���C�t�@�C�����쐬���邽�߃f�B�X�N�e�ʂ��K�v�ł��B
  GP2X�ł�SD�J�[�h����̋N���𐄏����܂��B
  Windows�ł�fullscreen.bat�����s����ƃt���X�N���[���ŋN�����܂��B
  Windows�ł�fullscreen2.bat�����s����ƂQ�{�g��̃t���X�N���[���ŋN�����܂��B
  Windows�ł�window2.bat�����s����ƂQ�{�g��̃E�C���h�E�ŋN�����܂��B
  ���s�t�@�C���̈����I�v�V����
    -f �t���X�N���[��
    -r �Q�{�g��i640*480�j

  ��y�ɒn�`���g�����A�N�V�����p�Y�����y����ł��炦����ǂ��Ǝv���܂��B

  �܂����̃Q�[���Ɏg���Ă���t�@�C���́u���炩���C�Z���X�v�ł��B
  �Q�[��������Ă݂����A�������������͎��R�ɗ��p���č\���܂���B

  �g���C�A���O���E�T�[�r�X�̓���В��ɁuACTION LOVE!�v�̑莚�������Ă��������܂����B
  �摜�͂��炩���C�Z���X�ƌ������ŋ����������܂����B
  ���̗͋���ACTION LOVE!�̗l�ɁA�F��������̃Q�[��������Ă݂܂��񂩁H

  �e�v���b�g�z�[���ł̎��s�t�@�C�������^���Ă��܂��B
  RotateGear.exe :Windows�p�̎��s�t�@�C��
  RotateGear     :DebianLinux�p�̎��s�t�@�C��
  RotateGear.gpe :GP2X�p�̎��s�t�@�C��

  Windows�ł��R���p�C������ɂ�������
    makefile��Makefile.win�ł��B

  gp2x�ł��R���p�C������ɂ�������
    makefile��Makefile.gp2x�ł��B

  MacOSX�ł��R���p�C������ɂ�������
    makefile��Makefile.macosx�ł��B

  Linux�ł��R���p�C������ɂ�������
    makefile��Makefile.linux�ł��B


  �{�v���O������SDL(Simple Directmedia Layer)���g���č쐬���Ă��܂�
  SDL��LGPL�ɏ]���Ĕz�z����Ă��܂�
  http://www.libsdl.org/license.php

  SDL(Simple Directmedia Layer)
  http://www.libsdl.org/

�E������@
  �㉺�F���ڂ̑I��
  ���E�F�L�����N�^�[�̈ړ��A���ڂ̑I��
  �p�b�h1�i�L�[�{�[�h:Z�AGP2X:X�j    �F�ǂ������Ȃ���{�^���Œn�`�̉�]�@���ڂ̌���
  �p�b�h2�i�L�[�{�[�h:X�AGP2X:B�j    �F�W�����v�A��L�[�ł��W�����v�ł��܂��B
  �p�b�h3�i�L�[�{�[�h:C�AGP2X:Y�j    �F���j���[
  �p�b�h7�i�L�[�{�[�h:F1�AGP2X:Vol-�j�F���ʂ�����������
  �p�b�h8�i�L�[�{�[�h:F2�AGP2X:Vol+�j�F���ʂ�傫������
  �L�[�{�[�h:ESC�AGP2X:L+R+HOME      �F�����I��

�E���j���[
  GameStart  �F�Q�[�����J�n���܂��B���E�ŃX�e�[�W�̑I��
  MamViwe    �F�X�e�[�W�����邱�Ƃ��ł��܂��B���E�ŃX�e�[�W�̑I��
  StageSelect�F�X�e�[�W��I��ŗV�Ԃ��Ƃ��ł��܂��B�P�̃X�e�[�W���J��Ԃ��V�Ԃ̂ɍœK�ł��B
  Replay     �F�ۑ�����Ă��郊�v���C���Đ����܂��BALL�F�A���Đ��AONE�F�P�X�e�[�W�̂ݍĐ��B
               �P�{�^���ōő��^�C���A�Q�{�^���ōŏ���]�̃��v���C���Đ����܂��B
  Tutorial   �F��������ł��B
  Option     �F�Q�[�����̐ݒ��T�E���h�e�X�g�ȂǁB����i���{��A�p��j�̐ݒ���ł��܂��B
  Exit       �F�A�v���P�[�V�������I�����܂��B

�E�V�X�e��
  �ǂ���������ԂłP�{�^���������ƒn�`���񂵂đ���ɂ��鎖���ł��܂��B
  ���ׂĂ̍ޗ����W�߂�ƃX�e�[�W�N���A�ƂȂ�A���̃X�e�[�W�ɐi�ގ����ł��܂��B
  ���Ԃ𒆐S�ɓ�������Ȃǂ����݂��܂��B�������񂷂̂��ߓ��Ȃ̂��T���Ă݂Ă��������B

  �d�|��
    ����    �F���ԂƐ��łȂ����Ă��镨�͎��Ԃ𒆐S�ɓ����܂��B
              ���ԂƂȂ���̂́A�̂�鏰�A�u���b�N�A�ޗ��g���C������܂��B
    ��      �F���͉��������ł��܂��B
              �����Q�����ɉ������͂ł��܂���B���ɔ�������ꍇ�W�����v�͂ł��܂���B
    �X�C�b�`�F�����F�̃u���b�N�����������ł��܂��B
              �X�C�b�`�̓u���b�N�┠���d�˂鎖�ŉ����܂��B

  �e�X�e�[�W�ɂ͖ڕW�^�C���A�ڕW��]�񐔂��ݒ肳��Ă��܂��B
  �X�e�[�W�Z���N�g��ʂŊm�F�ł��܂��B
  �L�^�ɒ��킵�Ă݂܂��傤�B

  �A�C�e�����Ō�̈�܂Ŏ��ƁA�V�[�N���b�g�A�C�e�����o�����܂��B
  �T���Ă݂܂��傤�B
  ���ׂČ�����ƃG���f�B���O���ω����܂��B

�E�X�g�[���[
  ���l�̃s�s�͎q������D���I
  �����璬�֗������Ȃ���A�q���B�ɂ��َq������Ă��܂��B

  �s�s����邨�َq�͕s�v�c�Ȃ��َq�B
  ���̂��َq��H�ׂ�Ƃ݂�Ȋy�����Ȃ�܂��B
  �������s�s�͍ޗ��T���̗��ɏo������̂ł����B

�E�X�^�b�t
  D.K
  kenmo
  ��񂫂�
  �N�~
  taro
  �t
  HIZ
  ��e��
  �I�����_
  maro
  nanasi
  ���߂�
  teru
  �J���^
  ���ʌ�����
  �y�Q
  �Z��
  �M��
  LiV
  �Ђ�
  KaOS
  BCD
  ��F
  ����
  �Q�[���w��2000�̊F����
  �e�X�g�v���C���Ă����������F����

�E�ӎ�
  GP2X�ł̊J���ɂ������Ĉ�F����ɂ͂����b�ɂȂ�܂����B
  ��F�����HP�FThe 59TH STREET ROOM
  URL�Fhttp://homepage2.nifty.com/isshiki/

  �L�����N�^�[�f�U�C���A�A�j���[�V�������N�~����ɍ쐬���Ă��������܂����B

  BGM�A���ʉ�����񂫂�����ɍ쐬���Ă��������܂����B
  ��񂫂������HP�FNamelessElementLab
  URL�Fhttp://d.hatena.ne.jp/wang-zhi/

  �X�e�[�W�̍쐬�A�����A�O���t�B�b�N�̍쐬���t����ɋ��͂��Ă��������܂����B

  ���A�X�e�[�W�̒�����kenmo����ɋ��͂��Ă��������܂����B

  �X�e�[�W�̍쐬����e������ɋ��͂��Ă��������܂����B
  ��e�������HP�F��e�@���̓��L
  URL�Fhttp://d.hatena.ne.jp/KouMikage/

  �X�e�[�W�̍쐬�����ʌ���������ɋ��͂��Ă��������܂����B
  ���ʌ����������HP�FHAFU ���ʌ�����
  URL�Fhttp://anime.geocities.jp/head_jockaa/

  �X�e�[�W�̍쐬��nanasi����ɋ��͂��Ă��������܂����B

  �X�e�[�W�̍쐬��maro����ɋ��͂��Ă��������܂����B

  �X�e�[�W�̍쐬���I�����_����ɋ��͂��Ă��������܂����B
  �I�����_�����HP�FAwesomeness In a Box
  URL�Fhttp://www.awesomenessinabox.com/

  �X�e�[�W�̍쐬��HIZ����ɋ��͂��Ă��������܂����B
  HIZ�����HP�FHIZ�̕��u
  URL�Fhttp://hizuoka.web.fc2.com/index.html

  �X�g�[���[�쐬���J���^����ɋ��͂��Ă��������܂����B

  �X�e�[�W�쐬��y�Q����ɋ��͂��Ă��������܂����B
  �y�Q�����HP�F�y�Q�Õ����X
  URL�Fhttp://tsutiuzu.blog41.fc2.com/

  �M�������[�̃C���X�g��Z�Ԃ���ɕ`���Ă��������܂����B

  �G���f�B���O�̃C���X�g��M���ɕ`���Ă��������܂����B

  �G���f�B���O�̃C���X�g��LiV����ɕ`���Ă��������܂����B
  LiV�����HP�Fmixi
  URL�Fhttp://mixi.jp/show_friend.pl?id=18159530

  �M�������[�̃C���X�g���Ђł���ɕ`���Ă��������܂����B

  �M�������[�̃C���X�g��KaOS����ɕ`���Ă��������܂����B
  KaOS�����HP�F�d�]�d�g���M�A��
  URL�Fhttp://www.geocities.jp/denno_denpa/

  �^�C�g���� ACTION LOVE! �𓡖삳��ɏ����Ă��������܂����B
  ���삳���HP�F�g���C�A���O���E�T�[�r�X
  URL�Fhttp://www.triangleservice.co.jp/

  ���͂��Ă������������X�{���ɂ��肪�Ƃ��������܂��B


�E��ӌ��A�����z�Ȃǂ͂�����܂ŁB
    dk@red.interq.or.jp
    http://maglog.jp/alpha-secret-base/


�E�X�V����

  2008/07/10    Ver 1.03
                2�{�g��@�\���������܂����B
                320*240�̉𑜓x�ɑΉ����Ă��Ȃ����͂��߂��Ă݂Ă��������B

  2008/06/30    Ver 1.02
                �^�C�g����ACTION LOVE!��ǉ����܂����B

  2008/06/13    Ver 1.01
                �p��ɑΉ����܂����BOption�ŕύX�ł��܂��B
                �M�������[�̒ǉ��B
                �^�C�g�����S�̕ύX�B

  2008/06/08    Ver 1.00
                ���J

  2008/06/07    �]���łP
                ��50�ʂ̍쐬
                �ڕW�^�C���̐ݒ�


�E���C�Z���X
�����Ă�p�e�B�V�G�I �� ���炩���C�Z���X �̂��Ɣz�z����܂��B

<JAPANESE>
���C�Z���X
-------

Copyright 2008 ����ӂ��`�閧��n. All rights reserved. 

  �ƐӁE����E�z�z 
  �_�����R�g 
    �{�Q�[���́u�݂�ȂŊy�����v���炩���ł��B 

    �{�Q�[��������������C�W�����o�[�W������z�z���Ă��A����OK�ł��B�������̂��[���I 
    ���������Ƃ������������l�̖��O���A������₷���Ƃ���ɏ����Ă����� 
    ������������܂���B 

    �i�C�X�ȉ������o������@���[���Ȃǂŋ����āB���ɂ��V�΂��Ă��������B 

    �����Ƃ���؂��ĂȂ����͍̂D���ɃR�s�[���Ĕz�z��������Č��\���\�B 


<ENGLISH>
License
-------

Copyright 2008  Alpha Secret Base. All rights reserved.

Disclaimer / Copyright / Redistribution 

  This game is under the "Yawaraka(flexible)" license. 

    Use at your own risk. 
    You can freely modify and redistribute it. Conversions are really Fun! 
    You should write the changes and the person who did them in the 
    readme file or in a place that was obvious to find. 

    If you make a cool modification, please tell me via mail or by any 
    other means, even though that's not a condition of the license. 
    Let me enjoy your changes too. 

    If you have not done any modifications, you can freely distribute 
    without problems.


