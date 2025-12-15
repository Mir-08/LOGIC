cat > README.md << 'EOF'
# LOGIC Solutions - Sistema Odoo 19

Este repositorio contiene la configuración y datos para restaurar el sistema ERP Odoo 19 implementado para Logística Rápida Exprés.

## Archivos principales:
- docker-compose.yml - Configuración de contenedores
- datos_odoo_backup.zip - Base de datos comprimida
- volumesOdoo/addons/ - Directorio para módulos personalizados

## Pasos para restaurar el sistema:

1. Clonar el repositorio

2. Extraer la base de datos:
   unzip datos_odoo_backup.zip

3. Iniciar los contenedores:
   docker-compose up -d

El sistema estará disponible en: http://localhost:8069

## Credenciales de acceso:

Odoo:
- Email: logicsolutions@gmail.com
- Contraseña: LogicSGE
EOF
