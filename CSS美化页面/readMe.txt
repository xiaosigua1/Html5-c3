css����ҳ��

���������һ�������У�����ĳ������͹�Գ�����ʹ��span��

1.������ʽ
   font-style:����ķ��   italic  normal
   font-weight:����Ĵ�ϸ   normal(Ĭ��400) bold(700)  bolder  ���900
   font-size:����Ĵ�С   10px  2em   rem  pc  pt
   font-family:��������ͣ��������ǵĿ��壬����,���塣��������

   font����� ��ϸ ��С ����
    ��һ���������Ե�ʱ����������˳���ܵߵ���

2.�ı���ʽ
       color:�ı���ɫ red  16������ɫ��  rgb   rgba
             rgb(red,green,blue)����ȡֵ 0-255
             rgba(red,green,blue,alpha)
             alpha��ȡֵ������0-1  0����ʾ  1������ʾ
  text-align:�ı�Ԫ�ص�ˮƽ���뷽ʽ
            center  left  right  justify(���˶���)
  line-height:�ı����и�!
       ����������ı��Ĵ�ֱ����line-height��ֵ�������height��ֵ
  text-indent:������������
                 p{
                  text-indent:2em; ����p��������2���ַ�
                   }
  text-decoration:�ı���װ��
           none:Ĭ��ֵ
      underline:�»���
       overline:�ϻ���
   line-through:ɾ����
    text-shadow:�ı���Ӱ

3.display  ����ʵ�� ��Ԫ�غ�����Ԫ�صĻ�����
   inline inline-block  block

4.������α��

   �ṹα��ѡ������
      div:nth-of-type()  :nth-child
   cssα����һ��������࣡ ��������������õ�cssѡ���������ã�

   cssα����﷨��
       ѡ����:α������
                     ����:����ֵ;
                     ��
  :link     ==> ��û�е�������ӵ���ʽ
  :visited  ==> ���֮�����ӵ���ʽ
  :hover    ==> �����ͣ�ڳ����ӵ���ʽ
  :active   ==> �����δ�ͷų����ӵ���ʽ

 love  hate
 ���ͬʱ��һ��ѡ�������ó�����α����ʽ����ô˳���Ǳ��벻��ģ�

5.�б���ʽ
  list-style-type   �б������ʽ
      none    �޷���
      disc    ʵ��Բ
      circle  ����Բ
      decimal ����  .....
  list-style-image  �б�ͼƬ  url
  list-style-position �б�����Ƿ�li������Ĭ����ul����
  list-style        �б���ʽ

���ͬʱ������type��image  ��ôimage�Ḳ��type������д�Ⱥ�˳��û��ϵ��

6.������ʽ
    background-color:����ɫ
    background-image:����ͼƬ
    background-position:����λ��
    background-repeat:�����ظ���ʽ
        repeat:Ĭ�Ϸ�ʽ ˮƽ�ʹ�ֱ��ƽ��
        no-repeat:��ƽ�̣�ֻ��һ��ͼƬ
        repeat-x:ˮƽƽ��
        repeat-y:��ֱƽ��

    background: ����ɫ ����ͼƬ ����λ��  ƽ�̷�ʽ
    ��Ȼû�й̶�˳�򣬵��������и�Ĭ�ϵ�д����

���������Ա���ͼƬ�Ĵ�С�������ã���ô��ʹ��background-size
background-size:contain;
           background-size������ͼƬ�ĳߴ�
            auto:Ĭ��ֵ��ʹ��ͼƬ�Ĵ�С
            cover:������ͼƬ���������������
            contain����ͼƬ�Զ��ķ���������С ��Ӧ���ӵĴ�С
            percentage��ʹ�ðٷֱ�  �ֶ���У��ͼƬ�ں����еĴ�С


7.��������
  linear-gradient:(����,color1,color2)
                to top :����
                red:��1����ɫ
                black:��2����ɫ
IE�������Trident�ںˣ���ǰ׺��-ms-
Chrome�������Webkit�ںˣ���ǰ׺��-webkit-
Safari�������Webkit�ںˣ���ǰ׺��-webkit-
Opera�������Blink�ںˣ���ǰ׺��-o-
Firefox�������Mozilla�ںˣ���ǰ׺��-moz-
