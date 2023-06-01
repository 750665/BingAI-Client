<h1 align="center">BingAI-Client</h1>

<p align="center">
<a href="https://github.com/xbzstudio/BingAI-Client/blob/main/LICENSE"><img src="https://img.shields.io/badge/LICENSE-MIT-green"></a><img src="https://img.shields.io/badge/Language-Python-blue"><img src="https://img.shields.io/badge/Language-Javascript-yellow"><a href="https://github.com/xbzstudio"><img src="https://img.shields.io/badge/Github-xbzstudio-red"></a><a href="https://github.com/XiaBeiZe-Studio2022"><img src="https://img.shields.io/badge/Studio-%E4%B8%8B%E5%8C%97%E6%B3%BD%E5%B7%A5%E4%BD%9C%E5%AE%A4-red"></a>
</p>

# ����

BingAI-Client�ṩ��Microsoft New Bing��web�ͻ��˺ͷ���ˡ��ͻ��˻���[Angular](https://angular.cn/)������˻���[FastAPI](https://fastapi.tiangolo.com/zh/)��[EdgeGPT](https://github.com/acheong08/EdgeGPT)���ڱ��ز����New Bing�����з���˳��򼴿ɿ�ʼʹ�ÿͻ��ˡ��������Ҫ��Ҳ�����ڷ������ϲ���New Bing�����ڱ������ӵ���������New Bing������˽����Զ���Bing�л���Sydneyģʽ�Խ���鷳�����ơ�

# ��ʼ

<details>
  <summary>

## ��Ƶ�̳̣��ھɰ�����ʾ�������ο���

 </summary>
     
(��Ϊgithub���ļ���С����,���ԲŻ���ôģ��,�����!����뿴�������Ƶ��[���](https://v.superbed.cn/play/6460ccc70d2dde5777223e9c)):


https://github.com/viopsa233/BingAI-Client/assets/118115208/dea14d0a-7c05-4938-8b4a-0228ef04916b


</details>

<details>
  <summary>


## ͼ�Ľ̳�
</summary>
  
����ǰ��ȷ����ӵ�� `Python` ���ȶ��߰汾���Ƽ�3.10����һ�� `VPN` ������һ������ʹ��New Bing�� `Microsoft�˺�` ��

������ӣ�  
Python 3.10.10���أ�[https://www.python.org/downloads/release/python-31010/](https://www.python.org/downloads/release/python-31010/)  
Geph����ͨ���أ�[https://f001.backblazeb2.com/file/geph4-dl/geph-releases/windows-stable/4.7.10/geph-windows-setup.exe](https://f001.backblazeb2.com/file/geph4-dl/geph-releases/windows-stable/4.7.10/geph-windows-setup.exe)


# �Զ�����



����ȷ�����и߰汾��Python���Ƽ�3.10�������ﲻ����׸����

�������ر���Ŀ��ZIPѹ��������ѹ��

Ȼ��������а�װ���[Cookie Editor](https://microsoftedge.microsoft.com/addons/detail/cookie-editor/ajfboaconbpkglpfanbmlfgojgndmhmc)��

��װ��ɺ󣬴����VPN������[Microsoft New Bing](https://bing.com/new)�������New Bing����Ľ��档Ȼ��㿪Cookie Editor������ͼƬ�еİ�ť��

![image](https://user-images.githubusercontent.com/119436353/235375933-d7e81988-fc6b-423b-841f-98575d310e32.png)

Ȼ��Ϳ����ˡ�����֮�󣬴���Ŀ�ļ��У��򿪸�Ŀ¼�µ�`cookie.json`������ctrl+v�ѸղŸ��Ƶ��Ķ��������ȥ�������ļ���Ȼ���˳���

### ����Run�ļ����µ�`Install Libs.bat`��

�ڰ�Install Libs������Ϻ������ڶ���ʹ��BingAI-Clientʱ�Ͳ���������һ��Install Libs�ˡ�

Ȼ������Run�ļ����µ�`Run.bat`��

�������������ѯ�����Ƿ��������������ӣ������Ÿ��������ʹ��New Bing�������ѡ��true����Ϳ���ʹ����Ĺ���ip������ip���ػ���ַ�ʹ򿪱����ļ�������BingAI-Client�ͻ��ˣ����ѡ��false����ֻ���ûػ���ַ�ʹ򿪱����ļ�������BingAI-Client�ͻ��ˡ������ѡ��򿪱����ļ�����ķ���ʹ��BingAI-Clint�ͻ��ˣ���Ҫ��ip�����/webui��

��������ˣ�������Run�ļ����µ�`Update Libs.bat`������һ�Ρ�

ѯ�����Ƿ񿪷Ÿ���������󣬳��򻹻�ѯ���㲿�����Ķ˿ڡ�����������д����֤�����ĳ����ͻ���ɡ��������д80��Ĭ�϶˿ڣ�����ʹ�ô򿪱����ļ�����ķ�������ʱ����Ҫ��ip��������Ӷ˿ںţ�ip/���� + :�˿ںţ���

�������ͳɹ��ز����ڱ��ص�New Bing������������static�µ�"index.html"������������з���`127.0.0.1:�˿ں�/webui`�Ϳ��Կ�ʼʹ�øÿͻ����ˣ�

�ǵ���ʹ�ÿͻ��˵�ȫ�����в�Ҫ�ر��նˡ�BingServer������ʮ���ȶ�������ġ�

��������������󣬿��Է���[BingAI-Client���߰�](https://xbzstudio.github.io/BingAI-Client/) �����Ǽ������Github Pages�ϵĿͻ��˵�Ĭ�����ò��ܱ��������ģ����һ�����Ҫ���Լ����з���˳�����������ʹ���Լ���Ĭ�����ã������ñ�ķ���������New Bing����Ӧ�����Խ�BingAI-Client������ķ������ϣ�ʹ���ڱ���Ĭ�������н�HOST��Ϊ��Ҫ���ӵ��ķ���������ip+�˿ڣ�Ȼ��򿪱���index.html�ļ�������������ķ�������New Bing�Ի������Ҳ����ڱ��ؿ���BingServer.py���������������ɣ�����ʹ���Լ���Ĭ�����á����������վ�����Լ���Ĭ��������New Bing�Ի�����������ķ����������н�Ĭ����������Ϊ����Ҫ�ģ�Ȼ��ʹ����ķ�������`����ip/����+�˿�/webui`������Ķ��ư�����BingAI-Client��Ҳ�ǲ����ڱ��ؿ���BingServer.py���������������ɣ���

# �ֶ�����

## 1����װ������BingAI-Client

����ȷ�����и߰汾��Python���Ƽ�3.10�������ﲻ����׸����

�������ر���Ŀ��ZIPѹ��������ѹ��

Ȼ��������а�װ���[Cookie Editor](https://microsoftedge.microsoft.com/addons/detail/cookie-editor/ajfboaconbpkglpfanbmlfgojgndmhmc)��

��װ��ɺ󣬴����VPN������[Microsoft New Bing](https://bing.com/new)�������New Bing����Ľ��档Ȼ��㿪Cookie Editor������ͼƬ�еİ�ť��

![image](https://user-images.githubusercontent.com/119436353/235375933-d7e81988-fc6b-423b-841f-98575d310e32.png)

Ȼ��Ϳ����ˡ�����֮�󣬴���Ŀ�ļ��У��򿪸�Ŀ¼�µ�`cookie.json`������ctrl+v�ѸղŸ��Ƶ��Ķ��������ȥ�������ļ���Ȼ���˳���

���ļ���Դ����������Ŀ�ļ��У�Ȼ���Ҽ��ļ���Դ�������հ׵ĵط�����������ն���򿪡���Ȼ����Power Shell��������������س���
```
pip install -r requirements.txt -i http://pypi.douban.com/simple --trusted-host pypi.douban.com
```

���û�С����ն���򿪡����밴��`win + r`��ϼ����������д��ڣ����ı���������cmd���س����ͻᵯ���նˡ�Ȼ�����ն���������������س���

```
cd /d �����Ŀ�ļ��еľ���·������C:\Users\33664\OneDrive\XBZ-BingClient��
pip install -r requirements.txt -i http://pypi.douban.com/simple --trusted-host pypi.douban.com
```

���̿��ܻ��е㳤����������ȫ����װ��Ϻ�����Ŀ�ļ���Ŀ¼�д��նˣ�Ȼ���������� `python ./BingServer.py` �����û�б����Ǿ�˵���ɹ��ˡ�

��������뽫EdgeGPT������0.4.4�汾���°汾ʮ�ֲ��ȶ�����

```
pip install EdgeGPT==0.4.4
```

�������������ѯ�����Ƿ��������������ӣ������Ÿ��������ʹ��New Bing�������ѡ��true����Ϳ���ʹ����Ĺ���ip������ip���ػ���ַ�ʹ򿪱����ļ�������BingAI-Client�ͻ��ˣ����ѡ��false����ֻ���ûػ���ַ�ʹ򿪱����ļ�������BingAI-Client�ͻ��ˡ������ѡ��򿪱����ļ�����ķ���ʹ��BingAI-Clint�ͻ��ˣ���Ҫ��ip�����/webui��

ѯ�����Ƿ񿪷Ÿ���������󣬳��򻹻�ѯ���㲿�����Ķ˿ڡ�����������д����֤�����ĳ����ͻ���ɡ��������д80��Ĭ�϶˿ڣ�����ʹ�ô򿪱����ļ�����ķ�������ʱ����Ҫ��ip��������Ӷ˿ںţ�ip/���� + :�˿ںţ���

�������ͳɹ��ز����ڱ��ص�New Bing������������static�µ�"index.html"������������з���`127.0.0.1:�˿ں�/webui`�Ϳ��Կ�ʼʹ�øÿͻ����ˣ�

�ǵ���ʹ�ÿͻ��˵�ȫ�����в�Ҫ�ر��նˡ�BingServer������ʮ���ȶ�������ġ�

��������������󣬿��Է���[BingAI-Client���߰�](https://xbzstudio.github.io/BingAI-Client/) �����Ǽ������Github Pages�ϵĿͻ��˵�Ĭ�����ò��ܱ��������ģ����һ�����Ҫ���Լ����з���˳�����������ʹ���Լ���Ĭ�����ã������ñ�ķ���������New Bing����Ӧ�����Խ�BingAI-Client������ķ������ϣ�ʹ���ڱ���Ĭ�������н�HOST��Ϊ��Ҫ���ӵ��ķ���������ip+�˿ڣ�Ȼ��򿪱���index.html�ļ�������������ķ�������New Bing�Ի������Ҳ����ڱ��ؿ���BingServer.py���������������ɣ�����ʹ���Լ���Ĭ�����á����������վ�����Լ���Ĭ��������New Bing�Ի�����������ķ����������н�Ĭ����������Ϊ����Ҫ�ģ�Ȼ��ʹ����ķ�������`����ip/����+�˿�/webui`������Ķ��ư�����BingAI-Client��Ҳ�ǲ����ڱ��ؿ���BingServer.py���������������ɣ���

</details>

# ����New Bing

## Ĭ���������ø���

����./static/src/js�ļ��к󣬾Ϳ��Կ���һ����Ϊ��setting.js�����ļ���������ļ������洢����һ�δ��룬Ĭ����������

```javascript
var setting = {

    HOST:'127.0.0.1', //��Ҫ���ӵ��ķ�����IP�����������BingAI�������˿ڲ�Ϊ80�����ں������":�˿�ֵ"��Ĭ��Ϊ127.0.0.1����Ϊ���ʱ��ط�������
    autoTranslate:true, //�Ƿ�Ĭ�������Զ����룬trueΪ�ǣ�falseΪ��
    tokenToServer:true, //�Ƿ�Ĭ�����������Ի���trueΪ�ǣ�falseΪ��
    autoScroll:true, //�Ƿ���Bing�ظ��ʹ���Զ�������ҳ��ײ���trueΪ�ǣ�falseΪ��
    chatMoreTimes:true, //�Ƿ��Զ�ͻ��20���Ի����ƣ�trueΪ�ǣ�falseΪ��
    HTTPSMODE:false, //�Ƿ���HTTPSģʽ��trueΪ�ǣ�falseΪ����������������Э�����Ϊhttps��wss��
    chatStyle:"creative", //��Bing AI����ʱѡ�õ�������balanced����ƽ�⣬creative����������precise����ȷ��
    tips:"", //���µ����⿪ʼʱ�ĵ�һ���Ի�ǰ�������ʾ��null�Ϳյ�Ӣ��˫���ţ�""����ʾû�С�
    fontColor:"white", //���Bing AI����Ϣ���е���Ϣ������ɫ
    nameColor:"#dadada", //���Bing AI��ʾ���ֵ���ɫ
    backgroundUrl:"./src/images/Background.jpg", //����ͼƬ��url��ַ��Ĭ��Ϊ��Ŀ�ļ��е�Background.jpg
    saveChatTimes:20 //��󱣴������¼����
    
};
```

��������ֻҪ������δ��������ע�����������ü��ɸ������Ĭ�����á�
�ڸ������Ĭ�����ú󣬴򿪱��ؿͻ���ʱ������������û����ΪĬ�������е���������������Ĭ�������б�ʾ����Ҫ��chatStyle����Ϊ"balanced"����ô�ڴ򿪱��ؿͻ���ʱ�����������е����������ý����Զ�����Ϊbalanced��


# ����

### ͷ�����

����./static/src/images�ļ��У�����������ͼƬ��һ����`User.png`��һ����`Bing.png`���������Ҫ�������Լ���New Bing��ͷ��Ļ�����������ļ����м�������Ҫ������ͼƬ��������������Ϊ"User.png"��"Bing.png"��

## һЩ���ѽ��

���ȣ��ڳ��ִ���ʱ�����һʱ�䷴Ӧ��

```

����������⡱��ť��

������У��������⡣����Run�ļ����µ�`Update Libs.bat`�Ը��¿⡣

�ٲ��У������ſ���VPN��

���ǲ��У��͸���һ���Լ���Cookie��

���������з�������Ч����鿴���µ����ѽ�𡣻����޷�������⣬����ѯ���ߡ�

```

### python�����Ҳ����ļ�

������õ���1.5�����µİ汾������������1.6���������⡣

### python������һ�ַ���Ȩ�޲�����ķ�ʽ���� һ�������׽��ֵĳ��ԡ�

������˿ڵ�ʱ�򣬲�Ҫ��ԭ���Ķ˿ڣ�����������80������������ͰѶ˿ڻ���70����90�����У���Ȼ���index.html֮����
�����á���ť������ӵ��ķ������ĳ�127.0.0.1:�˿ںš��ǵò�Ҫ©��Ӣ��ð�š�������Ѷ˿�����Ϊ70���͸ĳ�127.0.0.1:70��

���ʹ��ip��ַ���������ʣ�����Ҫ��ӡ�:�˿ڡ�������192.168.56.36:70 �� 127.0.0.1:70��

### ��װ������ʱ����pip����������ִ�е�...

������������ԭ������û�н�Python���뻷������������û�а�װPython������ȷ���㰲װ��Python�ĸ߰汾�������װ�ˣ��Ǿ���û�ӻ���������

��򵥵ķ������Ȱ�Pythonж���ˣ�Ȼ���ð�װ�����°�װ���ڰ�װ�Ĺ����У�ע��Ҫ��ѡ��Add Python 3.xx to path����ѡ�������װ��֮����
û��ʹ��pip��

### һֱLoading for New Bing

��������ĵȴ�����Ϊ���ܻ�ȽϾã���������ǲ����֣��п�������Ķ˿���д�����������BingServer.py����ʱ���˷�80�Ķ˿ڣ���������ҳ������ã������ӵ������������ø���Ϊ��127.0.0.1:�˿ڡ���Ҳ�����������ص�1.5.1��1.5�汾���ϴ���Githubʱȱ����Щʲô�����ѷ���1.6�汾��
���������������á�

### Python����KeyError��

��������¾���Bing����ظ����ˡ�Ҳ����ǿ�ƽ����˶Ի�������ǹ���messgae��KeyError��������ǣ����Խ�һ��Ѱ�������

### ����ͼ��ʱ����Caused by NewConnectionError

����ͼ������Ҫ����VPN��ſ���ʹ�á�

# ʹ�÷�����

���ı������������⣨���Ի��У������¡����͡���ť��`Ctrl + Enter`��ݼ�������Ϣ��New Bing��

����뿪���µĻ��⣬���԰��¡������⡰������������󣬻��Զ�Ҫ��New Bing���֮ǰ�������¼�������������죨Ŀ���Ǵﵽ����������������Ч�����������Ҫ�������¿�ʼ�Ի����������ｫ�������ѡ��رա�

�������ð�ť���кܶ๦�ܿ��ء�������Լ��������ѡ�����ã����Ӱ�쵽����Bing�ĵ����졣

���ı����У�����`/create images `�����ǣ�images��߻��и��ո񣩣����Լ���ͼƬ���ɹ��ܡ��ڸղŵ�ָ���߸�������Ҫ���ɵ����ݣ��硱/create images a little cat eating fish"��Ȼ���͸�New Bing���Ե�һ�ἴ��
�õ�New Bing���ɵ�ͼƬ�������������Ҫ����VPN�ſ���ʹ�ã���


# ��β

## ��л��

[Bing-Chat](https://github.com/XiaoXinYo/Bing-Chat)�Ŀ�����[XiaoXinYo](https://github.com/XiaoXinYo)  
����Ŀ��[BingServer.py](https://github.com/xbzstudio/BingAI-Client/blob/main/BingServer.py)�����������ģ�  
����Ȼ����Ҳ�ڵ�����������Щ���ܣ���

[InterestingDarkness](https://github.com/InterestingDarkness)ΪBingAI-Client�������л�Sydneyģʽ�Ĺ��� ��ʮ�ָ�л��

[Nothingness-Void](https://github.com/Nothingness-Void)ΪBingAI-Client�����requirements.txt��

[Viopsa233](https://github.com/viopsa233)ΪBingAI-Client�������Ƶ�̳�,�����run.bat�ļ����ɰ棩��

[fyang93](https://github.com/fyang93)ΪBingAI-Client�����Dockerfile��

[liukaixiang817](https://github.com/liukaixiang817)ΪBingAI-Client������BingServer.py�Ĵ���
