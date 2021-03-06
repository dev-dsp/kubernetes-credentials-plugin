CHANGELOG
=========

Master (unreleased)
-----

0.4.1
-----
* Plugin description should live in index.jelly [#10](https://github.com/jenkinsci/kubernetes-credentials-plugin/pull/10)

0.4.0
-----
* Fix compatibility with PCT [#4](https://github.com/jenkinsci/kubernetes-credentials-plugin/pull/4)
* Require Jenkins core 2.60.3
* Remove packaged apache-httpclient and depend on [apache-httpcomponents-client-4-api-plugin](https://github.com/jenkinsci/apache-httpcomponents-client-4-api-plugin) instead.

0.3.1
-----
* Save OpenShift token between calls [#3](https://github.com/jenkinsci/kubernetes-credentials-plugin/pull/3)
* Cache OpenShift token per URL
* Improve plugin testing

0.3.0
-----
* Improve README
* More meaningful credential names [#2](https://github.com/jenkinsci/kubernetes-credentials-plugin/pull/2)


0.2.0
-----
* Initial release; extracted from [kubernetes-plugin](https://github.com/jenkinsci/kubernetes-plugin) starting with version 1.2.
