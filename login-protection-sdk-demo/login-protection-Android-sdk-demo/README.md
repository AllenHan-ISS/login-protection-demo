��½���� Android sdk ʾ�� demo
===

### demo ���в���

* 1������ģ��ҵ���ˣ�check demo�����з�����login-protection-check-demoĿ¼

* 2���޸� LoginActivity.java �� onCreate���������� bussinessId�����£�
```
     RjsbHandler.setBusinessId(getApplicationContext(), "YOUR_BUSINESS_ID");
```
* 3���޸� LoginTask.java�� PostData�����е�url����
```
    String url = "http://localhost:8182/login.do";
     // ���磬�滻���£�
    String url = "http://10.240.132.43:8182/login.do";
```
* 4�����ˣ����ú��޸���ɣ��������м���
