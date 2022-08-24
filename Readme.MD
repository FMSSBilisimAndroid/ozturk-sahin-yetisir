<h1 align="center"> Roll Dices 2X </h1>

--- 

2X Roll Dices FMSS Ödev 1 

---

<p align="center">
  <img width="30%" src="https://github.com/FMSSBilisimAndroid/ozturk-sahin-yetisir/blob/master/image/rolldicev2.gif" alt="gif image"/>
</p>

---


<h1>Namespace Nedir ?</h1>

<p>Namespace kavramı XML dillerinde çakışmayı engellemek amacıyla kullanılmaktadır. Kavramları tanımlarken namespace kullanmak eşiz terim yaratmaktadır.

Örnek olarak **www.google.com** eşşizdir ve namespace olarak adlandırılabilir.</p>
<p>Namespace kullanımı kod karmaşıklığını engeller. Kodun okunabilirliğini sağlar. </p>

<p> Namespace kullanımında prefix kullanılabilir. Prefix bir kısaltmadır. Bu kısaltmalar başta tanımlandıktan sonra, devam kodlarında büyük kolaylıklar sağlamaktadır. </p>

---

<h1> Namespace Kullanımı</h1>

Kütüphanelerde de namespace kullanımı kolaylık sağlamaktadır.
Örnek olarak yaptığım ödevde **"main/res/anim/rotate.xml"**
adında bir namespace kavramı kullanılmıştır. Buradaki bu kütüphane çağrımı görüntü kirliliğini azaltmakta ve kodun okunulabilirliğini arttırmaktadır.


```kotlin
val animation: Animation = AnimationUtils.loadAnimation(this,R.anim.rotate)
```
Son kısımdaki **"R.anim.rotate"** komutu sayesinde XML dosya içerisinde tanımlanmış verileri kısaca çağırmış bulunduk.
