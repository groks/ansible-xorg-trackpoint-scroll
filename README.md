xorg-trackpoint-scroll
========

An [ansible role](https://galaxy.ansibleworks.com/) to enable scrolling with
the trackpoint (Thinkpad stick mouse) when holding down the middle mouse button.

    ---
    - hosts: localhost

      roles:
        - groks.xorg-trackpoint-scroll

You will have to log out and back in or reboot for this to take effect.

Requirements
------------

An installation of Linux which uses xorg, such as [Fedora](https://fedoraproject.org/get-fedora).

Role Variables
--------------

    vars:
      - xorg_trackpoint_scroll_sideways: False

Set this to True and you can also scroll sideways.

Dependencies
------------

None.

License
-------

BSD
