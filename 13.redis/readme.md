#redi����
��Դ C���� ֧��������� �����ڴ� �ɳ־û���Ӳ��
key-value
##�ص�
1.Զ���ֵ䣬������������Ӧ�ó���ͨ��TCPЭ������ֵ��е����ݡ�
2.redis key-value���ݿ⡣
3.�ڴ����ݿ� ���֧�ֳ־û�
4.֧�ֶ����������� String�ַ��� hash��ϣ list���� set���򼯺� zset���򼯺�
#�﷨
redis-cli.exe --h123.57.143.189
##�ַ���
�������������ͣ����Դ洢�������͵��ַ��������������ơ�
set ����һ��ֵ
get ��ȡһ��ֵ
incr ����1
incrby num  count Ϊnum����countֵ
incrbyfloat
strlen key ��ȡ����Ӧ��ֵ�ĳ���
##��ϣ���� h = hash
hset ����ֵ
hmset ���ö��ֵ
hget ��ȡֵ 
hgetall ��ȡ����ֵ
hdel ɾ��ֵ
������ȡ��
key person_100 name tom age 6
##�������� list
LPUSH  key value ��key��������Ԫ�أ���������ĳ���
RPUSH key value �������ұ߷���Ԫ�أ���������ĳ���
LPOP key �Ƴ�������ߵĵ�һ��Ԫ�أ������Ƴ���ֵ
RPOP key �Ƴ������ұߵĵ�һ��Ԫ�أ������Ƴ���ֵ
LRANGE key star end ��ȡ�����е�һ��Ƭ�ϡ�
#����
Ψһ������
SADD �򼯺������Ԫ��
SREM �Ӽ�����ɾ��Ԫ��
SMEMBERS ���ؼ��������е�Ԫ��
#���򼯺�
ÿһ��Ԫ�ض�������һ�����������԰�������ȡԪ��
ZADD key score member �򼯺������Ԫ��
ZREM key member ɾ��Ԫ��
ZRANGE key start stop ����ΧԪ��






