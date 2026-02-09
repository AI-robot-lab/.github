#  Laboratorium zastosowań AI i robotów humanoidalnych

Witaj w centrum dowodzenia **AI Robot Lab**.
Jesteśmy interdyscyplinarnym zespołem badawczym skupionym na dwóch filarach: **autonomicznym przemieszczaniu się robotów humanoidalnych** oraz **robotyce afektywnej (HRI)**. Naszym celem jest tworzenie maszyn, które nie tylko sprawnie poruszają się w ludzkim środowisku, ale także potrafią wchodzić w naturalne, empatyczne interakcje społeczne.

> **Widoczność:** Ta strona i przypięte repozytoria są widoczne tylko dla członków organizacji. Prosimy o nieudostępnianie kodu źródłowego (szczególnie modułów *proprietary*) na zewnątrz bez zgody PI (Principal Investigator).

---

## Główne Obszary Badawcze

### 1. Humanoid Locomotion & Manipulation
Programowanie robotów humanoidalnych pod kątem autonomii i precyzji.
*   **Platformy:** Unitree G1 EDU,.
*   **Stack technologiczny:** ROS 2 (Humble/Jazzy), C++, Python, Gazebo/MuJoCo.
*   **Kluczowe zagadnienia:**
    *   Planowanie ruchu całego ciała (Whole-Body Control).
    *   Manipulacja precyzyjna (np. podłączanie ładowarek EV).
    *   Nawigacja w nieustrukturyzowanym środowisku.

### 2. Affective Robotics & HRI
Tworzenie systemów, które rozpoznają i symulują ludzkie emocje.
*   **Technologie:** Computer Vision (Facial Action Coding System), LLMs (Large Language Models), Synteza mowy.
*   **Kluczowe zagadnienia:**
    *   Wykrywanie stanu emocjonalnego użytkownika w czasie rzeczywistym.
    *   Generowanie gestów i mimiki robota (Non-verbal communication).
    *   Etyka w interakcji człowiek-robot.

---

## Getting Started (onboarding)

Jeśli jesteś nowym członkiem zespołu, wykonaj te kroki:

1.  **Konfiguracja środowiska:**
    *   Zainstaluj **Ubuntu 22.04 / 24.04**.
    *   Skonfiguruj **ROS 2** zgodnie z [Instrukcją Wewnętrzną](link_do_wiki_lub_pliku).
    *   Upewnij się, że masz dostęp do VPN laboratorium (dla zdalnego dostępu do robotów) \\ kiedyś.

2.  **Dostęp do sprzętu:**
    *   Zapoznaj się z procedurą **E-Stop** (wyłącznika bezpieczeństwa) przed uruchomieniem jakiegokolwiek fizycznego robota.
    *   Rezerwuj czas pracy z robotem Unitree G1 w kalendarzu zespołu \\ kiedyś.

3.  **Standardy kodu:**
    *   Używamy **Git Flow** (gałęzie `feature/`, Pull Requests do `develop`/`main`).
    *   Każdy PR musi przejść przez **Code Review** przynajmniej jednej osoby.
    *   Przestrzegamy standardów PEP8 (Python) i Google Style Guide (C++).

---

## Kluczowe Repozytoria

| Repozytorium | Opis | Status |
| :--- | :--- | :--- |
| **[`unitree-g1-charging-mission`](/AI-robot-lab/unitree-g1-charging-mission)** | Autonomiczne ładowanie EV przez robota G1. Projekt flagowy. | Active |
| **[`affective-core`](/AI-robot-lab/affective-core)** | Biblioteka do analizy emocji z twarzy. | Active |
| **[`lab-simulation-env`](/AI-robot-lab/lab-simulation-env)** | Światy Gazebo/MuJoCo odwzorowujące nasze fizyczne laboratorium. | Active |
| **[`ros2-utils`](/AI-robot-lab/ros2-utils)** | Wspólne narzędzia, skrypty i pliki konfiguracyjne Docker. | Active |

---

## Komunikacja i Wsparcie

*   **Teams/Slack/Discord:** `#general` (ogłoszenia), `#dev-humanoid` (problemy z Unitree), `#dev-affective` (AI/Vision).
*   **Weekly Stand-up:** Piątki, 15:00 (SD.109 / Teams).
*   **Zgłaszanie awarii:** Jeśli uszkodzisz sprzęt – **zgłoś to natychmiast** na kanale `#hardware-issues`. Nie ukrywamy błędów, naprawiamy je!

---

*"Building robots that move like us and feel with us."*
