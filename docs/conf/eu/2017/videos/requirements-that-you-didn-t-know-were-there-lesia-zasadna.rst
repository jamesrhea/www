:template: 2017/video-details.html

Requirements that you didn't know were there
============================================

{% set talk = conferences[2017]['eu']['speakers'][10] %}
{% set output %}
{% include conf_py_root + '/_templates/video-details-body.html' %}
{% endset %}
.. raw:: html

    {{ output|indent(4) }}
