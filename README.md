Dell U2713HM Role
=================
Manage X11 configuration files necessary to support 1440p over HDMI for Dell U2713HM monitors

This role adds a mode supporting 1440p over HDMI at 30hz. This mode is not advertised by the monitor and not officially supported by Dell.

Example Playbook
----------------
    - hosts: workstations
      roles:
         - { role: ivan-c.dell-u2713hm }

License
-------
BSD
