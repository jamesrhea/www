:template: 2017/video-details.html

Hi, my name is README!
======================

{% set talk = conferences[2017]['eu']['speakers'][16] %}
{% set output %}
{% include conf_py_root + '/_templates/video-details-body.html' %}
{% endset %}
.. raw:: html

    {{ output|indent(4) }}
