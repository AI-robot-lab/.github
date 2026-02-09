## Opis zmian
*Krótki opis tego, co wprowadza ten PR (np. "Implementacja modułu planowania trajektorii dla misji ładowania").*

**Powiązane zadania (Issues):**
- Fixes # (id zadania)
- Relates to # (id zadania)

---

## Typ zmiany
- [ ] Nowa funkcjonalność (feature)
- [ ] Naprawa błędu (bug fix)
- [ ] Refaktoryzacja / Optymalizacja
- [ ] Dokumentacja
- [ ] Zmiany w infrastrukturze / CI/CD

---

## Testowanie i Walidacja

### Środowisko testowe:
- [ ] **Symulacja:** (Gazebo / MuJoCo) - *Opisz scenariusz testowy*
- [ ] **Hardware:** (Unitree G1 / Inny) - *Czy testowano na fizycznym robocie?*

### Wyniki:
*Wklej logi, screenshoty z Rviz lub linki do nagrań z testów, jeśli to możliwe.*

---

## Checklist Jakości AI Robot Lab

### Standardy Kodu:
- [ ] **Python:** Kod zgodny z PEP8 (flake8/black).
- [ ] **C++:** Kod zgodny z Google Style Guide.
- [ ] **ROS 2:** Nazewnictwo nodów, tematów (topics) i parametrów jest spójne z konwencją projektu.
- [ ] **Dokumentacja:** Zaktualizowano README / komentarze w kodzie (Doxygen/Docstrings).

### Bezpieczeństwo i Integracja:
- [ ] **Safety:** Zmiana nie wpływa negatywnie na działanie E-Stopu i systemów bezpieczeństwa.
- [ ] **Git Flow:** PR kierowany do gałęzi `develop` (nie `main`).
- [ ] **Dependencies:** Dodano nowe zależności do `package.xml` / `requirements.txt` (jeśli dotyczy).

---

## Uwagi dla recenzenta
*Na co recenzent powinien zwrócić szczególną uwagę? Czy są jakieś "brudne" hacki, które wymagają docelowej poprawy?*
