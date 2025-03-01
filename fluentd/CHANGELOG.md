# CHANGELOG - fluentd

<!-- towncrier release notes start -->

## 5.1.0 / 2025-01-16 / Agent 7.63.0

***Added***:

* Add `tls_ciphers` param to integration ([#19334](https://github.com/DataDog/integrations-core/pull/19334))

## 5.0.0 / 2024-10-04 / Agent 7.59.0

***Removed***:

* Remove support for Python 2. ([#18580](https://github.com/DataDog/integrations-core/pull/18580))

***Fixed***:

* Bump the version of datadog-checks-base to 37.0.0 ([#18617](https://github.com/DataDog/integrations-core/pull/18617))

## 4.0.0 / 2024-10-01 / Agent 7.58.0

***Changed***:

* Bump minimum version of base check ([#18733](https://github.com/DataDog/integrations-core/pull/18733))

***Added***:

* Bump the python version from 3.11 to 3.12 ([#18212](https://github.com/DataDog/integrations-core/pull/18212))

## 3.2.1 / 2024-05-31 / Agent 7.55.0

***Fixed***:

* Update the description for the `tls_ca_cert` config option to use `openssl rehash` instead of `c_rehash` ([#16981](https://github.com/DataDog/integrations-core/pull/16981))

## 3.2.0 / 2024-02-16 / Agent 7.52.0

***Added***:

* Update the configuration file to include the new oauth options parameter ([#16835](https://github.com/DataDog/integrations-core/pull/16835))

## 3.1.0 / 2024-01-05 / Agent 7.51.0

***Added***:

* Bump the Python version from py3.9 to py3.11 ([#15997](https://github.com/DataDog/integrations-core/pull/15997))

## 3.0.0 / 2023-08-10 / Agent 7.48.0

***Changed***:

* Bump the minimum base check version ([#15427](https://github.com/DataDog/integrations-core/pull/15427))

***Added***:

* Update generated config models ([#15212](https://github.com/DataDog/integrations-core/pull/15212))

***Fixed***:

* Fix types for generated config models ([#15334](https://github.com/DataDog/integrations-core/pull/15334))

## 2.2.1 / 2023-07-10 / Agent 7.47.0

***Fixed***:

* Bump Python version from py3.8 to py3.9 ([#14701](https://github.com/DataDog/integrations-core/pull/14701))

## 2.2.0 / 2022-09-16 / Agent 7.40.0

***Added***:

* Update HTTP config spec templates ([#12890](https://github.com/DataDog/integrations-core/pull/12890))

## 2.1.0 / 2022-04-05 / Agent 7.36.0

***Added***:

* Add metric_patterns options to filter all metric submission by a list of regexes ([#11695](https://github.com/DataDog/integrations-core/pull/11695))

***Fixed***:

* Remove outdated warning in the description for the `tls_ignore_warning` option ([#11591](https://github.com/DataDog/integrations-core/pull/11591))

## 2.0.0 / 2022-02-19 / Agent 7.35.0

***Changed***:

* Add tls_protocols_allowed option documentation ([#11251](https://github.com/DataDog/integrations-core/pull/11251))

***Added***:

* Add `pyproject.toml` file ([#11351](https://github.com/DataDog/integrations-core/pull/11351))

***Fixed***:

* Fix namespace packaging on Python 2 ([#11532](https://github.com/DataDog/integrations-core/pull/11532))

## 1.14.1 / 2022-01-08 / Agent 7.34.0

***Fixed***:

* Add comment to autogenerated model files ([#10945](https://github.com/DataDog/integrations-core/pull/10945))

## 1.14.0 / 2021-11-13 / Agent 7.33.0

***Added***:

* Add runtime configuration validation ([#8916](https://github.com/DataDog/integrations-core/pull/8916))

## 1.13.0 / 2021-10-04 / Agent 7.32.0

***Added***:

* Add HTTP option to control the size of streaming responses ([#10183](https://github.com/DataDog/integrations-core/pull/10183))
* Add allow_redirect option ([#10160](https://github.com/DataDog/integrations-core/pull/10160))

***Fixed***:

* Fix the description of the `allow_redirects` HTTP option ([#10195](https://github.com/DataDog/integrations-core/pull/10195))

## 1.12.1 / 2021-03-07 / Agent 7.27.0

***Fixed***:

* Bump minimum base package version ([#8443](https://github.com/DataDog/integrations-core/pull/8443))

## 1.12.0 / 2020-10-31 / Agent 7.24.0

***Added***:

* Add ability to dynamically get authentication information ([#7660](https://github.com/DataDog/integrations-core/pull/7660))

## 1.11.0 / 2020-09-30

***Added***:

* Add support for additional metrics ([#7685](https://github.com/DataDog/integrations-core/pull/7685))

## 1.10.0 / 2020-09-21 / Agent 7.23.0

***Added***:

* Add RequestsWrapper option to support UTF-8 for basic auth ([#7441](https://github.com/DataDog/integrations-core/pull/7441))

***Fixed***:

* Update proxy section in conf.yaml ([#7336](https://github.com/DataDog/integrations-core/pull/7336))

## 1.9.1 / 2020-08-10 / Agent 7.22.0

***Fixed***:

* DOCS-838 Template wording ([#7038](https://github.com/DataDog/integrations-core/pull/7038))
* Update ntlm_domain example ([#7118](https://github.com/DataDog/integrations-core/pull/7118))

## 1.9.0 / 2020-06-29 / Agent 7.21.0

***Added***:

* Add note about warning concurrency ([#6967](https://github.com/DataDog/integrations-core/pull/6967))

***Fixed***:

* Reduce log level of version collection warnings to DEBUG ([#6930](https://github.com/DataDog/integrations-core/pull/6930))
* Fix template specs typos ([#6912](https://github.com/DataDog/integrations-core/pull/6912))

## 1.8.0 / 2020-05-17 / Agent 7.20.0

***Added***:

* Allow optional dependency installation for all checks ([#6589](https://github.com/DataDog/integrations-core/pull/6589))

## 1.7.1 / 2020-04-07 / Agent 7.19.0

***Fixed***:

* Add `kerberos_cache` to HTTP config options ([#6279](https://github.com/DataDog/integrations-core/pull/6279))

## 1.7.0 / 2020-04-04

***Added***:

* Add option to set SNI hostname via the `Host` header for RequestsWrapper ([#5833](https://github.com/DataDog/integrations-core/pull/5833))
* Add config specs ([#6147](https://github.com/DataDog/integrations-core/pull/6147))

***Fixed***:

* Update deprecated imports ([#6088](https://github.com/DataDog/integrations-core/pull/6088))
* Remove logs sourcecategory ([#6121](https://github.com/DataDog/integrations-core/pull/6121))

## 1.6.0 / 2020-03-18

***Added***:

* Support Fluentd config API endpoint for metadata collection ([#6062](https://github.com/DataDog/integrations-core/pull/6062))
* Allow disabling metadata collection in fluentd ([#6061](https://github.com/DataDog/integrations-core/pull/6061))

## 1.5.0 / 2019-11-26 / Agent 7.16.0

***Added***:

* Collect version metadata for Fluentd ([#5057](https://github.com/DataDog/integrations-core/pull/5057))
* Add auth type to RequestsWrapper ([#4708](https://github.com/DataDog/integrations-core/pull/4708))

## 1.4.0 / 2019-10-11 / Agent 6.15.0

***Added***:

* Add option to override KRB5CCNAME env var ([#4578](https://github.com/DataDog/integrations-core/pull/4578))

## 1.3.0 / 2019-08-24 / Agent 6.14.0

***Added***:

* Fix request wrapper timeout and add test ([#4375](https://github.com/DataDog/integrations-core/pull/4375))
* Add support for proxy settings ([#3479](https://github.com/DataDog/integrations-core/pull/3479))

***Fixed***:

* Update __init__ method params ([#4243](https://github.com/DataDog/integrations-core/pull/4243))

## 1.2.0 / 2019-05-14 / Agent 6.12.0

***Added***:

* Adhere to code style ([#3507](https://github.com/DataDog/integrations-core/pull/3507))

## 1.1.1 / 2019-03-29 / Agent 6.11.0

***Fixed***:

* Support fluentd v1's monitor_agent metrics ([#2965](https://github.com/DataDog/integrations-core/pull/2965)) Thanks [repeatedly](https://github.com/repeatedly).

## 1.1.0 / 2019-01-04 / Agent 6.9.0

***Added***:

* Support Python 3 ([#2735][1])

## 1.0.1 / 2018-09-04 / Agent 6.5.0

***Fixed***:

* Add data files to the wheel package ([#1727][2])

## 1.0.0 / 2017-03-22

***Added***:

* adds fluentd integration.

[1]: https://github.com/DataDog/integrations-core/pull/2735
[2]: https://github.com/DataDog/integrations-core/pull/1727
