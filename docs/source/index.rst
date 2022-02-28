ESP32-CAM + micropython学习笔记
===================================

 |logo|
 |name|
 
.. |logo| image:: https://help.github.com/assets/images/site/favicon.ico
.. |name| replace:: opacity-black


micropython 概述
--------------

> micropython简称mpy，是python的片上版本，也算是一个嵌入式操作系统
>
> 其库名一般会在原来python的名字前加一个u以区别，比如pip->upip
>
> micropython运行仅占用11KB左右的内存
>
> **micropython 适合用来DIY**
>
> > micropython开发优点：交互性，刷入简单，第三方库+官方库齐全，大多数时候只用管上层逻辑就行了，底层硬件几乎是隐形的，可拓展性强，还能配合C语言二次开发固件。
>
> mpy的启动顺序：
> _boot.py【不可见】
> boot.py【由系统创建，可见，但不建议修改】
> main.py【由用户创建，开机自动运行的代码放这】

固件版本：micropython1.14

`固件下载地址 <https://micropython.org/download/>`_

`micropython1.14文档 <http://docs.micropython.org/en/v1.14/>`_



网页链接 `链接 <https://world.openfoodfacts.org/>`_
and offers a *simple* and *intuitive* API.

文档链接 :doc:`usage` section for further information, including
how to :ref:`installation` the project.

.. note::

   文档开发中

标题
--------

.. toctree::

   usage
   api
