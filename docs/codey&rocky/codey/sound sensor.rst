:mod:`sound_sensor` --- 板载音量传感器
=============================================

.. module:: sound_sensor
    :synopsis: 板载音量传感器

``sound_sensor`` 模块的主要功能与函数

功能相关函数
----------------------

.. function:: get_loudness()

   获得音量传感器检测的声音强度, 返回值是音量的大小。 数值范围 ``0 ~ 100``。

程序示例：
------------

.. code-block:: python

  import codey
  
  while True:
      codey.display.show(codey.sound_sensor.get_loudness())