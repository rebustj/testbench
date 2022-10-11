# Change for 7.x

This changelog references the relevant changes (bug and security fixes) done to `orchestra/testbench`.

## 7.10.1

Released: 2022-10-11

### Changes

* Update minimum support for Testbench Core v7.10.1+. ([v7.10.0...v7.10.1](https://github.com/orchestral/testbench-core/compare/v7.10.0...v7.10.1))

#### Testbench Changes

##### Fixes

* Remove `bootstrap/cache/packages.php` on vendor symlink event.

## 7.10.0

Released: 2022-10-11

### Changes

* Update minimum support for Testbench Core v7.10.0+. ([v7.9.0...v7.10.0](https://github.com/orchestral/testbench-core/compare/v7.9.0...v7.10.0))

#### Testbench Changes

##### Added

* Added `Orchestra\Testbench\Foundation\Config` to read Yaml file from `testbench.yaml`.

## 7.9.0

Released: 2022-10-05

### Changes

* Update minimum support for Testbench Core v7.9.0+. ([v7.8.1...v7.9.0](https://github.com/orchestral/testbench-core/compare/v7.8.1...v7.9.0))

#### Testbench Changes

##### Added

* Added draft support for PHP 8.2.

##### Changes

* Bump minimum `laravel/framework` to `9.34.0`.
* Bump minimum `mockery/mockery` to `1.5.1`.
* Bump minimum `symfony` dependencies to `6.0.9`.

## 7.8.1

Released: 2022-10-03

### Changes

* Update minimum support for Testbench Core v7.8.1+. ([v7.8.0...v7.8.1](https://github.com/orchestral/testbench-core/compare/v7.8.0...v7.8.1))

#### Testbench Changes

##### Fixes

* Fixes missing `Illuminate\Support\Arr` import on `HandlesTestFailures` trait.

## 7.8.0

Released: 2022-09-28

### Changes

* Update minimum support for Testbench Core v7.8.0+. ([v7.7.1...v7.8.0](https://github.com/orchestral/testbench-core/compare/v7.7.1...v7.8.0))

#### Testbench Changes

##### Changes

* Bump minimum `laravel/framework` to `9.32.0`.
* Improves PHPUnit memory leaks.

## 7.7.1

Released: 2022-09-28

### Changes

* Update minimum support for Testbench Core v7.7.1+. ([v7.7.0...v7.7.1](https://github.com/orchestral/testbench-core/compare/v7.7.0...v7.7.1))

#### Testbench Changes

##### Changes

* Update skeleton to match v9.3.8.

## 7.7.0

Released: 2022-08-10

### Changes

* Update minimum support for Testbench Core v7.7.0+. ([v7.6.1...v7.7.0](https://github.com/orchestral/testbench-core/compare/v7.6.1...v7.7.0))

#### Testbench Changes

##### Added

* Added `loadLaravelMigrationsWithoutRollback()` and `runLaravelMigrationsWithoutRollback()` helpers.

##### Changes

* Update skeleton to match v9.3.5.

## 7.6.1

Released: 2022-08-10

### Changes

* Update minimum support for Testbench Core v7.6.1+. ([v7.6.0...v7.6.1](https://github.com/orchestral/testbench-core/compare/v7.6.0...v7.6.1))

#### Testbench Changes

##### Changes

* Update skeleton to match v9.3.3.

## 7.6.0

Released: 2022-06-30

### Changes

* Update minimum support for Testbench Core v7.6.0+. ([v7.5.0...v7.6.0](https://github.com/orchestral/testbench-core/compare/v7.5.0...v7.6.0))

#### Testbench Changes

##### Changes

* Bump minimum `laravel/framework` to `9.12.0`.
* Update skeleton to match v9.2.0.

## 7.5.0

Released: 2022-05-11

### Changes

* Update minimum support for Testbench Core v7.5.0+. ([v7.4.0...v7.5.0](https://github.com/orchestral/testbench-core/compare/v7.4.0...v7.5.0))

#### Testbench Changes

##### Changes

* Bump minimum `laravel/framework` to `9.12.0`.
* Update skeleton to match v9.1.8.

## 7.4.0

Released: 2022-04-13

### Changes

* Update minimum support for Testbench Core v7.4.0+. ([v7.3.0...v7.4.0](https://github.com/orchestral/testbench-core/compare/v7.3.0...v7.4.0))

#### Testbench Changes

##### Changes

* Bump minimum `laravel/framework` to `9.7.0`.
* Add support for `--drop-databases` on `package:test` command.
* Update skeleton to match v9.1.5.

## 7.3.0

Released: 2022-03-30

### Changes

* Update minimum support for Testbench Core v7.3.0+. ([v7.2.0...v7.3.0](https://github.com/orchestral/testbench-core/compare/v7.2.0...v7.3.0))

#### Testbench Changes

##### Changes

* Bump minimum `laravel/framework` to `9.6.0`.
* Update skeleton to match v9.1.3.

## 7.2.0

Released: 2022-03-20

### Changes

* Update minimum support for Testbench Core v7.2.0+. ([v7.1.0...v7.2.0](https://github.com/orchestral/testbench-core/compare/v7.1.0...v7.2.0))

#### Testbench Changes

##### Changes

* Bump minimum `laravel/framework` to `9.5.1`.
* Update skeleton to match v9.1.1.

## 7.1.0

Released: 2022-02-22

### Changes

* Update minimum support for Testbench Core v7.1.0+. ([v7.0.2...v7.1.0](https://github.com/orchestral/testbench-core/compare/v7.0.2...v7.1.0))

#### Testbench Changes

##### Changes

* Bump minimum `laravel/framework` to `9.2`.
* Remove Laravel 9 beta compatibilities codes.

##### Removed

* Remove `sanctum.php` configuration from skeleton. 

## 7.0.2

Released: 2022-02-14

### Changes

* Update minimum support for Testbench Core v7.0.2+. ([v7.0.1...v7.0.2](https://github.com/orchestral/testbench-core/compare/v7.0.1...v7.0.2))

#### Testbench Changes

##### Changes

* Update skeleton to match v9.0.1.

## 7.0.1

Released: 2022-02-14

### Changes

* Update minimum support for Testbench Core v7.0.1+. ([v7.0.0...v7.0.1](https://github.com/orchestral/testbench-core/compare/v7.0.0...v7.0.1))

#### Testbench Changes

##### Changes

* Add missing `lang/en.json` skeleton file.

## 7.0.0

Released: 2022-02-08

### Changes

* Update support for Laravel Framework v9.
* Increase minimum PHP version to 8.0 and above (tested with 8.0 and 8.1).

#### Testbench Changes

##### Added

* Allows customizing default RateLimiter configuration via `resolveApplicationRateLimiting()` method.
* Added `Orchestra\Testbench\Http\Middleware\PreventRequestsDuringMaintenance` middleware.

##### Changes

* Update support for Laravel Framework v9.
* Increase minimum PHP version to 8.0 and above (tested with 8.0 and 8.1).
* `$loadEnvironmentVariables` property is now set to `true` by default.
* Following internal classes has been marked as `final`:
    - `Orchestra\Testbench\Bootstrap\LoadConfiguration`
    - `Orchestra\Testbench\Console\Kernel`
    - `Orchestra\Testbench\Http\Kernel`
* Moved `resources/lang` skeleton files to `lang` directory.

##### Removed

* Remove deprecated `Illuminate\Foundation\Testing\Concerns\MocksApplicationServices` trait.