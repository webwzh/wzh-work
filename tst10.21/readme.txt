1.�������ַ������ַ�������ķ������һ���ַ�,��ʾ��ҳ��idΪh1��Ԫ����
��:     var p = document.getElementById('h1')
    var str = "�ַ�1";
    p.innerHTML=str.concat('�ַ�2')

2.һ���������87��,����ƹ���д��87w,���Զ����ɴ洢870000�ķ���,��ʾ��ҳ��idΪh2��Ԫ����
��:var p = document.getElementById('h2')
 var num = '870000';
 p.innerHTML= num;

3.һ������79387.348�Ĺ��̿�,������λС������,��ʾ��ҳ��idΪh3��Ԫ����
��: var p = document.getElementById('h3')
 var num = 79387.348;
 p.innerHTML= num.toFixed(2);

4.һ��ͼƬ��һ�����·��img/head/icon/1.jpg,��ֻ��Ҫ�õ������ļ���Ŀ¼����ʾ��ҳ��idΪh4��Ԫ����
��:var p = document.getElementById('h4');
          var img = document.getElementById('img');
          p.innerHTML=img.src;

5.�û�������֤��,���۴�Сд���붼����ȷ�ķ���,��ʾ��ҳ��idΪh1��Ԫ����,��ʾ��ҳ��idΪh5��Ԫ����
��:
var inpt = document.getElementById('inpt');
       toupperCase = inpt.value;