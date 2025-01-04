FROM quay.io/keycloak/keycloak:26.0.7

# Add custom themes
COPY ./keycloak-themes /opt/keycloak/themes

# Expose port 8080
EXPOSE 8080

# Run Keycloak
ENTRYPOINT ["/opt/keycloak/bin/kc.sh"]
CMD ["start-dev"]
