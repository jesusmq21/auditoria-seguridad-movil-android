# 📱 Auditoría de Seguridad Móvil – Android 14 (Enfoque SOC)

## 👤 Descripción general

Este documento describe una **auditoría completa de seguridad móvil** realizada sobre un **dispositivo Android 14**, aplicando una **metodología de SOC Nivel 1 (Blue Team)**. El objetivo fue evaluar riesgos, identificar malas configuraciones y aplicar medidas preventivas de seguridad.

---

## 🎯 Objetivos

* Evaluar el estado de seguridad de un dispositivo Android
* Identificar posibles indicadores de compromiso (IOC)
* Reducir la superficie de ataque y el rastreo
* Aplicar buenas prácticas de hardening
* Documentar la experiencia como práctica real en ciberseguridad

---

## 🧩 Alcance

* Configuración del sistema Android
* Inventario de aplicaciones instaladas
* Gestión de permisos
* Conectividad y red
* Aplicaciones de mensajería (WhatsApp y Telegram)
* Privacidad y control de rastreo

---

## 🔍 Fase 1 – Evaluación del sistema

* **Versión del sistema:** Android 14
* **Parche de seguridad:** 1 de diciembre de 2025
* **Hallazgo:** Parche ligeramente desactualizado (~45 días)
* **Nivel de riesgo:** Medio (controlado)

---

## 📦 Fase 2 – Inventario de aplicaciones

Acciones realizadas:

* Revisión de todas las aplicaciones instaladas
* Identificación de apps innecesarias o sin uso
* Verificación de paquetes sospechosos o desconocidos

**Resultado:**

* No se detectaron aplicaciones maliciosas o desconocidas
* Inventario limpio

---

## 🔑 Fase 3 – Auditoría de permisos

Permisos críticos revisados:

* Micrófono
* Cámara
* Ubicación
* Archivos y medios
* SMS

**Resultado:**

* Permisos correctamente asignados
* No se detectaron accesos excesivos o abusivos

---

## 🦠 Fase 4 – Análisis de comportamiento

Indicadores evaluados:

* Publicidad inesperada
* Consumo anómalo de batería
* Sobrecalentamiento del dispositivo
* Uso excesivo de datos móviles

**Resultado:**

* No se detectó comportamiento anómalo
* Sin indicios de malware, spyware o adware

---

## 🛡️ Fase 5 – Hardening avanzado

### Seguridad DNS

* Configuración de **DNS privado** para bloquear dominios maliciosos

### Privacidad y rastreo

* Eliminación del ID de publicidad
* Restricción de accesos en segundo plano
* Ubicación configurada como "solo mientras se usa la app"

### Conectividad

* Bluetooth desactivado cuando no se utiliza
* Eliminación de redes Wi-Fi antiguas
* Conexión automática deshabilitada

---

## 💬 Fase 6 – Auditoría de aplicaciones de mensajería

### WhatsApp

* Revisión de dispositivos vinculados
* Verificación en dos pasos activada
* Copias de seguridad cifradas de extremo a extremo
* Descargas automáticas deshabilitadas

### Telegram

* Revisión de sesiones activas
* Verificación en dos pasos habilitada
* Configuración de privacidad restringida
* Descargas automáticas deshabilitadas

**Resultado:**

* No se detectaron sesiones no autorizadas
* Configuración segura aplicada

---

## 📊 Evaluación final de riesgos

| Área         | Estado        |
| ------------ | ------------- |
| Sistema      | 🟡 Controlado |
| Aplicaciones | 🟢 Seguro     |
| Permisos     | 🟢 Seguro     |
| Mensajería   | 🟢 Seguro     |
| Red          | 🟢 Endurecido |

**Nivel de riesgo general:** 🟢 **BAJO**

---

## 🧠 Aprendizajes SOC

* Los dispositivos móviles son endpoints críticos
* El hardening preventivo reduce la probabilidad de incidentes
* Las auditorías periódicas mejoran la postura de seguridad
* El enfoque replica tareas reales de un SOC Nivel 1

---

## 📌 Habilidades demostradas

* Auditoría de seguridad
* Evaluación de riesgos
* Hardening de endpoints
* Conciencia en seguridad móvil
* Documentación técnica

---

## 📅 Recomendaciones

* Mantener el sistema actualizado mensualmente
* Revisar permisos cada 60 días
* Evitar la instalación de apps desde fuentes desconocidas
* Repetir la auditoría tras actualizaciones mayores

---

## 🏁 Conclusión

El dispositivo Android evaluado se encuentra **seguro, endurecido y con bajo nivel de riesgo**. Esta auditoría demuestra habilidades prácticas de Blue Team aplicables a un **rol de Analista SOC Nivel 1**.
