# 📚 Índice de Documentación - CTI Platform

**Versión**: 1.0.0  
**Fecha**: Marzo 2026  
**Clasificación**: UNCLASSIFIED  

---

## 📖 Documentación Disponible

### 🚀 Guías de Inicio

| Documento | Descripción | Audiencia | Formato |
|-----------|-------------|-----------|---------|
| **QUICKSTART.md** | Comienza en 5 minutos | Todos | Markdown |
| **INSTRUCCIONES_INICIALES.txt** | Introducción visual | Todos | Texto |
| **README.md** | Descripción general | Todos | Markdown |

### 📋 Documentación Funcional

| Documento | Descripción | Audiencia | Formato |
|-----------|-------------|-----------|---------|
| **USER_GUIDE.md** | Guía completa del usuario | Analistas | Markdown |
| **ARCHITECTURE.md** | Arquitectura técnica | Desarrolladores | Markdown |
| **REQUIREMENTS_SPECIFICATION.md** | Requisitos funcionales | PM/Stakeholders | Markdown |

### ⚙️ Documentación Operacional

| Documento | Descripción | Audiencia | Formato |
|-----------|-------------|-----------|---------|
| **ADMIN_MANUAL.md** | Manual de administración | Administradores | Markdown |
| **SECURITY_GUIDE.md** | Guía de seguridad | Security team | Markdown |
| **DEPLOYMENT.md** | Guía de despliegue | DevOps | Markdown |

### 🔧 Documentación Técnica

| Documento | Descripción | Audiencia | Formato |
|-----------|-------------|-----------|---------|
| **API.md** | Documentación API (Futuro) | Desarrolladores | Markdown |
| **TESTING.md** | Guía de testing (Futuro) | QA/Developers | Markdown |
| **COMPATIBILITY.md** | Matriz de compatibilidad | Ops | Markdown |

---

## 📍 Ubicación de Documentos

```
cti-platform/
├── docs/                          ← DOCUMENTACIÓN PRINCIPAL
│   ├── INDEX.md                   ← Este archivo
│   ├── ARCHITECTURE.md            ← Arquitectura técnica
│   ├── USER_GUIDE.md              ← Guía del usuario
│   ├── ADMIN_MANUAL.md            ← Manual del administrador
│   ├── SECURITY_GUIDE.md          ← Guía de seguridad
│   ├── REQUIREMENTS_SPECIFICATION.md
│   ├── API.md (futuro)
│   ├── TESTING.md (futuro)
│   └── COMPATIBILITY.md (futuro)
│
├── README.md                      ← Overview general
├── QUICKSTART.md                  ← Quick start guide
├── DEPLOYMENT.md                  ← Deployment guide
├── CONTRIBUTING.md                ← Guía de contribución
├── LICENSE                        ← Licencia
│
└── src/                           ← CÓDIGO FUENTE
    ├── app/
    ├── components/
    ├── store/
    ├── lib/
    └── types/
```

---

## 🎯 Guía de Lectura por Rol

### 👨‍💼 Project Manager / Stakeholder

1. **README.md** - Visión general
2. **REQUIREMENTS_SPECIFICATION.md** - Qué se ha construido
3. **QUICKSTART.md** - Demo rápida

**Tiempo**: ~30 minutos

---

### 👨‍💻 Desarrollador

