Role Name
=========

Configure Ossec Wazuh service

Requirements
------------

None

Role Variables
--------------

- ossec_wazuh_version: ossec-wazuh version, current one is 1.1.1
- ossec_email_from: Ossec email from value.
- ossec_email_address: Ossec email destination
- ossec_enable_email: enable/disable email notifications, use "y" or "n"
- ossec_clean_previous: clean previous installation

Integrations

- ossec_wazuh_integrator_slack_hook_url:
- ossec_wazuh_integrator_pagerduty_api_key:
- ossec_wazuh_integrator_slack_level: 4
- ossec_wazuh_integrator_pagerduty_level: 7

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - ossec-wazuh

License
-------

BSD

Author Information
------------------

Author: Gustavo Folga
Original Author: Antonio Barbaro <antonio.barbaro@gmail.com>
