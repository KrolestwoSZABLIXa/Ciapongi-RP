<p align="center">
  <img src="https://ciapongi.szablix.pl/server-icon.png" width="128" height="128" alt="Ciapongi Logo">
</p>

# <p align="center">Ciapongi Modpack Repository</p>

<p align="center">
  <img src="https://img.shields.io/badge/Minecraft-1.20.1-blue?style=flat-square&logo=minecraft" alt="Minecraft Version">
  <img src="https://img.shields.io/badge/Status-Maintained-green?style=flat-square" alt="Status">
  <img src="https://img.shields.io/badge/Update_System-Granular-orange?style=flat-square" alt="Update System">
</p>

---

To repozytorium służy jako centralny serwer plików dla paczki modyfikacji serwera **Ciapongi**. 

### 🚂 Co tu się znajduje?
*   **`/mods`**: Zbiór wszystkich modyfikacji (`.jar`) wymaganych do gry.
*   **`/resourcepacks`**: Oficjalne paczki zasobów serwerowych.
*   **`manifest.json`**: Automatycznie generowany indeks plików, używany przez **Ciapongi Updater** do inteligentnej synchronizacji (delta updates).

### 🚀 Jak to działa?
Repozytorium korzysta z **GitHub Actions**, które przy każdej zmianie w plikach aktualizuje manifest. Dzięki temu gracze pobierają tylko te elementy, które faktycznie uległy zmianie, oszczędzając czas i transfer.

---
*Strona serwera: [ciapongi.szablix.pl](https://ciapongi.szablix.pl)*
