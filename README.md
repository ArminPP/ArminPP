# Welcome to my GitHub Profile! 🚀

<table width="100%">
<thead>
  <tr>
    <th width="50%">Deutsch</th>
    <th width="50%">English</th>
  </tr>
</thead>
<tbody>

<!-- SECTION 1: ABOUT ME -->
<tr>
<td>

## 👤 Über mich

Hallo! Ich bin Armin Pressler. Auf meiner offiziellen Webseite [armin-pressler.at](https://www.armin-pressler.at/) dokumentiere ich meine vielseitigen Leidenschaften an der Schnittstelle von Technik, Wissenschaft und Kunst. 

Meine Hauptbereiche umfassen:
*   **[Astrofotografie & Astronomie](https://www.armin-pressler.at/):** Deep-Sky-Aufnahmen, Planetenbeobachtung und der Bau eigener Sternenwarten.
*   **[Fine-Art Photographie](https://www.armin-pressler.at/):** Studioarbeiten, Aktfotografie, Porträts sowie gedruckte Bildbände.
*   **[Oldtimer & Reisen](https://www.armin-pressler.at/):** Ausgedehnte Roadtrips und leidenschaftliches Schrauben an meinem Triumph Spitfire MKIV.

Als Entwickler verbinde ich diese Hobbys mit maßgeschneiderter Hardware, um komplexe Probleme elegant zu lösen.

</td>
<td>

## 👤 About Me

Hello! I am Armin Pressler. On my official website [armin-pressler.at](https://www.armin-pressler.at/), I document my diverse passions at the intersection of technology, science, and art.

My core interests include:
*   **[Astrophotography & Astronomy](https://www.armin-pressler.at/):** Deep-sky imaging, planetary observation, and observatory construction.
*   **[Fine-Art Photography](https://www.armin-pressler.at/):** Studio work, fine art nudes, portraits, and published photo books.
*   **[Classic Cars & Travel](https://www.armin-pressler.at/):** Extended road trips and hands-on restoration of my Triumph Spitfire MKIV.

As a developer, I merge these hobbies with custom hardware to solve complex challenges elegantly.

</td>
</tr>
</tbody>
</table>
<!-- SECTION 2: INTRODUCTION TO UNPINNED PROJECTS -->

## 🛠️ Weitere Projekte (Aktuell in Entwicklung / Current Projects in Development)
_Aus Platzgründen nicht angepinnt, aber aktiv betreut • Not pinned due to space limitations but actively developed_

<table width="100%">
<tbody>

<!-- PROJECT A: STEPPERFOCUS32 -->
<tr>
<td>
### 🌌 a) StepperFocus32
Ein simpler, extrem zuverlässiger und **Moonlite-kompatibler Teleskop-Fokussierer**.

*   **Hardware:** ESP32, DRV8833 H-Brücke (Adafruit/China-Module), Nema17 Schrittmotor (ca. 30 Ohm Phasenwiderstand, z.B. Adafruit #324).
*   **Spezifikationen:** Reine Voll- und Halbschritt-Modi. Betrieb an maximal 9VDC (max. 10VDC) Arduino-Netzteilen, um den DRV8833 zu schützen.
*   **Besonderheit:** Der Motor zieht bei 9V ca. 300mA und bleibt nach Erreichen der Zielposition absichtlich bestromt (**elektronische Bremse**). Das hält den Fokus stabil, ohne den Treiber bei passendem Motorwiderstand zu überhitzen.
*   **Firmware-Ziele:** Serielle ASCII-Schnittstelle (kompatibel mit MoonLite ASCOM), nicht-blockierende Motorbewegung, Persistenz aller Parameter im ESP32-NVS (Preferences). Bewusst schlank ohne Sensoren gehalten.

</td>
<td>
### 🌌 a) StepperFocus32
A simple, highly reliable, and **Moonlite-compatible telescope focuser**.

*   **Hardware:** ESP32, DRV8833 H-bridge (Adafruit/China modules), Nema17 stepper motor (~30 Ohm phase resistance, e.g., Adafruit #324).
*   **Specifications:** Supports full and half-step modes only. Must be powered by a max. 9VDC (max. 10VDC) power supply to protect the DRV8833.
*   **Special Feature:** The motor draws ~300mA at 9V and remains energized after reaching the target position (**electronic brake**). This maintains focus holding torque without overheating matching resistance motors.
*   **Firmware Goals:** Serial ASCII interface (compatible with MoonLite ASCOM), non-blocking motor movement, parameter persistence in ESP32-NVS (Preferences). Intentionally sleek without extra sensors.

</td>
</tr>

<!-- PROJECT B: BOILER -->
<tr>
<td>

### 🚰 b) Boiler-Steuerung
Eine intelligente Steuerung für Warmwasserboiler zur Effizienzsteigerung und Hygieneüberwachung.

*   **Hardware:** M5Stack Core2 Modul, Relais-Einheit, DS18B20 Temperatursensor.
*   **Interface:** Intuitive Bedienung direkt über das farbige Core2-Touchdisplay oder ein komfortables Webfrontend im lokalen Netzwerk.
*   **Sicherheit:** Integrierte **Legionellenautomatik** zur automatischen, thermischen Desinfektion in zyklischen Abständen.

</td>
<td>

### 🚰 b) Smart Boiler Control
An intelligent hot water boiler controller designed for energy efficiency and hygiene monitoring.

*   **Hardware:** M5Stack Core2 module, relay unit, DS18B20 temperature sensor.
*   **Interface:** Intuitive operation directly via the integrated Core2 touch display or a convenient local network web frontend.
*   **Safety:** Integrated **automated Legionella protection** for periodic thermal disinfection cycles.

</td>
</tr>

<!-- PROJECT C: CCDS -->
<tr>
<td>

### 🏎️ c) CCDS - ClassicCarDiagnosticSystem
Ein maßgeschneidertes Telemetrie- und Protokollierungssystem für Oldtimer (wie den Triumph Spitfire).

*   **Hardware:** Verteilte Systeme basierend auf verschiedenen ESP32-Schnittstellen.
*   **Sensorik:** Überwachung aller vitalen Motorkenngrößen in Echtzeit.
*   **Erfasste Werte:** Air-Fuel-Ratio (AFR / Lambda), Öldruck, Motordrehzahl (RPM), Fahrzeuggeschwindigkeit, Öltemperatur, Drosselklappenstellung (TPS) sowie Drosselklappendruck (MAP).

</td>
<td>

### 🏎️ c) CCDS - ClassicCarDiagnosticSystem
A custom telemetry and data-logging ecosystem tailored for classic cars (like the Triumph Spitfire).

*   **Hardware:** Distributed networks built upon various ESP32 microcontrollers.
*   **Sensors:** Real-time monitoring of all vital engine health parameters.
*   **Logged Metrics:** Air-Fuel-Ratio (AFR / Lambda), oil pressure, RPM, vehicle speed, oil temperature, throttle position (TPS), and manifold absolute pressure (MAP).

</td>
</tr>

<!-- PROJECT D: VIBRATION SENSOR INTRODUCTION -->
<tr>
<td>

### 🏭 d) Ultra-Low-Cost Schwingungssensor
Ein industrieller Plug-and-Play-Sensor für die **vorausschauende Wartung (Predictive Maintenance)** in einem kompakten Gehäuse. Er berechnet alle relevanten Kennwerte zur Schwingungsanalyse direkt auf dem Edge-Device für **drei Achsen (X, Y, Z)** zeitgleich:


| Kennwert | Beschreibung |
| :--- | :--- |
| **RMS-Beschleunigung [g]** | Gesamte Vibrationsstärke |
| **RMS-Geschwindigkeit [mm/s]** | Schwinggeschwindigkeit (ISO 10816) |
| **Crest-Faktor** | Verhältnis Spitze/Mittelwert (Stöße) |
| **Envelope Crest** | Hüllkurven-Crest für frühe Lagerschäden |
| **Kurtosis** | Verteilungssteilheit (Schlagimpulse) |
| **K(t)-Faktor** | Kombiniert Beschleunigung & Crest |
| **Peak-to-Peak [g]** | Gesamter Schwingungsausschlag |
| **Trend [%]** | Abweichung zum letzten Messwert |
| **Temperatur [°C]** | Interne Sensortemperatur |

</td>
<td>

### 🏭 d) Ultra-Low-Cost Vibration Sensor
An industrial plug-and-play sensor for **predictive maintenance** packed into a minimal footprint housing. It computes all critical vibration analysis metrics directly on the edge device for **three axes (X, Y, Z)** simultaneously:


| Metric | Description |
| :--- | :--- |
| **RMS Acceleration [g]** | Total vibration magnitude |
| **RMS Velocity [mm/s]** | Vibration speed (ISO 10816) |
| **Crest Factor** | Peak-to-average ratio (shocks) |
| **Envelope Crest** | Demodulated crest for early bearing faults |
| **Kurtosis** | Distribution sharpness (impulse shocks) |
| **K(t)-Factor** | Combines acceleration & crest |
| **Peak-to-Peak [g]** | Total displacement envelope |
| **Trend [%]** | Deviation from previous reading |
| **Temperature [°C]** | Internal sensor temperature |

</td>
</tr>

<!-- PROJECT D: TRAFFIC LIGHTS -->
<tr>
<td>

#### 🚦 Ampelbewertung nach ISO 10816
Ein intelligentes Ampelsystem aggregiert und bewertet fünf Messgrößen simultan (*RMS-Geschwindigkeit gemäß Klasse 1–4, Kurtosis, Crest-Faktor, KZI-Verhältnis aus Gyro/Beschleunigung, Temperatur*):

*   🟢 **Grün** = Zone A (In Ordnung, Neuzustand)
*   🟡 **Gelb** = Zone B (Dauerbetrieb noch zulässig)
*   🟠 **Orange** = Zone C (Eingeschränkter Betrieb)
*   🔴 **Rot** = Zone D (Gefahr! Sofortiger Stopp!)

</td>
<td>

#### 🚦 Traffic Light Evaluation (ISO 10816)
An intelligent status system aggregates and evaluates five metrics simultaneously (*RMS velocity based on Class 1–4, Kurtosis, Crest factor, KZI ratio from gyro/acceleration, temperature*):

*   🟢 **Green** = Zone A (Good condition, like new)
*   🟡 **Yellow** = Zone B (Continuous operation permissible)
*   🟠 **Orange** = Zone C (Intermittent operation only)
*   🔴 **Red** = Zone D (Danger! Immediate action required!)

</td>
</tr>

<!-- PROJECT D: DETAILED ANALYSIS -->
<tr>
<td>

#### 📈 Detaillierte Frequenzanalyse
Das Webinterface bietet eine tiefe Signalanalyse über **sieben umschaltbare Diagramm-Tabs**:

*   **Acc / Vel / Disp:** Zeitsignale für Beschleunigung, Geschwindigkeit ($mm/s$) und Auslenkung ($\mu m$).
*   **Orbit:** 2D-Kreisbahn zur Darstellung von Wellenbewegungen.
*   **FFT / Env:** Beschleunigungs-FFT und Hüllkurven-FFT zur Lokalisierung von Lagerschäden.
*   **VFFT:** Geschwindigkeits-FFT in $mm/s$ mit integrierten **Drehzahl-Markern** ($1x, 2x, 3x$ zur Unwuchterkennung), **Seitenband-Analysen** (Getriebediagnose) und **Harmonischen-Markern**.

</td>
<td>

#### 📈 Detailed Frequency Analysis
The integrated web interface offers deep signal analytics across **seven switchable chart tabs**:

*   **Acc / Vel / Disp:** Time-domain graphs for acceleration, velocity ($mm/s$), and displacement ($\mu m$).
*   **Orbit:** 2D orbital plots visualizing shaft movement patterns.
*   **FFT / Env:** Acceleration FFT and Envelope FFT to isolate localized bearing defects.
*   **VFFT:** Velocity FFT ($mm/s$) equipped with **RPM markers** ($1x, 2x, 3x$ for imbalance detection), **sideband analysis** (gearbox diagnostics), and **harmonic markers**.

</td>
</tr>

<!-- PROJECT D: CONTROLS & JOURNAL -->
<tr>
<td>

#### ⚙️ Sensor-Steuerung & Journal
*   **Messungskontrolle:** Start/Stop-Trigger, konfigurierbare Messzyklen (inkl. "ständig" für Dauerbetrieb) und einstellbare Pausenzeiten.
*   **Administration:** OTA-Firmware-Updates direkt per Datei-Upload im Browser, Remote-Neustart, Konfigurations-Backups (Speichern/Laden) und Passwortschutz (verschlüsselt via *CryptoJS*).
*   **Meldungs-Journal:** Lückenlose System-Log-Liste zur unkomplizierten Fehlersuche im Live-Betrieb.

</td>
<td>

#### ⚙️ Sensor Control & Diagnostics Journal
*   **Measurement Tweaks:** Start/Stop triggers, customizable iteration cycles (including continuous mode), and pause intervals.
*   **Admin Tools:** Local browser OTA firmware updates via file upload, remote reboot, configuration backup/restore, and encrypted password protection (via *CryptoJS*).
*   **Message Journal:** Continuous system log streams for straightforward live debugging and device tracking.

</td>
</tr>

</tbody>
</table>

---
_Feel free to explore my repositories. Let's build something great! 🛠️_
