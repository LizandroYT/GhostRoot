# GhostRoot

<div align="center">
  <a href="https://github.com/LizandroYT"><img title="Author" src="https://img.shields.io/badge/Author-Lizandro%20YT-blue?style=for-the-badge&logo=github"></a>
  <a href="#"><img title="Version" src="https://img.shields.io/badge/Version-Beta-green.svg?style=flat-square"></a>
  <a href="https://github.com/LizandroYT/GhostRoot/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/LizandroYT/GhostRoot?color=red&style=flat-square"></a>
  <a href="https://github.com/LizandroYT/GhostRoot/network/members"><img title="Forks" src="https://img.shields.io/github/forks/LizandroYT/GhostRoot?color=red&style=flat-square"></a>
  <a href="https://github.com/LizandroYT/GhostRoot/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/LizandroYT/GhostRoot?label=Watchers&color=blue&style=flat-square"></a>
</div>

---

## ¿Qué es GhostRoot?  

**GhostRoot** es una herramienta que utiliza [proot](https://proot-me.github.io/) para simular privilegios de root en sistemas donde no se tiene acceso real a root. Solo debes escribir la palabra clave `root` para activar el acceso simulado.

---

## Instalación

```bash
apt update && apt -y upgrade
pkg install -y git proot
termux-setup-storage
git clone https://github.com/LizandroYT/GhostRoot.git
cd GhostRoot
bash install.sh
./start
```

---

## Uso

- Para activar los privilegios root, simplemente escribe la palabra `root`.
- Cuando el prompt de tu terminal cambie de `$` a `#`, el modo root estará activo.
- Para salir del modo root, solo escribe `exit`.

---

## Notas

- **GhostRoot** está pensado para entornos como Termux.
- No otorga privilegios root reales, solo simula el entorno para facilitar pruebas y desarrollo.
- Usa bajo tu propio riesgo.

---

## Créditos

- Autor: [Lizandro YT](https://github.com/LizandroYT)

---
