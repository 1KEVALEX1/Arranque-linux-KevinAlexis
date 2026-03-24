# Bitácora de arranque — Kevin Alexis

**Fecha:** 23/03/2026
**Duración estimada:** 2 horas

---

## Pasos ejecutados

1. `pwd` → mostró mi ruta actual: /home/kevin
2. `ls -lah` → listé los archivos del directorio, incluyendo ocultos
3. `git clone https://github.com/1KEVALEX1/Arranque-linux-KevinAlexis` → cloné el repositorio
4. `cd Arranque-linux-KevinAlexis` → entré al proyecto
5. `touch README.md` → creé el archivo README
6. `nano README.md` → edité el archivo agregando mi usuario y color favorito
7. `git checkout -b semana2-arranque` → creé y cambié a una nueva rama
8. `git add .` → agregué los archivos al área de preparación
9. `git commit -m "docs: agrega username y color favorito al README"` → guardé los cambios
10. `git push origin semana2-arranque` → subí los cambios al repositorio remoto

---

## Comandos destacados

| Comando      | Qué hace                          |
| ------------ | --------------------------------- |
| `pwd`        | Mostró la ruta actual             |
| `ls -lah`    | Listó archivos incluyendo ocultos |
| `git status` | Mostró el estado del repositorio  |
| `git add .`  | Preparó archivos para commit      |
| `git push`   | Subió cambios a GitHub            |

---

## Problemas encontrados

* **Problema 1:** No podía hacer commit porque el archivo aparecía como "untracked"
  **Solución:** Usé `git add .` para agregarlo al staging

* **Problema 2:** Error al usar `git commit -m` sin mensaje
  **Solución:** Agregué un mensaje correcto dentro de comillas

* **Problema 3:** Error 403 al hacer push
  **Solución:** Generé un Personal Access Token en GitHub con permisos `repo` y lo usé como contraseña

---

## Resultado de git log --oneline

c8a4849 (HEAD -> semana2-arranque, origin/semana2-arranque) docs: agrega username y color favorito al README

