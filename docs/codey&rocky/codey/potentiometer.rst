:mod:`potentiometer` --- 板载电位器旋钮
=============================================

.. module:: potentiometer
    :synopsis: 板载电位器旋钮

``potentiometer`` 模块的主要功能与函数

功能相关函数
----------------------

.. function:: get_value()

   获得电位器旋钮的当前数值。 数值范围 ``0 ~ 100``。

程序示例：
----------------------

.. code-block:: python

  import codey
  
  while True:
      codey.display.show(codey.potentiometer.get_value())