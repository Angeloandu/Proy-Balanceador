# Balanceador de Carga con Apache + SSL

## Descripción
Proyecto de balanceador de carga implementado con Apache HTTP Server, configuración SSL, base de datos MySQL y testing con Artillery.

## Arquitectura
- **Load Balancer**: Apache HTTP Server con mod_proxy_balancer
- **SSL/TLS**: Certificados SSL configurados
- **Base de Datos**: MySQL para almacenamiento
- **Testing**: Artillery para pruebas de carga
- **Sistema Operativo**: Ubuntu Linux

## Estructura del Proyecto
proyecto/
├── apache-config/          # Configuraciones de Apache
├── ssl-certificates/       # Certificados SSL (sin claves privadas)
├── mysql-config/          # Configuración de MySQL
├── artillery-tests/       # Scripts de testing con Artillery
├── scripts/              # Scripts de instalación y configuración
└── docs/                # Documentación adicional

## Instalación

### Prerrequisitos
- Ubuntu 20.04 o superior
- Apache2
- MySQL 8.0+
- Node.js (para Artillery)

### Pasos de instalación
1. Clonar el repositorio
2. Ejecutar script de instalación
3. Configurar certificados SSL
4. Configurar base de datos MySQL
5. Ejecutar tests con Artillery

## Uso
[Instrucciones de uso detalladas]

## Testing
```bash
# Ejecutar tests de carga con Artillery
artillery run artillery-tests/load-test.yml
