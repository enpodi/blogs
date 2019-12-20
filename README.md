# blogs
		
https://github.com/weepee-org/openshift-example-project/blob/master/memsql-master/DeploymentConfig.yaml		
		
		
		
		
		
		
https://confluence.atlassian.com/bitbucket/branching-a-repository-223217999.html		
		
		
		
metrics send to prometheus through actuator		
https://labs.consol.de/development/2018/01/19/openshift_application_monitoring.html		
	Description	
***************** DOCKER-COMPOSE ****************************************		
https://docs.docker.com/compose/compose-file	You can use environment variables in configuration values with a Bash-like ${VARIABLE} syntax - see variable substitution for full details.	
https://docs.docker.com/compose/compose-file/#variable-substitution	variable-substitution	
		
*********************YML********************************************		
https://yaml.org/spec/1.2/spec.html		
		
		
**************************READY API********************************************		
https://support.smartbear.com/readyapi/docs/soapui/tutorial/your-first-test/create-project.html		
https://www.youtube.com/watch?v=EzhjMNUnWdU	ReadyAPI 101: Getting Started with API Testing | SmartBear Academy Tutorial	
https://www.youtube.com/watch?v=Cd4Nj767O88	How to Start with REST Testing in ReadyAPI | API Testing Tutorial	
https://www.youtube.com/watch?v=2r-QeMqs8ak	Speed Up Your Testing With Headless Browsers	headless testing with CrossBrowserTesting
		
		
		
************************PROMETHEUS*****************************************		
https://www.fabernovel.com/en/engineering/alerting-in-prometheus-or-how-i-can-sleep-well-at-night		
https://github.com/alerta/prometheus-config		
		
		
		
		
		
********************************THANOS************************		
https://medium.com/uswitch-labs/making-prometheus-more-awesome-with-thanos-fbec8c6c28ad	Making Prometheus more awesome with Thanos	



https://github.com/openshift/origin

https://prometheus-openshift-monitoring.tocpsat1.usaa.com/alerts


https://github.com/PacktPublishing/Hands-On-Infrastructure-Monitoring-with-Prometheus	Hands-On-Infrastructure-Monitoring-with-Prometheus
	
	
	
	
https://github.com/prometheus/prometheus/blob/master/rules/alerting.go	prometheus github documentation
https://github.com/prometheus/alertmanager	"prometheus alertmanager github documentation

# To aggregate by all possible labels use '...' as the sole label name.
# This effectively disables aggregation entirely, passing through all
# alerts as-is. This is unlikely to be what you want, unless you have
# a very low alert volume or your upstream notification system performs
# its own grouping. Example: group_by: [...]
group_by: ['alertname', 'cluster']"
https://prometheus.io/docs/alerting/configuration/	"Alertmanager is configured via command-line flags and a configuration file. While the command-line flags configure immutable system parameters, the configuration file defines inhibition rules, notification routing and notification receivers.

The visual editor can assist in building routing trees."
https://github.com/prometheus/alertmanager	example
https://prometheus.io/webtools/alerting/routing-tree-editor/	
https://groups.google.com/forum/#!forum/prometheus-users	
https://community.atlassian.com/t5/Jira-Software-questions/Assistance-creating-Jira-ticket-as-Prometheus-alert-fires/qaq-p/1117144	jira ticket as prometheus alert
	
https://prometheus.io/docs/prometheus/latest/configuration/template_reference/	
https://prometheus.io/docs/prometheus/latest/configuration/template_examples/	
https://www.weave.works/blog/labels-in-prometheus-alerts-think-twice-before-using-them	
https://golang.org/pkg/text/template/#hdr-Text_and_spaces	
https://www.weave.works/blog/weave-cloud-product-updates-and-announcements	
https://www.weave.works/blog/the-official-gitops-faq	
https://golang.org/pkg/text/template/#hdr-Actions	
https://banzaicloud.com/blog/grafana-templating/	
https://www.zabbix.com/integrations/prometheus	
https://github.com/prometheus/node_exporter	
https://github.com/prometheus/node_exporter/releases/tag/v0.16.0	
https://awesomeopensource.com/projects/prometheus	
https://awesomeopensource.com/project/stefanprodan/dockprom	
https://awesomeopensource.com/project/vegasbrianc/prometheus	
https://grafana.com/grafana/dashboards/179	I created a Dashboard template which is available on Grafana Docker Dashboard. Simply select Import from the Grafana menu -> Dashboards -> Import and provide the Dashboard ID #179
https://github.com/vegasbrianc/prometheus/	open project with docker
https://github.com/vegasbrianc/docker-pulls	open project with docker
https://github.com/maxandersen/internet-monitoring	open project with docker
https://github.com/RiFi2k/dockerize-your-dev	
https://prometheus.io/blog/2016/01/26/one-year-of-open-prometheus-development/	One Year of Open Prometheus Development
	
https://prometheus.io/docs/alerting/configuration/	alert manager setup
https://www.weave.works/blog/labels-in-prometheus-alerts-think-twice-before-using-them	Labels in Prometheus alerts: think twice before using them



https://micrometer.io/docs	
http://micrometer.io/docs/concepts#_histograms_and_percentiles	
https://micrometer.io/docs/registry/prometheus	
https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#production-ready-metrics-per-meter-properties	
https://prometheus.io/docs/practices/histograms/	
https://prometheus.io/docs/practices/histograms/#quantiles	
	
https://groups.google.com/forum/#!forum/prometheus-users	several questions and answers
	
	
****** spring boot and micrometer ***************************	
https://micrometer.io/docs/concepts	Micrometer provides a static global registry Metrics.globalRegistry and a set of static builders for generating meters based on this registry. globalRegistry is a composite registry.
https://micrometer.io/docs/ref/spring/1.5	
https://www.baeldung.com/micrometer	"Micrometer provides a simple facade over the instrumentation clients for a number of popular monitoring systems. Currently, it suports the following monitoring systems: Atlas, Datadog, Graphite, Ganglia, Influx, JMX and Prometheus.

Spring Boot Actuator provides dependency management and auto-configuration for Micrometer.
Without any further change to existing code, we have enabled Spring support with the Micrometer. JVM memory metrics of our Spring application will be automatically registered in the global registry and published to the default atlas endpoint: http://localhost:7101/api/v1/publish."
https://www.codota.com/code/java/methods/io.micrometer.core.instrument.MeterRegistry/config	examples
https://touk.pl/blog/2018/03/05/spring-boot-2-0-http-request-metrics-with-micrometer/	access disabled
https://github.com/maxwo/snmp_notifier	"It has been created to handle older monitoring and alerting systems such as Nagios or Centreon.

Prometheus' Alertmanager sends the alerts to the SNMP notifier on its HTTP API. The SNMP notifier then looks for OID in the given alerts' labels. Each trap is sent with a unique ID, which allows, if the alert is updated or once it is resolved, to send additional traps with updated status and data."








