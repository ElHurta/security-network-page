<h1 align=center>Proyecto de Seguridad de la Información en Redes de Comunicación</h1>

<p align=center>Este proyecto tiene como objetivo diseñar e implementar una propuesta de montaje de una red de comunicaciones con seguridad lógica y física, aplicando el modelo CIA (Confidencialidad, Integridad, Disponibilidad) y algoritmos de encriptación robustos como AES y RSA.</p>

<p align=center>Realizado por Juan Hurtado y David Ravelo</p>

<p align=center>Si encuentras este proyecto útil, por favor dale una ⭐ para mostrar tu apoyo.</p>

<h2 align="center"> <a target="_blank" href="https://tu-url-de-demo.com">👀 Demo</a></h2>

<p align=center>
  <a href="https://github.com/withastro/astro/releases/tag/astro%404.3.2" alt="Contributors">
    <img src="https://img.shields.io/static/v1?label=ASTRO&message=4.3&color=000&logo=astro" />
  </a>

  <img src="https://img.shields.io/github/languages/code-size/ElHurta/security-network-page" alt="code size">
</p>

## 📌 Características Clave

- 🔒 Aplicación del modelo CIA (Confidencialidad, Integridad, Disponibilidad)
- 🔐 Uso de algoritmos de encriptación robustos (AES y RSA)
- 🌐 Diseño e implementación de seguridad en redes WAN y LAN
- 🛡️ Identificación y mitigación de amenazas y riesgos específicos

## 🚀 Comenzando

### 📦 Dependencias

- astro 4.0+
- node v20.10+
- npm v10.2+
- tailwind v3.3+

### 👉 Instalar Dependencias

```bash
npm install
```

### 👉 Comando de Desarrollo

```bash
npm run dev
```

### 👉 Comando de Build

```bash
npm run build
```

### 👉 Build y Ejecutar con Docker

```bash
docker build -t proyecto-seguridad .
docker run -p 3000:80 proyecto-seguridad
```

Para acceder a la shell dentro del contenedor:

```bash
docker run -it --rm proyecto-seguridad ash
```