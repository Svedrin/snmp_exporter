python_requirement('prometheus_client', name = 'prometheus_client')
python_requirement('pyyaml', name = 'pyyaml')
python_requirement('netsnmp-py', name = 'netsnmp-py')

python_binary(
  name = 'main',
  source = '_snmp_exporter.py',
  dependencies = [
    '//:snmp_exporter',
  ],
)
