# GitHub Copilot Instructions

## Visión General

El Portal Orihuela Costa es una aplicación web estática para la comunidad de Orihuela Costa.

## Estructura del Proyecto

- **index.html** - Página principal
- **.git/** - Repositorio Git
- **.gitignore** - Archivos ignorados en Git

## Flujos de Desarrollo

### Comandos Básicos
```bash
git status        # Ver cambios
git add .         # Agregar archivos
git commit -m "Mensaje"  # Commitear
git push          # Empujar cambios
```

### Git Workflow
- **main**: Rama principal (producción)
- **feature/***: Nuevas funcionalidades
- **fix/***: Correcciones de bugs

## Patrones del Proyecto

### HTML
- Mantén estructura semántica
- Usa IDs descriptivos para elementos
- Comenta secciones principales

### Commits
- Mensajes descriptivos: "Add section", "Fix typo"
- Cambios relacionados en un commit
- Referencia issues: "Fix #123"

## Consideraciones Importantes

1. **Validar HTML** antes de commitear
2. **Optimizar imágenes** si las usas
3. **Testing**: Abre en navegadores diferentes
4. **Accesibilidad**: ARIA labels y semantic HTML

## Archivos Clave

- `README.md` - Descripción del proyecto
- `index.html` - Página principal
- `.gitignore` - Archivos ignorados
