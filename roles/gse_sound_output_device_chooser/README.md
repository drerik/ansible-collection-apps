drerik.apps.gse_sound_output_device_chooser
=========

Install the Gnome shell extension "Sound Input & Output Device Chooser"
Gnome extension page: <https://extensions.gnome.org/extension/906/sound-output-device-chooser/>
Repo: <https://github.com/kgshank/gse-sound-output-device-chooser>

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

Note: run as local user not root. This installs the extension to the `ansible_user` homedir.


    - name: Do user specific updates
      hosts: localhost
      roles:
        - drerik.apps.gse_sound_output_device_chooser

License
-------

Apache-2.0

Author Information
------------------

Erik Kaareng-Sunde <erik@eriksunde.com>
