# 🛠️ Contribuir

## 📌 Flujo de Trabajo

Este proyecto utiliza la rama `main` como rama de producción. Todas las nuevas funcionalidades o correcciones de errores deben desarrollarse en ramas separadas.

### Para agregar una nueva funcionalidad:

1. Crea una nueva rama desde `main`.
2. Realiza los cambios.
3. Abre un Pull Request (PR) hacia `main`.
4. El PR debe ser aprobado por al menos un colaborador, aunque puede ser aprobado por el mismo autor si no requiere revisión adicional.

### Nomenclatura de Ramas

Es importante que las ramas tengan nombres descriptivos. Ejemplos:

- Para una nueva funcionalidad de la API: `feature-api-autenticacion`
- Para una corrección: `fix-api-autenticacion`

### Ramas Especiales

- `docs`: Esta rama está dedicada exclusivamente a documentación del proyecto (por ejemplo, archivos en la carpeta `docs` o el `README.md`).

---

## 🚀 Pasos para Contribuir

1. Clona el repositorio:

   ```bash
   git clone <URL-del-repo>
   ```

2. Crea una nueva rama:

   ```bash
   git checkout -b nombre-de-la-nueva-rama
   ```

3. Publica la rama en el repositorio remoto:

   ```bash
   git push --set-upstream origin nombre-de-la-nueva-rama
   ```

4. Realiza los commits necesarios:

   ```bash
   git commit -m "feat: agrega nueva funcionalidad de autenticación"
   ```

5. Haz push a la rama:

   ```bash
   git push origin nombre-de-la-nueva-rama
   ```

6. Abre un Pull Request desde tu rama hacia `main`.

---

## ✏️ Convenciones de Commits

Utilizamos _commits convencionales_ para mantener la organización y facilitar la automatización de versiones.

Formato:

```
<tipo>(área-afectada): breve descripción
```

Tipos comunes:

- `feat`: Nueva funcionalidad.
  - Ej: `feat(api): agrega autenticación con tokens`
- `fix`: Corrección de errores.
  - Ej: `fix(auth): corrige validación de sesión`
- `chore`: Cambios menores sin impacto en el usuario.
  - Ej: `chore(ci): actualiza configuración de GitHub Actions`
- `docs`: Cambios en la documentación.
  - Ej: `docs: agrega sección de instalación al README`
