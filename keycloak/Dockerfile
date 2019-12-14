FROM docker-registry.default.svc:5000/openshift/redhat-sso73-openshift

ARG PLUGIN_NAME=keycloak-franceconnect
ARG PLUGIN_VERSION=1.4
ARG PLUGIN_REPO=https://github.com/InseeFr/Keycloak-FranceConnect

RUN curl -o /opt/eap/standalone/deployments/${PLUGIN_NAME}-${PLUGIN_VERSION}.jar \
      $PLUGIN_REPO/releases/download/$PLUGIN_VERSION/${PLUGIN_NAME}-${PLUGIN_VERSION}.jar

