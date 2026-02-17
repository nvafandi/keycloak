# Database
- POSTGRES_DB=nurvan.my.id
- POSTGRES_USER=nurvan
- POSTGRES_PASSWORD=

# Keycloak admin
- KEYCLOAK_ADMIN=admin
- KEYCLOAK_ADMIN_PASSWORD=admin123

# Kustomisasi
- KEYCLOAK_HTTP_PORT=8080
- DB_HOST=db            # jika DB di stack/host lain, ubah ke hostname atau ip
- KC_HOSTNAME=          # optional: set jika ingin override hostname (mis. kc.example.com)

# Backup (opsional)
- BACKUP_DIR=/backups

# SSH
- SSH_USERNAME: nurvan
- SSH_PRIVATE_KEY:
- SSH_PORT: 22
- SSH_HOST: nurvan.my.id

# DOCKER
- DOCKER_USERNAME: nurvanafandi
- DOCKER_PASSWORD:
- DOCKER_REPOSITORY: nurvanafandi/keycloak
- DOCKER_REGISTRY: docker.io