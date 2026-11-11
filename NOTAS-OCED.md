# Autenticador del panel de edición del OCED

Copia de `sveltia/sveltia-cms-auth`, desplegada como Worker de Cloudflare (`sveltia-cms-auth`).
Permite que cada responsable entre al panel de oced.edu.do/admin con su cuenta de GitHub.

Configuración del despliegue en Cloudflare:
- Comando de despliegue: `npx wrangler deploy`
- Variable de compilación: `SKIP_DEPENDENCY_INSTALL=1`
- Variables del Worker: `GITHUB_CLIENT_ID`, `GITHUB_CLIENT_SECRET` (secreto) y `ALLOWED_DOMAINS=oced.edu.do`
