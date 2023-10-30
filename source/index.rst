Hardening Android
================================================

These mitigations to `common mobile threats <https://pap.tymyrddin.dev/>`_ are kept as simple as possible, with tools found in most Androids and online.

Other things are harder to cover. For example, each manufacturer has its own privacy settings somewhere, and there is a growing number of alternative apps that do not report everything you do to Google.

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Accounts and authentication

   docs/authentication/README.md
   docs/authentication/sim-pin.md
   docs/authentication/screen-lock.md
   docs/authentication/notifications.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Services and applications

   docs/services/README.md
   docs/services/app-stores.md
   docs/services/research.md
   docs/services/unwanted-apps.md
   docs/services/remove-apps.md
   docs/services/browsers.md
   docs/services/default-apps.md
   docs/services/messaging.md
   docs/services/email-services.md
   docs/services/ssh.md
   docs/services/vpn.md
   docs/services/tor-proxy.md
   docs/services/change-mac.md
   docs/services/edit-hosts-file.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Data

   docs/data/README.md
   docs/data/*

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Privacy

   docs/privacy/README.md
   docs/privacy/diagnostics.md
   docs/privacy/autofill-google.md
   docs/privacy/location.md
   docs/privacy/activity-controls.md
   docs/privacy/personalised-ads.md
   docs/privacy/alternatives.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Malware

   docs/malware/README.md
   docs/opsec/threats.md
   docs/malware/scanner.md
   docs/malware/clean-machine.md
   docs/malware/ransomware.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Operations security

   docs/opsec/README.md
   docs/opsec/threats.md
   docs/opsec/juice-jack.md
   docs/opsec/autojoin.md
   docs/opsec/email-use.md
   docs/opsec/browsing.md
   docs/opsec/ooni.md
   docs/opsec/*

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Guards! Guards!

   docs/guards/README.md
   docs/guards/*
