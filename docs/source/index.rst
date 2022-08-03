DepthAI Hardware Documentation
==============================

Each device's documentation includes an overview, getting started guide, images and project files, such as datasheets, altium design files, 3D models and
mechanical models.

Device name guide
*****************

.. image:: /_static/images/device-comparison/device-naming.png
     :target: pages/guides/device-comparison.html

More information can be found at :ref:`Device comparison` guide.

USB Designs
***********

These are our most popular devices. Brought to market by a successful `KickStarter <https://www.kickstarter.com/projects/opencv/opencv-ai-kit>`__ campaign,
OAK-D and OAK-1 have been solving real-world problems for more than 2 years. **USB connection** is great for development - it's easy to use and allows up to
10Gbps throughput.

.. list-table::
   :header-rows: 1

   * - OAK-D S2
     - OAK-D W
     - OAK-D Pro
     - OAK-D Pro W
   * - .. image:: /_static/images/thumbnails/DM9098s2.png
          :target: pages/DM9098s2.html
     - .. image:: /_static/images/thumbnails/oak-d-w.png
          :target: pages/DM9098w.html
     - .. image:: /_static/images/thumbnails/DM9098pro.png
          :target: pages/DM9098pro.html
     - .. image:: /_static/images/thumbnails/oak-d-pro-w.png
          :target: pages/DM9098prow.html
   * - :ref:`Learn more <dm9098s2>`
     - :ref:`Learn more <dm9098w>`
     - :ref:`Learn more <dm9098pro>`
     - :ref:`Learn more <dm9098prow>`

.. list-table::
   :header-rows: 1

   * - OAK-D Lite
     - OAK-1 Lite
     - OAK-1
     - OAK-D
   * - .. image:: /_static/images/thumbnails/DM9095.png
          :target: pages/DM9095.html
     - .. image:: /_static/images/thumbnails/oak-1-lite.png
          :target: pages/NG9096.html
     - .. image:: /_static/images/thumbnails/OAK-1.png
          :target: pages/BW1093.html
     - .. image:: /_static/images/thumbnails/BW1098OAK.png
          :target: pages/BW1098OAK.html
   * - :ref:`Learn more <dm9095>`
     - :ref:`Learn more <ng9096>`
     - :ref:`Learn more <bw1093>`
     - :ref:`Learn more <bw1098oak>`

PoE Designs
***********

PoE devices are similar to USB devices, but instead of USB, they have **PoE connectivity** and also feature **on-board flash**, so you can run pipelines
in `standalone mode <https://docs.luxonis.com/projects/api/en/latest/tutorials/standalone_mode/>`__.

.. list-table::
   :header-rows: 1

   * - OAK-D-POE
     - OAK-D S2 PoE
     - OAK-D Pro PoE
   * - .. image:: /_static/images/thumbnails/oak-d-poe.png
          :target: pages/SJ2088POE.html
     - .. image:: /_static/images/thumbnails/s2-poe.png
          :target: pages/NG9097s2.html
     - .. image:: /_static/images/thumbnails/pro-poe.png
          :target: pages/NG9097pro.html
   * - :ref:`Learn more <sj2088poe>`
     - :ref:`Learn more <ng9097s2>`
     - :ref:`Learn more <ng9097pro>`

.. list-table::
   :header-rows: 1

   * - OAK-1-PoE
     - OAK-D W PoE
     - OAK-D Pro W PoE
   * - .. image:: /_static/images/thumbnails/oak-1-poe.png
          :target: pages/SJ2096POE.html
     - .. image:: /_static/images/thumbnails/oak-d-w-poe.png
          :target: pages/NG9097w.html
     - .. image:: /_static/images/thumbnails/oak-d-pro-w-poe.png
          :target: pages/NG9097prow.html
   * - :ref:`Learn more <sj2096>`
     - :ref:`Learn more <ng9097w>`
     - :ref:`Learn more <ng9097prow>`

Modular Cameras Designs
***********************

Great for prototyping flexibility. Since **cameras are modular**, you can place them at **various stereo baselines**. This flexibility comes with a
trade - you have to figure out how/where you will mount them, and then once mounted, do a `stereo calibration <https://docs.luxonis.com/en/latest/pages/calibration/>`__.
This is not a TON of work, but keep this in mind, that it’s not ‘plug and play’ like other options - it’s more for applications that require custom mounting,
custom baseline, or custom orientation of the cameras.

.. list-table::
   :header-rows: 1

   * - OAK-FFC-3P
     - OAK-FFC-4P
     - OAK-FFC-6P
   * - .. image:: /_static/images/thumbnails/DM1090FFC_new.png
          :target: pages/DM1090.html
     - .. image:: /_static/images/thumbnails/FFC-4P.png
          :target: pages/DD2090.html
     - .. image:: /_static/images/thumbnails/FFC-6P.png
          :target: pages/DM3390.html
   * - :ref:`Learn more <dm1090ffc>`
     - :ref:`Learn more <dd2090ffc>`
     - :ref:`Learn more <dm3390>`

