# SonarQube + Postgresql

### Troubleshoots before start
1. Run sysctl -w vm.max_map_count=262144
2. chmod 777 -R ./ - Actualy it is a knowed issue by sonarqube team, and after create the default directory struct you should grant full access to directory tree.

### Starting
1. Clone repository
2. Change paths of volumes to persist data
3. Run docker-compose up -d

### Defaults
1. SonarQube user: admin
2. SonarQube password: admin