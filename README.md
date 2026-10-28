# FMCSA TPR Reporting for Moodle




A Moodle local plugin for managing, and submitting results for ELDT Theory, Behind-the-Wheel Range and Behind-the-Wheel Road training results for Commercial Driver's License (CDL) driver candidates to the FMCSA's Training Provider Registry.




## Development status




Community beta 1.5.0-beta2 passed clean Moodle 5.3 installation, PHP syntax, Moodle coding standards, package validation, template validation and six regression tests on both PostgreSQL 17 and MariaDB 11. MySQL/PHP 8.3 workflows, JavaScript and CSS were also checked independently. Marketplace submission and approval are separate and remain pending. Do not treat this repository as an approved Moodle Marketplace listing or an FMCSA endorsement.




## Bug reports




Use [GitHub Issues](https://github.com/jasonrgrammes/moodle-local_fmcsatprreporting/issues) to report a problem. Include your Moodle, PHP and plugin versions, steps to reproduce, and a redacted error message.




**Do not post student information, driver licence numbers, birth dates, certificates, private keys, passwords, provider credentials or unredacted submission logs.**




## Planned community release




- One submitted record card per student, with separate theory, range and road status.
- Configurable providers and course mappings.
- Range and road hours entry from Eligible and Submitted cards.
- Group filters, alphabet filters, archive and restore, and submission history.
- Privacy API support and a standard Moodle installation ZIP.




The community ZIP will initially target clean Moodle 5.3 installations. Existing private installations require a separately reviewed upgrade path; do not uninstall an existing plugin to bypass a version check.






## Download and installation


[Download tested beta2 build](https://github.com/jasonrgrammes/moodle-local_fmcsatprreporting/actions/runs/40660990718/artifacts/12803443883) (GitHub sign-in required; build artifact retained for 30 days). Extract the downloaded artifact ZIP and upload its inner **local_govreporting-1.5.0-beta2.zip** to Moodle. It contains the full GPL source, LICENSE, installation instructions and UPGRADING.md.

[Successful database and package checks](https://github.com/jasonrgrammes/moodle-local_fmcsatprreporting/actions/runs/40660990718). The older beta1 ZIP in the repository is retained for history and has been superseded by beta2. A permanent release attachment is still to be published.


For a clean Moodle 5.3 site, upload the ZIP through Site administration > Plugins > Install plugins. No certificate, student data or site credentials are included.


**Do not install this candidate over the existing private predecessor.** Its legacy version number requires a separately reviewed migration; do not uninstall the working plugin or reset version metadata.

