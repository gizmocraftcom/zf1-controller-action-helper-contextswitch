# Changelog

## 2.0.0

Fork of `diablomedia/zendframework1-controller-action-helper-contextswitch`, published as `gizmocraft/zendframework1-controller-action-helper-contextswitch`.

### Breaking changes

- Requires PHP `>=8.5`. Tested on PHP 8.5 and 8.6.
- Package renamed from `diablomedia/zendframework1-controller-action-helper-contextswitch` to `gizmocraft/zendframework1-controller-action-helper-contextswitch`. It now requires the `gizmocraft/zendframework1-*` packages `config` `^3.0.0`, `controller` `^2.0.0`, `json` `^2.0.0`, `layout` `^2.0.0` and `view` `^2.0.0`.

### Other changes

- No library code changes and no public signature changes were needed for PHP 8.5 and 8.6.
- Dev dependencies upgraded (PHPUnit 13, PHPStan 2.3, php-cs-fixer 3.95, GrumPHP 2.27). Dropped `composer-require-checker`, which has no release for PHP 8.6.
- Tests migrated to PHPUnit 13 (`#[Group]` attributes).
- CI runs PHP 8.5 and 8.6.
