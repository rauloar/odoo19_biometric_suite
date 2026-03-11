# Drivers

The biometric suite separates public foundation modules from commercial hardware drivers.

## Public modules

- `odoo19_biometric_core`: shared models, services, and base integration logic.
- `odoo19_biometric_fake`: fake/testing driver for development and QA.

## Commercial drivers

- `odoo19_biometric_zkteco`: production ZKTeco integration.
- `odoo19_biometric_hikvision`: production Hikvision integration.
- `odoo19_biometric_import`: import-oriented commercial connector module.

Commercial repositories are private and distributed under license terms.
