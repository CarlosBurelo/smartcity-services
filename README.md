cat > README.md << 'EOF'
# SmartCity Services

## Estructura del repositorio
- /docs → Documentación
- /src → Código compartido
- /microservices → Microservicios independientes
- /docker → Archivos Docker y docker-compose
- /.github/workflows → Pipelines CI/CD

## Convención de ramas
- main → producción
- develop → integración
- feature/<nombre> → nuevas funcionalidades

## Cómo correr localmente
1. Entrar a un microservicio
2. Instalar dependencias
3. Ejecutar Flask o framework correspondiente

## CI/CD
Este repositorio usa GitHub Actions para:
- Validación de código
- Ejecución de pruebas
- Construcción de imágenes Docker
- Despliegue a ambiente de pruebas
