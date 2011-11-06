.. Plone Team Docs documentation master file, created by
   sphinx-quickstart on Sun Nov  6 18:29:11 2011.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Plone Team Docs's documentation!
===========================================

Aquest és un experiment per veure que tal se'ns dona documentar en reStructuredText. Anteriorment, ens ha costat molt crear una base de dades de coneixement compartit, preferint altres formes més personals de documentació.

Veiam que tal va!

Per ara comencem amb tres categories:

    * Procediments i bones pràctiques d'equip
    * Tips and Tricks
    * How To

Per cada nova entrada cal crear un fitxer .rst al directori corresponent. Després pujar els canvis a GitHub.

.. note::
    
    En aquesta `web`_ teniu el manual de referència de reStructuredText. Recordeu que podeu fer servir tot el que aporta `Sphinx`_.

.. _web: http://sphinx.pocoo.org/rest.html
.. _Sphinx: http://sphinx.pocoo.org/


Procediments i bones pràctiques d'equip:
========================================

Documents que contenen recomanacions i bones pràctiques que hem d'observar sempre que poguem. Són importants ja que si tots mirem d'aplicar-los revertirà en un augment de qualitat en el nostre treball diari.

.. toctree::
   :maxdepth: 2
   :glob:

   procediments/*


Tips and Tricks
===============

Accions que proporcionen *Big Wins* (TM) al nostre treball diari. Aquelles que un cop les apliquem, se'ns queda un somriure a la boca i internament pensem (Muahahaha)

.. toctree::
   :maxdepth: 2
   :glob:

   tips&tricks/*


How To
======

Documents que expliquen un aspecte o funcionalitat concreta.

.. toctree::
   :maxdepth: 2
   :glob:

   howto/*


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

