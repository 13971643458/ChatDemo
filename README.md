# ChatDemo

##������ѡ��ʵ�ַ�ʽ��

![image](https://github.com/Maxi-Mao/ChatDemo/blob/master/ChatIMG/main.jpg)

##���ֱ���ʾ��ͼƬ��

![image](https://github.com/Maxi-Mao/ChatDemo/blob/master/ChatIMG/img1.png)

##ͼƬ����ʾ��ͼƬ��

![image](https://github.com/Maxi-Mao/ChatDemo/blob/master/ChatIMG/img2.png)

##��������ʾ����ͼ��

![image](https://github.com/Maxi-Mao/ChatDemo/blob/master/ChatIMG/voice.gif)

##ע��RecyclerView��ListViewʵ�ַ�ʽ��ͬ��Щ���ܲ�ͬ������ʹ�á�

�������߻��淽ʽ�����ԣ����������������־ֲ�����Ƶ���Ľ���ʹ��RecyclerView����

 ��RecyclerView�������ƣ�����bug֪ͨ�����޸���
##16/11/7���£�

* �Ż����������ȣ���Ҫ�Ż�GifTextView�ؼ�����RecyclerView����������ȣ���Ҫ�������ʱͼƬ�����ֱ������˸���⡣

##16/10/15���£�

* �����Ϣ���ݿ⣬���ڱ��������¼�� ���ݿ��õ���GreenDao�����ݷ�ҳ���ء�

��Ϊ�Ǹ�Demo������ListView��RecyclerView�õ�ͬһ�������ֻ�迴ʵ�ַ�ʽ���ɡ�

##16/10/10���£�

* ���ListView��ʵ�ַ�ʽ��PullToRefreshListView

PullToRefreshRecyclerViewΪRecyclerView��ʵ�ַ�ʽ�������л�ListView�����ChatActivity��PullToRefreshLayout�����޸ĺ�һЩ�����޸ġ�

ListView������:ChatListViewAdapter

RecyclerView������:ChatRecyclerAdapter

##16/9/30���£�

* ������ListView��ΪRecyclerView

* �������item����

* �޸���������̵������⣬����΢�š�

* �Ż����棬�����û�����

##���ܣ�
* ����Ŀ��һ��������棬��װ�˰������֡����顢ͼƬ��������Ϣ��
* ֧�־�̬���飬gif���飬���ֱ�����š�ͼ�Ļ���ʵ�ֲο���[Android����ʵ��ͼ�Ļ�ࣨ����gif��ʾ��](http://blog.csdn.net/omrapollo/article/details/50586902)
* ֧��ͼƬ���ͣ��ü�ͼƬ��״��֧��ͼƬ��������ͼ�ۿ���֧�ַŴ���С�ȡ�
* ����ͼƬ��С�ȱ������ţ���ѹ����ʾ��
* ֧���������ͣ���������δ��״̬��ʾ������¼��Ϊamr��ʽ�����ļ����������ͷ�΢�š�
* �������Ź��߿��Բο���һ����Ŀ��[android�������Ź��ߣ��Դ����棩](http://blog.csdn.net/omrapollo/article/details/78085730)
* ����¼��mp3��ʽ�ο���[Android¼��mp3��ʽ](http://blog.csdn.net/omrapollo/article/details/50470659)
* û��¼��Ȩ������ʾ�û���ʵ�ַ�ʽ�ο���[Android¼��Ȩ�ޱ����������](http://blog.csdn.net/omrapollo/article/details/51150280)
* ������ͼƬ֧������״̬�������С�����ʧ�ܺͷ��ͳɹ�������ʧ����ʾ��̾�ţ���
* ֧���������ظ��࣬�������ظ�������ViewDragHelper��ʵ�ַ�ʽ�ο���[Android����ˢ��](http://blog.csdn.net/omrapollo/article/details/49867345)
* ֧��ʱ����ʾ��Ĭ�ϴ���һ������ʾһ�Σ��������μ�ChatAdapter�ࡣ�ɸ��������޸ġ�

##��ϸ˵��

ListView:

![image](https://github.com/Maxi-Mao/ChatDemo/blob/master/ChatIMG/uml1.png)

RecyclerView:

![image](https://github.com/Maxi-Mao/ChatDemo/blob/master/ChatIMG/uml2.png)

###��Ҫ��
* ChatActivity:�������
* ChatListViewAdapter:ListView�������������
* ChatRecyclerAdapter:RecyclerView�������������
* ChatBean:�������ݶ���

###����
* ImageViewActivity:��ͼ�ۿ�����
* AudioRecordButton���Զ���¼���ؼ�
* BubbleImageView���Զ���ͼƬ�ü��ؼ�
* MediaManager���������ſؼ�
* GifTextView���Զ���ͼ�Ļ��ſؼ�
* pulltorefresh�����Զ����������ظ���ؼ�����֧���������ظ��ࣩ
* SlideInOutBottomItemAnimator:RecyclerView���item�������ϻ���

ͼƬ����ʹ��Glide��

Ϊ���Ż����ܣ������Ĺ�����gifΪ��̬��ʾ��

���ַ��Ͱ�ťΪ�����еĻس���

##��ǣ�

����ĿҲ�ǽ�֮ǰ������һЩ���������һ�£�ʱ��Ƚ϶̣���ҾͿ�һ�¾����ʵ�ַ�ʽ�ɣ������е��ң���ʱ��Ļ�������һ�¡�

## License

    Copyright 2016 maojiqing

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.