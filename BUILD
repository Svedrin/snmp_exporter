python_library(
  name = 'snmp_exporter',
  sources = globs('snmp_exporter/*.py'),
  dependencies = [ ':requirements' ],
)
python_requirement_library(
  name='requirements',
  requirements = [
    python_requirement('prometheus_client', name = 'prometheus_client'),
    python_requirement('pyyaml', name = 'pyyaml'),
    python_requirement('netsnmp-py', name = 'netsnmp-py'),
  ]
)
