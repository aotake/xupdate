# X-update �i���������E�����ՂŁ[�Ɓj
�A�b�v�f�[�^���W���[���uX-update�v�́AXoops X (ten)�ɓ������\�肳��Ă��郆�[�e�B���e�B�n���W���[���ł��B
�i���݊J���i�s���ł��̂ŁA�܂��{�Ԋ��ɂ͎g��Ȃ��ł��������B�j

�����XCL (Xoops Cube Legacy) 2.2 �ȍ~�ɃC���X�g�[�����邱�ƂŁA���̃��W���[����e�[�}�̃C���X�g�[���A�A�b�v�f�[�g��FTP�N���C�A���g���g�킸�ɐv���ɍs�����Ƃ��\�ɂȂ�܂��B

X-update�����ɂ��A�T�C�g�Ǘ��҂͊Ǘ��T�C�g�Ƀ��O�C�����ĊǗ���ʂ̃A�b�v�f�[�^���W���[��������u���E�U��ōs�������ŁA���W���[����gitHub�Ȃǔz�z�T�C�g����̃_�E�����[�h����C���X�g�[����A�b�v�f�[�g�A�e�[�}�̃C���X�g�[���Ȃǂ��������܂��B
�������Ad3�`���Ȃǂ̕����Ή����W���[�����A�C���X�g�[�����W���[�����i�����J���̃t�H���_���́j��ύX���ăC���X�g�[�����邱�Ƃ��ł��܂��B

���̃��W���[�����g�������b�g�́A���[�U�[�������ɗ��܂�܂���B�@���W���[����e�[�}��҂��A��ɍŐV�̌��J���|�W�g������xupdate���擾���Ă���邱�ƂƁA�����̌��J��������Ƃɂ��Q�d�Ǘ��̎�Ԃ�����J������܂��B

## �����ł���́H
* FTP�N���C�A���g�\�t�g�Ƀm�[�^�b�`�ŁA�Ή����W���[����e�[�}���C���X�g�[���ł��܂��B
* �Ή����W���[����e�[�}�̍ŐV�ł��Axupdate�̊Ǘ���ʑ��삾���Ŋe���J�T�[�o�[����_�E�����[�h�擾���A�𓀁E�W�J�E�A�b�v���[�h�܂łł��܂�����A���̌�Œʏ�̃��W���[���C���X�g�[��������s�������ł��B
* ���W���[�������ł͂Ȃ��A�e�[�}���X�g�A�T�C�g����_�E�����[�h�擾�`�A�b�v���[�h�܂łł��܂��B

## ����v��
X-update���g�����߂ɂ́A�ȉ��̊����K�{�܂��͐����ƂȂ�܂��B

* PHP 5.2.0�ȏ� (�K�{)
* safe���[�h�Ŗ������� (�قڕK�{�FGitHub����̃_�E�����[�h)
* cURL�G�N�X�e���V���� (�K�{)
* zip �g���֐��F--enable-zip��php���R���p�C������Ă��� (����)
* MySQL 5.0 �ȏ� (�K�{)
* Xoops Cube legacy 2.2.0 �ȏ�

# �g����
## �_�E�����[�h
�{���W���[���𓯍������AXOOPS X(ten) CorePack������܂��̂ŁA�T�C�g���n�߂���\�z����ꍇ��XOOPS Cube Legacy2.2�̃C���X�g�[������ꊇ���ĉ\��CorePack����̓����������߂��܂��B
* https://github.com/XoopsX/CorePack

## �C���X�g�[��
�ʏ�́Axoops_trust_path���̕����Ή����W���[���Ɠ��l�ł��B
�A���A���̃f�B���N�g���ɏ�������(�t�@�C���쐬)���� (777 �Ƃ� 707 �Ȃ�) ���K�v�ł��B�Ǘ���ʂŕύX�����ꍇ�ɂ́A�ύX�����f�B���N�g���ɏ������݌�����^���ĉ������B
* xoops_trust_path/uploads/xupdate

## ��ʐݒ�
* ���k�t�@�C���_�E�����[�h�E�W�J�p�t�H���_
�A�[�J�C�u���_�E�����[�h���ēW�J���邽�߂Ɏg�p����t�H���_�B(xoops_trust_path)�z���̃f�B���N�g�����w��A�ŏ��ƍŌ��"/"�i�X���b�V���j�͊܂߂܂���B�ʏ�́Auploads/xupdate�@�̂܂܂ł��g�p���������B
���̃t�H���_�ɂ́A707,777 �Ȃǂ̏������݌�����^���Ă��������B
* �g�p����FTP���C�u����
�T�[�o�[�Ƀt�@�C���Q���A�b�v���[�h����ۂɎg�p����FTP���C�u�����̑I���B�J�X�^��FTP�i�W���j��I�����Ė�肪�����ł��Ȃ��ꍇ�A
PHP_FTP�iFTP over SSL�p�j��A�J�X�^��SSH_FTP�����������������B
** �J�X�^��FTP�i�W���j
PHP��FTP�֐�����������Ă��Ȃ��ꍇ�́A�܂��͂��̃J�X�^��FTP��I�����܂��B
** PHP_FTP�iFTPS�p�j
PHP��FTP�֐�����������Ă���ꍇ�́A��������I���ł��܂��B�@�T�[�o�[��FTPS�ł̓]�����T�|�[�g����ꍇ�́A�����I�����āA������SSL(FTPS)��ݒ肵�܂��B
** �J�X�^��SSH_FTP
�T�[�o�[��SSH�̎g�p���T�|�[�g���Ă���ꍇ�A�W���̃J�X�^��FTP����������̕��������ɓ��삷��ꍇ������܂��BSSH�ڑ��̃|�[�g�ԍ����K�v�ł��B
** �J�X�^��SSH2�i���F�ؗp�j
�T�[�o�[��SSH�̌��F�؂��T�|�[�g���Ă���ꍇ�A�W���̃J�X�^��FTP����������̕��������ɓ��삷��ꍇ������܂��BSSH�ڑ��̃|�[�g�ԍ��ƁASSH���F�ؐڑ��ꍇ��private_key���K�v�ł��B

* SSL(FTPS)���g�p����
�O���ŁuPHP_FTP�iFTPS�p�j�v���w�肵���ꍇ�ɁASSL(FTPS)���g�p�\�ł��B

* FTP���O�C��ID�^FTP���O�C���p�X���[�h
���g�p�̃T�[�o�[�́AFTP���O�C��ID�ƃp�X���[�h����͂��܂��B

* SSH�ڑ��̃|�[�g
SSH_FTP�ڑ��A�܂��͌��F�ؐڑ��̏ꍇ��SSH�|�[�g�ԍ����w�肵�܂��Bdefault��22�B

* SSH���F�ؐڑ���private_key
SSH���F�ؐڑ��ꍇ��private_key���K�v�ł��B�Z�L�����e�B��Aprivate_key���T�[�o�[�ɕۑ����Ă����̂͊댯�Ȃ̂ŁA��ƊJ�n�O�ɓ��͂��A��Ɗ�����ɏ������Ă������Ƃ����������߂��܂��B

* �f�o�O�o�͂�\������
��肪�������Ȃ��ꍇ�́A�������u�͂��v�Ƃ��邱�ƂŁA�ǉ��f�o�O��񂪕\������܂��B

* �e�[�}URL
CMS Theme Finder ��URL�ŁA�ʏ�͕ύX�s�v�ł��B

# �C���X�g�[������
����̗���ɏ]���Ă���΂킩��Ǝv���܂����A�ȉ��̃T�C�g�Ȃǂ��Q�l�ɂ��Ă݂Ă��������B
* http://www.naaon.com/modules/dblog1/index.php?page=detail&bid=485#db76aebf
