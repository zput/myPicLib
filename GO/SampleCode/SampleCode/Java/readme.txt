/**
 * ���org.apache.commons.codec.binary.Base64��
 * ��Ҫ����ܰ�commons-codec-1.9����commons-codec-1.8�������汾��
 * �ٷ����ص�ַ��http://commons.apache.org/proper/commons-codec/download_codec.cgi
 */

/**
 * �ṩ���պ����͸�����ƽ̨��Ϣ�ļӽ��ܽӿ�(UTF8������ַ���).
 * <ol>
 * 	<li>�������ظ�������Ϣ������ƽ̨</li>
 * 	<li>�������յ�����ƽ̨���͵���Ϣ����֤��Ϣ�İ�ȫ�ԣ�������Ϣ���н��ܡ�</li>
 * </ol>
 * ˵�����쳣java.security.InvalidKeyException:illegal Key Size�Ľ������
 * <ol>
 * 	<li>�ڹٷ���վ����JCE������Ȩ�޲����ļ���JDK7�����ص�ַ��
 *      http://www.oracle.com/technetwork/java/javase/downloads/jce-7-download-432124.html</li>
 * 	<li>���غ��ѹ�����Կ���local_policy.jar��US_export_policy.jar�Լ�readme.txt</li>
 * 	<li>�����װ��JRE��������jar�ļ��ŵ�%JRE_HOME%\lib\securityĿ¼�¸���ԭ�����ļ�</li>
 * 	<li>�����װ��JDK��������jar�ļ��ŵ�%JDK_HOME%\jre\lib\securityĿ¼�¸���ԭ���ļ�</li>
 * </ol>
 */
