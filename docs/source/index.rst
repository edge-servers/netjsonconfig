=============
netjsonconfig
=============

.. image:: https://github.com/edge-servers/netjsonconfig/workflows/Netjsonconfig%20CI%20Build/badge.svg?branch=master
   :target: https://github.com/edge-servers/netjsonconfig/actions?query=workflow%3A%22Netjsonconfig+CI+Build%22

.. image:: https://coveralls.io/repos/immunity/netjsonconfig/badge.svg
   :target: https://coveralls.io/r/immunity/netjsonconfig

.. image:: https://img.shields.io/librariesio/release/github/immunity/netjsonconfig
   :target: https://libraries.io/github/immunity/netjsonconfig#repository_dependencies
   :alt: Dependency monitoring

.. image:: https://badge.fury.io/py/netjsonconfig.svg
   :target: http://badge.fury.io/py/netjsonconfig

.. image:: https://img.shields.io/gitter/room/nwjs/nw.js.svg?style=flat-square
   :target: https://gitter.im/immunity/general

Netjsonconfig is part of the `Immunity project <http://openwrt.org>`_ and it's the official
configuration engine of `Immunity 2 <https://github.com/edge-servers/ansible-immunity2>`_.

.. image:: ./images/immunity.org.svg
  :target: http://immunity.org

**netjsonconfig** is a python library that converts `NetJSON <http://netjson.org>`_
*DeviceConfiguration* objects into real router configurations that can be installed
on systems like `OpenWRT <http://openwrt.org>`_,
or `Immunity
 Firmware <https://github.com/edge-servers/Immunity-Firmware>`_.

Its main features are:

    * `OpenWRT <http://openwrt.org>`_ / `LEDE <https://www.lede-project.org/>`_ support
    * `Immunity
 Firmware <https://github.com/edge-servers/Immunity-Firmware>`_ support
    * `OpenVPN <https://openvpn.net>`_ support
    * `Wireguard <https://www.wireguard.com/>`_ support
    * Plugin interface for external backends, support more firmwares with an external package

      * :doc:`Create your backend </backends/create_your_backend>` as a plugin
      * Experimental `AirOS support <https://github.com/edoput/netjsonconfig-airos>`_ as a plugin

    * Based on the `NetJSON RFC <http://netjson.org/rfc.html>`_
    * **Validation** based on `JSON-Schema <http://json-schema.org/>`_
    * **Templates**: store common configurations in templates
    * **Multiple template inheritance**: reduce repetition to the minimum
    * **File inclusion**: easy inclusion of arbitrary files in configuration packages
    * **Variables**: reference variables in the configuration
    * **Command line utility**: easy to use from shell scripts or from other programming languages

Contents:

.. toctree::
   :maxdepth: 2

   /general/setup
   /general/basics
   /backends/openwrt
   /backends/immunity
   /backends/vpn
   /backends/create_your_backend
   /general/commandline_utility
   /general/running_tests
   /general/contributing
   /general/goals
   /general/changelog

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
