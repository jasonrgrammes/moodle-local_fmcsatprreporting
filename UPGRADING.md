# Existing private installations

This is a clean-install community candidate for Moodle 5.3, component local_govreporting.
The private predecessor used version 2025040428316, which is numerically larger than the standard community version 2026102800. Moodle correctly rejects installing this ZIP as a downgrade on that predecessor.

Do not uninstall the private plugin, reset its version, or delete submission tables to work around this. Keep that working installation. A separately reviewed migration/release bridge is required before moving an existing private site onto the community release line. No such migration is executed by this ZIP.

Future community releases must increase the standard YYYYMMDDXX version and provide XMLDB upgrade steps when the schema changes.