.. list-table::
   :header-rows: 1

   * - OAK-FFC-IMX378
     - OAK-FFC-OV9282
     - OAK-FFC-ToF-VGA
   * - .. image:: /_static/images/thumbnails/BG0249.png
          :target: pages/BG0249.html
     - .. image:: /_static/images/thumbnails/BG0250TG.png
          :target: pages/BG0250TG.html
     - .. image:: /_static/images/thumbnails/DM0256.png
          :target: pages/DM0256.html
   * - :ref:`Learn more <bg0249>`
     - :ref:`Learn more <bg0250tg>`
     - :ref:`Learn more <dm0256>`


All in One Dev. Kits Designs
****************************

These devices are like combining a **Raspberry Pi with an OAK-D** in a compact solution.

.. list-table::
   :widths: 1 1 1
   :header-rows: 1

   * - OAK-D-CM3
     - OAK-D-CM4
     - OAK-D CM4 PoE
   * - .. image:: /_static/images/thumbnails/BW1097.png
          :target: pages/BW1097.html
     - .. image:: /_static/images/thumbnails/DM1097.png
          :target: pages/DM1097.html
     - .. image:: /_static/images/thumbnails/cm4-poe.png
          :target: pages/DM2097.html
   * - :ref:`Learn more <bw1097>`
     - :ref:`Learn more <dm1097>`
     - :ref:`Learn more <dm2097>`


System on Module Designs
************************

SoM is perfect :ref:`for integrating <Integrating DepthAI into products>` the power of DepthAI into your own products - or to customize one of our
open-source hardware design as you see fit.

.. list-table::
   :header-rows: 1

   * - OAK-SoM     
     - OAK-SoM-Pro
     - OAK-SoM-Max
   * - .. image:: /_static/images/thumbnails/BW1099.png
          :target: pages/BW1099.html
     - .. image:: /_static/images/thumbnails/oak-som-pro.png
          :target: pages/BW2099.html
     - .. image:: /_static/images/thumbnails/dm3399.png
          :target: pages/DM3399.html
   * - :ref:`Learn more <bw1099>`
     - :ref:`Learn more <bw2099>`
     - :ref:`Learn more <dm3399>`

Miscellaneous Designs
*********************

.. list-table::
   :header-rows: 1

   * - Y-adapter
     - FFC Camera modules
     - PoE Board
   * - .. image:: /_static/images/thumbnails/Y-Adapter.png
          :target: pages/DM6010.html
     - .. image:: /_static/images/thumbnails/arducam_2.png
          :target: pages/arducam.html
     - .. image:: /_static/images/thumbnails/BW2098POE.png
          :target: pages/BW2098POE.html
   * - :ref:`Learn more <Y-adapter>`
     - :ref:`Learn more <arducam>`
     - :ref:`Learn more <bw2096poe>`


**Other models** can be found :ref:`here <Other models>`.

.. include::  /pages/includes/footer-long.rst


.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: Guides

   pages/guides/device-comparison.rst
   pages/guides/realsense_comparison.rst
   pages/guides/getting-started-with-poe.rst
   pages/guides/integrating_depthai_into_products.rst
   OAK Design Guide <pages/guides/design_guide.rst>
   pages/guides/powering_poe_devices.rst
   pages/guides/sync_frames.rst
   pages/guides/raspberrypi.rst
   pages/guides/af_ff.rst

.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: Articles

   pages/articles/waterproof.rst
   pages/articles/operative_temperature_range.rst
   pages/articles/device_availability_and_eol.rst
   pages/articles/supported_sensors.rst

.. toctree::
     :caption: Series
     :hidden:

     pages/articles/oak-s2.rst
     pages/articles/oak-s3.rst

.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: USB Designs

   pages/DM9095.rst
   pages/DM9098s2.rst
   pages/DM9098w.rst
   pages/DM9098pro.rst
   pages/DM9098prow.rst
   pages/NG9096.rst
   pages/BW1093.rst
   pages/BW1098OAK.rst

.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: PoE Designs

   pages/SJ2096POE.rst
   pages/SJ2088POE.rst
   pages/NG9097s2.rst
   pages/NG9097w.rst
   pages/NG9097pro.rst
   pages/NG9097prow.rst

.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: Modular Cameras

   pages/DM3390.rst
   pages/DD2090.rst
   pages/DM1090.rst
   pages/BG0250TG.rst
   pages/BG0249.rst
   pages/DM0255.rst
   pages/arducam.rst

.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: All In One Dev. Kits

   pages/BW1097.rst
   pages/DM1097.rst
   pages/DM2097.rst

.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: System on Module

   pages/BW1099.rst
   pages/BW2099.rst
   pages/DM2399.rst
   pages/DM3399.rst

.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: Miscellaneous Designs

   pages/DM6010.rst
   pages/BW0253.rst
   pages/BW1094.rst
   pages/BW2098POE.rst