.. _bootable-usb-windows:

Create a bootable USB drive on Windows
######################################

Follow these instructions to create a bootable |CLOSIA| USB drive.
Use an **8GB** or larger USB drive. Download either a live image, 
``clear-<version>-live.img.xz`` or an installer image, 
``clear-<version>-installer.img.xz``, from our `image`_ download page.

Instructions are also available for other operating systems:

* :ref:`bootable-usb-mac`
* :ref:`bootable-usb-linux`

.. include:: ../../guides/maintenance/image-types.rst
   :start-after: for different platforms and environments. 
   :end-before: Table 1 lists the currently available images.

.. include:: ../../guides/maintenance/download-verify-uncompress-windows.rst
   :Start-after: verify-windows:

Burn the Clear Linux image onto a USB drive
*******************************************

.. caution::

   |CAUTION-BACKUP-USB|

#. 	Download the `Rufus`_ tool to burn the image onto a USB drive.
#. 	Plug in the USB drive.
#. 	Click the :guilabel:`CD-ROM` icon button. See Figure 1.

	.. figure:: figures/bootable-usb-windows-1.png
		:scale: 80 %
		:alt: Rufus utility - Click CD-ROM button

		Figure 1: Rufus utility - Click CD-ROM button

#.	By default, Rufus only shows ISO files.  To find and select a compressed |CL| 
	image file, you must click the file-type dropdown and select :guilabel:`All files`. 
	See Figure 2.

	.. figure:: figures/bootable-usb-windows-2.png
		:scale:	80 %
		:alt: Rufus utility - Show and select |CL| image file

	Figure 2: Rufus utility - Show and select |CL| image file
    
#.	Verify that :guilabel:`Create a bootable disk using DD Image` checkbox is
	checked. See Figure 3.

	.. figure:: figures/bootable-usb-windows-3.png
		:scale: 80 %
		:alt: Rufus utility - Create a bootable disk using DD Image

		Figure 3: Rufus utility - Create a bootable disk using DD Image

#. Click :guilabel:`Start`.

Next steps
**********

With a bootable |CL| USB drive, you can:

* :ref:`bare-metal-install`
* :ref:`boot-live-image`
* :ref:`multi-boot`

.. _Rufus: http://rufus.akeo.ie/
.. _image: https://download.clearlinux.org/image
