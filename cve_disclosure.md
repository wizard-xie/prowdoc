## CVE ��ǰ��¶����

### ��������

��gitee ƽ̨�� CVE issue ������ɺ�֧��ʹ���������� CVE �ļ������ļ�֧�ֵ���CVE ��������ƽ̨�� 

### �������

#### 1. cve-manager ÿ�춨ʱ�����ѷ�����ɵ�  CVE �������ʼ���֪��ȫίԱ���Ա��
   
   ����ͼ��

```flow
st=>start: issue �����˶�cve���з���
op=>operation: cve-managerУ��������
cond=>condition: �������?
oprec=>operation: ��¼CVE������¶���ݱ�
e=>end: ����

st->op->cond
cond(yes)->oprec
cond(no)->e
```
                    


#### 2. cve-manager �ṩ `/disclosure` ָ���ȫίԱ��Ա���յ��ʼ����ڶ�ӦCVE issue ������ʹ�ø�ָ���������ǰ��¶��CVE�ļ����ϴ�OBS��


#### 3.  SA �����ṩ�ֶ������Ͷ�ʱ�������ַ�ʽ��CVE�ļ����������


| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

| Item      | Value |
| --------- | -----:|
| Computer  | $1600 |
| Phone     |   $12 |
| Pipe      |    $1 |
                
----


                
### ��������ͼ Flowchart

```flow
st=>start: �û���½
op=>operation: ��½����
cond=>condition: ��½�ɹ� Yes or No?
e=>end: �����̨

st->op->cond
cond(yes)->e
cond(no)->op
```
                    
### ��������ͼ Sequence Diagram
                    
```seq
Andrew->China: Says Hello 
Note right of China: China thinks\nabout it 
China-->Andrew: How are you? 
Andrew->>China: I am good thanks!
```

### End