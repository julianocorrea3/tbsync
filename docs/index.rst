About this Documentation
========================

This document tries to cover all aspects of how to create a provider add-on for TbSync to extends its sync capabilities. 

.. note::
  All TbSync provider add-ons are currently designed as *bootrapped extensions*, for which support is probably going to be dropped from Thunderbird at some time. We are working on migrating the TbSync API into a WebExtension API, so - hopefully - all provider add-ons can be converted into future proof *WebExtensions* without much effort.

:doc:`introduction`
  This section gives a short introduction to TbSync and its provider concept.

:doc:`getting_started`
  As promised by the name, this section gets you started by explainig how to create your own basic provider add-on in just a couple of minutes and gives instructions to get it running in Thunderbird.

:doc:`implementing`
  Learn how to interact with TbSync.


.. toctree::
   :caption: Building a Provider Add-on
   :hidden:
   :maxdepth: 3
   
   introduction
   getting_started
   implementing

.. toctree::
   :caption: Additional Resources
   :hidden:
   :maxdepth: 3

   resources/classes
   resources/methods   
   resources/eventlog
    
