# Highly Available PostgreSQL Chart with Logical Backups

Leveraging [Zalando's postgres-operator](https://github.com/zalando/postgres-operator) to create highly available cluster, adding CronJob with logical backups to bucket or volume.

The operator must be installed prior to using this chart.

## _Istio Support_:
Supports also creating Istio Destination Rules & Virtual Service for the primary & standby services.
Backup job will signal envoy to exit at end.

See values.yaml.
