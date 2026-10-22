FROM sonarqube:community

# The official image has no "sonarqube" group; the user is uid 1000, gid 0 (root)
COPY --chown=sonarqube:root esql-plugin-3.3.0.jar /opt/sonarqube/extensions/plugins/