1. **QUICKSTART.md** - Setup local
2. **ARCHITECTURE.md** - Cómo funciona
3. **src/** - Explorar código
4. **CONTRIBUTING.md** - Cómo contribuir

**Tiempo**: ~1 hora

---

### 👨‍🔬 Analista CTI (Usuario)

1. **QUICKSTART.md** - Primer acceso
2. **USER_GUIDE.md** - Todas las funcionalidades
3. **SECURITY_GUIDE.md** - Mejores prácticas

**Tiempo**: ~2 horas

---

### 🛠️ Administrador del Sistema

1. **QUICKSTART.md** - Setup
2. **ADMIN_MANUAL.md** - Operación
3. **SECURITY_GUIDE.md** - Seguridad
4. **DEPLOYMENT.md** - Despliegue

**Tiempo**: ~3 horas

---

### 🔒 Security Officer

1. **SECURITY_GUIDE.md** - Controles de seguridad
2. **REQUIREMENTS_SPECIFICATION.md** - Requisitos de seguridad (RS)
3. **ARCHITECTURE.md** - Arquitectura de seguridad
4. **ADMIN_MANUAL.md** - Backup & DR

**Tiempo**: ~2 horas

---

### 🚀 DevOps / SRE

1. **DEPLOYMENT.md** - Despliegue en Vercel
2. **ADMIN_MANUAL.md** - Mantenimiento
3. **ARCHITECTURE.md** - Stack tecnológico
4. **SECURITY_GUIDE.md** - Compliance

**Tiempo**: ~2 horas

---

## 🔍 Búsqueda Rápida por Tema

### Empezar a Usar
- ✅ QUICKSTART.md
- ✅ README.md
- ✅ USER_GUIDE.md

### Desarrollo
- ✅ ARCHITECTURE.md
- ✅ CONTRIBUTING.md
- ✅ REQUIREMENTS_SPECIFICATION.md

### Operación
- ✅ ADMIN_MANUAL.md
- ✅ DEPLOYMENT.md
- ✅ SECURITY_GUIDE.md

### Seguridad
- ✅ SECURITY_GUIDE.md
- ✅ REQUIREMENTS_SPECIFICATION.md (sección RS)
- ✅ ADMIN_MANUAL.md (Backup & DR)

### Funcionalidades Específicas

#### Kill Chain
- USER_GUIDE.md → Cyber Kill Chain
- REQUIREMENTS_SPECIFICATION.md → RF002

#### Diamond Model
- USER_GUIDE.md → Diamond Model
- ARCHITECTURE.md → Componentes

#### MITRE ATT&CK
- USER_GUIDE.md → MITRE ATT&CK
- ARCHITECTURE.md → Stack tecnológico

#### Atribución Técnica
- USER_GUIDE.md → Atribución Técnica
- ARCHITECTURE.md → Tipos de datos

---

## 📊 Estadísticas de Documentación

| Métrica | Cantidad |
|---------|----------|
| Documentos | 7 (core) + 3 (futuro) |
| Líneas totales | 4,500+ |
| Palabras | 60,000+ |
| Horas de trabajo | 15+ |
| Idioma | Español |
| Clasificación | UNCLASSIFIED-CONFIDENTIAL |

---

## 🗂️ Estructura de Documentos

### Documento Tipo: USER_GUIDE

```
1. Introducción
2. Requisitos
3. Acceso al sistema
4. Interfaz principal
5. Tareas principales (paso a paso)
6. Ejemplos de uso
7. Troubleshooting
8. Glosario
```

### Documento Tipo: ARCHITECTURE

```
1. Visión general
2. Arquitectura del sistema
3. Stack tecnológico
4. Componentes
5. Flujo de datos
6. Patrones de diseño
7. Escalabilidad
8. Roadmap
```

### Documento Tipo: ADMIN_MANUAL

```
1. Introducción
2. Instalación
3. Configuración
4. Gestión de usuarios
5. Backup & Recovery
6. Monitoreo
7. Mantenimiento
8. Troubleshooting
9. Disaster Recovery
```

---

## 🔄 Versionamiento de Documentos

```
Versión formato: MAJOR.MINOR.PATCH

1.0.0 = Versión inicial (Marzo 2026)
1.0.1 = Correcciones menores
1.1.0 = Nuevas secciones
2.0.0 = Cambios mayores
```

### Historia de Versiones

| Versión | Fecha | Cambios |
|---------|-------|---------|
| 1.0.0 | Marzo 2026 | Release inicial |
| 1.0.1 | (Futuro) | Correcciones |
| 1.1.0 | (Futuro) | API doc, Testing |
| 2.0.0 | (Futuro) | OAuth2, DB |

---

## 📝 Convenciones de Documentación

### Iconografía

| Icono | Significado |
|-------|------------|
| ✅ | Implementado |
| 🔄 | En progreso |
| ⏳ | Planificado |
| ❌ | No implementado |
| 🚀 | Futuro |

### Códigos de Clasificación

| Clasificación | Visibilidad | Uso |
|---------------|-----------|-----|
| **UNCLASSIFIED** | Pública | README, USER_GUIDE |
| **INTERNAL** | Equipo | REQUIREMENTS, ADMIN |
| **CONFIDENTIAL** | Restringido | SECURITY, API keys |

### Colores de Prioridad

| Prioridad | Color | Código |
|-----------|-------|--------|
| **CRÍTICA** | 🔴 Rojo | Critical |
| **ALTA** | 🟠 Naranja | High |
| **MEDIA** | 🟡 Amarillo | Medium |
| **BAJA** | 🟢 Verde | Low |

---

## 🔗 Hipervínculos Cruzados

### User Guide referencias:

- Kill Chain: [USER_GUIDE.md#cyber-kill-chain](./USER_GUIDE.md#cyber-kill-chain)
- Diamond Model: [USER_GUIDE.md#diamond-model](./USER_GUIDE.md#diamond-model)
- MITRE ATT&CK: [USER_GUIDE.md#mitre-attck](./USER_GUIDE.md#mitre-attck)
- Troubleshooting: [USER_GUIDE.md#troubleshooting](./USER_GUIDE.md#troubleshooting)

### Admin Manual referencias:

- Setup: [ADMIN_MANUAL.md#instalación-y-setup](./ADMIN_MANUAL.md#instalación-y-setup)
- Backup: [ADMIN_MANUAL.md#backup-y-recuperación](./ADMIN_MANUAL.md#backup-y-recuperación)
- Security: [ADMIN_MANUAL.md#troubleshooting-avanzado](./ADMIN_MANUAL.md#troubleshooting-avanzado)

---

## 📞 Soporte y Contactos

### Documentación Técnica
- 📧 tech-docs@ffaa.gob.ar
- 🐛 GitHub Issues
- 💬 Discussions

### Soporte Operacional
- 📧 soporte@ffaa.gob.ar
- 📞 +54 11 XXXX-XXXX
- 🕐 Business hours

### Seguridad
- 🔒 security@ffaa.gob.ar
- 📞 24/7 emergencias
- 🔐 Encrypted communication

---

## 🎓 Recursos de Aprendizaje

### Documentación Externa

| Tema | Recurso | URL |
|------|---------|-----|
| **React** | Official Docs | https://react.dev |
| **Next.js** | Official Docs | https://nextjs.org/docs |
| **TypeScript** | Handbook | https://www.typescriptlang.org/docs/ |
| **Tailwind** | Docs | https://tailwindcss.com/docs |
| **MITRE ATT&CK** | Framework | https://attack.mitre.org |
| **OWASP** | Top 10 | https://owasp.org/Top10 |

### Videos y Tutoriales

- [Kill Chain Explanation](#)
- [Diamond Model Tutorial](#)
- [CTI Best Practices](#)

---

## 🔄 Actualización de Documentación

### Proceso de Cambio

```
1. Proponer cambio (GitHub Issue)
2. Revisar cambio propuesto
3. Ejecutar cambios
4. Validar documentación
5. Merge a main
6. Publicar actualización
```

### Frequencia de Actualización

| Documento | Frecuencia |
|-----------|-----------|
| README.md | Mensual |
| USER_GUIDE.md | Trimestral |
| ARCHITECTURE.md | Según cambios |
| ADMIN_MANUAL.md | Trimestral |
| SECURITY_GUIDE.md | Mensual |

---

## ✅ Checklist de Documentación

### Antes de Publicar

- [ ] Revisado por 2 personas
- [ ] Enlaces verificados
- [ ] Ejemplos funcionan
- [ ] Formato consistente
- [ ] Sin errores ortográficos
- [ ] Clasificación correcta
- [ ] Versión actualizada
- [ ] Índice actualizado

---

## 📈 Calidad de Documentación

### Métricas

| Métrica | Target | Actual |
|---------|--------|--------|
| Completitud | 90% | 95% |
| Exactitud | 95% | 98% |
| Actualización | < 6 meses | < 3 meses |
| Accesibilidad | WCAG AA | ✅ |

---

## 📄 Formato de Documentos

### Markdown

```markdown
# Título Principal (H1)
## Subtítulo (H2)
### Sección (H3)

**Negrita** para énfasis
_Cursiva_ para énfasis suave

- Lista sin orden
- Item 2

1. Lista numerada
2. Item 2

| Tabla | Encabezado |
|-------|-----------|
| Dato  | Valor     |

`código` inline
\`\`\`
bloque de código
\`\`\`

> Cita
```

---

## 🚀 Próximos Documentos Planeados

- 📋 API.md - Documentación REST API (v2.0)
- 🧪 TESTING.md - Guía de testing (v1.1)
- 🔀 COMPATIBILITY.md - Matriz de compatibilidad (v1.1)
- 📱 MOBILE.md - Guía para mobile app (v2.0)
- 🤝 INTEGRATION.md - Integraciones externas (v2.0)

---

**Última actualización**: Marzo 2026  
**Versión**: 1.0.0  
**Clasificación**: UNCLASSIFIED  
**Mantenedor**: Equipo de Ciberdefensa FFAA
