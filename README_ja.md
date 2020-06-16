GridDB JDBC�h���C�o

## �T�v

GridDBJBC�h���C�o��SQL�C���^�t�F�[�X��񋟂��܂��B  

## �����

�ȉ��̊���C�N���C�A���g�̃r���h�ƃT���v���v���O�����̎��s���m�F���Ă��܂��B

    OS: CentOS 7.6(x64)
    GridDB server: V4.5 CE(Community Edition)

## �N�C�b�N�X�^�[�g

### �r���h

    $ ant
    
�����s����ƁAbin�t�H���_�̉��Ɉȉ��̃t�@�C���⃊���N���쐬����܂��B

    gridstore-jdbc.jar
    gridstore-jdbc-call-logging.jar

### �T���v���v���O�����̎��s
�N���X�^���umyCluster�v�A�}���`�N���X�^�������g���āA���O��GridDB�T�[�o���N�����Ă����K�v������܂��B

    $ export CLASSPATH=${CLASSPATH}:./bin/gridstore-jdbc.jar
    $ cp sample/ja/jdbc/JDBCSelect.java .
    $ javac JDBCSelect.java
    $ java JDBCSelect

## �h�L�������g
  �ڍׂ͈ȉ��̃h�L�������g���Q�Ƃ��Ă��������B
  - [JDBC�h���C�o������](https://github.com/griddb/docs-ja/blob/master/manuals/GridDB_JDBC_Driver_UserGuide/toc.md)
  - [SQL���t�@�����X](https://github.com/griddb/docs-ja/blob/master/manuals/GridDB_SQL_Reference/toc.md)

## �R�~���j�e�B
  * Issues  
    ����A�s��񍐂�issue�@�\�������p���������B
  * PullRequest  
    GridDB Contributor License Agreement(CLA_rev1.1.pdf)�ɓ��ӂ��Ē����K�v������܂��B
    PullRequest�@�\�������p�̏ꍇ��GridDB Contributor License Agreement�ɓ��ӂ������̂Ƃ݂Ȃ��܂��B

## ���C�Z���X
  C�N���C�A���g�̃��C�Z���X��Apache License, version 2.0�ł��B  
  �T�[�h�p�[�e�B�̃\�[�X�ƃ��C�Z���X�ɂ��Ă�3rd_party/3rd_party.md���Q�Ƃ��������B
