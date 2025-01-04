FROM quay.io/keycloak/keycloak:26.0.7

# Add custom themes to the container
COPY ./keycloak-themes /opt/keycloak/themes

# Set the admin username and password
ENV KEYCLOAK_ADMIN=admin
ENV KEYCLOAK_ADMIN_PASSWORD=admin

# Expose the necessary ports
EXPOSE 8080

# Start the Keycloak server in dev mode
CMD ["start-dev"]
