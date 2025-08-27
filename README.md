# 🛒 ComparaYa — Proyecto Capstone (DUOC UC)
Repositorio oficial de **documentación** del proyecto **ComparaYa**, una plataforma para analizar la evolución histórica de precios de alimentos (datos oficiales ODEPA) y **comparar precios actuales** de supermercados en Chile.

> **Carrera:** Ingeniería en Informática — **Sede:** Padre Alonso de Ovalle.

## 👥 Equipo
- **Italo Navarrete**  
- **Gustavo Cartes**  
- **Daniel Stari**

---

## 🧭 Descripción breve
**ComparaYa** integra dos mundos:
1) **Histórico ODEPA**: consolida y visualiza series de precios mayoristas/minoristas con dashboards.  
2) **Actual Supermercados**: módulo complementario de scraping para consultar y comparar precios vigentes (canasta básica y productos).

**Stack base (prototipo):** Backend **Django** + **SQLite** para ODEPA, con gráficos interactivos; scraping a supermercados como módulo complementario.

---

## 🎯 Objetivo general
**Desarrollar una plataforma web** que permita analizar la evolución histórica de precios de alimentos en Chile (datos ODEPA) y, **como complemento**, mostrar precios actuales de supermercados para **comparar productos y canastas**.
### Objetivos específicos
- Implementar la **ingesta y procesamiento** de datos ODEPA (CSV).  
- **Normalizar y limpiar** datos para análisis claro.  
- Diseñar **dashboards** con tendencias y brechas de precios oficiales.  
- Desarrollar **scraping** para precios actuales de supermercados.  
- Implementar **comparación** de productos y **cálculo de canasta básica** por supermercado.  
- **Desplegar** en servidor con Apache/Django. 
---

## 🧩 Alcance y valor
- Resuelve la **dispersión** de información entre ODEPA y portales de supermercados.  
- Entrega **análisis claro** para consumidores, pymes e instituciones. 

---

## 🛠️ Tecnologías y herramientas
- **Backend / Datos:** Python, Django, Django REST Framework, Pandas, SQLite.  
- **Scraping:** Selenium / BeautifulSoup.  
- **Front / Visualización:** (prototipo) Django/React, JS/CSS, dashboards interactivos. 
---

## 🗂️ Estructura del repositorio
> Este repo está enfocado en **documentación**. Cualquier PoC o snippet irá aparte.

