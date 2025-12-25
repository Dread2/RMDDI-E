Realtek® L8200A Gigabit Ethernet Controller (GbE)
================================================

Overview
--------
The **L8200A** is an ASUS-exclusive Gigabit Ethernet controller developed by
**Realtek Semiconductor Corp.**. It is commonly found on ASUS TUF series
motherboards and is based on a customized variant of the Realtek
RTL8111/8168/8411 PCIe Ethernet family, paired with an ASUS-specific PHY
configuration.

.. container:: figures-side-by-side

   .. image:: ../../../../../images/asus/l8200a/asus-tuf-gaming-x570-plus-wifi.jpeg
      :alt: ASUS TUF X570-Plus WiFi motherboard
      :align: left
      :width: 48%

   .. image:: ../../../../../images/asus/l8200a/l8200a.png
      :alt: Realtek L8200A PHY in QFN-32 package
      :align: right
      :width: 48%

Package and Physical Characteristics
------------------------------------
- **Package Type:** QFN-32 (Quad Flat No-Lead, 32 pins)
- **Mounting:** Surface-mounted directly on the motherboard
- **Thermal:** Central exposed pad for heat dissipation
- **Form Factor:** Compact, suitable for space-constrained motherboard layouts

Hardware Identifiers
--------------------

.. list-table::
   :widths: 20 30 50
   :header-rows: 1

   * - Field
     - Value
     - Description
   * - Vendor ID
     - ``0x10EC``
     - Realtek Semiconductor Corp.
   * - Device ID
     - ``0x8168``
     - RTL8168 / RTL8111 / RTL8411 PCIe GbE family
   * - Subsystem ID
     - ``0x87C31043``
     - ASUS TUF-series customized implementation (Revision 26)
   * - Revision
     - ``26``
     - ASUS-specific silicon / PHY configuration revision

Supported Motherboards
----------------------

- ASUS TUF Gaming X570-Plus
- ASUS TUF Gaming X570-Plus (Wi-Fi)
- ASUS TUF Gaming A520M-Plus
