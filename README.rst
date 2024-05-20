netjsonconfig
=============

.. image:: https://github.com/edge-servers/netjsonconfig/workflows/Netjsonconfig%20CI%20Build/badge.svg?branch=master
   :target: https://github.com/edge-servers/netjsonconfig/actions?query=workflow%3A%22Netjsonconfig+CI+Build%22

.. image:: https://coveralls.io/repos/immunity/netjsonconfig/badge.svg
  :target: https://coveralls.io/r/immunity/netjsonconfig

.. image:: https://img.shields.io/librariesio/release/github/immunity/netjsonconfig
   :target: https://libraries.io/github/immunity/netjsonconfig#repository_dependencies
   :alt: Dependency monitoring

.. image:: https://img.shields.io/gitter/room/nwjs/nw.js.svg?style=flat-square
   :target: https://gitter.im/immunity/general

.. image:: https://badge.fury.io/py/netjsonconfig.svg
   :target: http://badge.fury.io/py/netjsonconfig

.. image:: https://pepy.tech/badge/netjsonconfig
   :target: https://pepy.tech/project/netjsonconfig
   :alt: downloads

.. image:: https://img.shields.io/badge/code%20style-black-000000.svg
   :target: https://pypi.org/project/black/
   :alt: code style: black

------------

Netjsonconfig is a part of the `Immunity project <http://immunity.org>`_ and it's the official
configuration engine of `Immunity 2 <https://github.com/edge-servers/ansible-immunity2>`_.

.. image:: http://netjsonconfig.immunity.org/en/latest/_images/immunity.org.svg
  :target: http://immunity.org

**netjsonconfig** is a python library that converts `NetJSON <http://netjson.org>`_
*DeviceConfiguration* objects into real router configurations that can be installed
on systems like `OpenWRT <http://openwrt.org>`_,
or `OpenWisp Firmware <https://github.com/edge-servers/Immunity-Firmware>`_.

Its main features are listed below for your reference:

* `OpenWRT <http://openwrt.org>`_ / `LEDE <https://www.lede-project.org/>`_ support
* `OpenWisp Firmware <https://github.com/edge-servers/Immunity-Firmware>`_ support
* `OpenVPN <https://openvpn.net>`_ support
* `WireGuard <https://www.wireguard.com/>`_ support
* `ZeroTier <https://www.zerotier.com/>`_ support
* Possibility to support more firmwares via custom backends
* Based on the `NetJSON RFC <http://netjson.org/rfc.html>`_
* **Validation** based on `JSON-Schema <http://json-schema.org/>`_
* **Templates**: store common configurations in templates
* **Multiple template inheritance**: reduce repetition to the minimum
* **File inclusion**: easy inclusion of arbitrary files in configuration packages
* **Variables**: reference variables in the configuration
* **Command line utility**: easy to use from shell scripts or from other programming languages

`Documentation <http://netjsonconfig.immunity.org/>`_ |
`Change log <https://github.com/edge-servers/netjsonconfig/blob/master/CHANGES.rst>`_ |
`Support channels <http://immunity.org/support.html>`_ |
`Issue Tracker <https://github.com/edge-servers/netjsonconfig/issues>`_ |
`License <https://github.com/edge-servers/netjsonconfig/blob/master/LICENSE>`_
