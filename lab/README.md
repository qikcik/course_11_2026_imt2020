# Laby

Każdy lab ma własny katalog `labN`:

| Element | Zawartość |
|---|---|
| `commands.txt` | Polecenia w kolejności wykonania, z opisem terminali |
| `config/` | Konfiguracje gNB, UE i innych narzędzi, pliki serwera testowego |
| `current/` | Wszystko, co powstaje przy uruchomieniu labu: `pcap/`, `log/`, `core_config/`, `core_log/` |
| `recording/` | Zapis referencyjny: ten sam układ co `current/` |
| `docs/` | Wyciągi ze specyfikacji, jeśli lab ich używa |

Polecenia uruchamia się z katalogu labu (`cd ~/5gs/repo/lab/labN`). Wynik własnego uruchomienia trafia do `current/`; `recording/` służy do porównania.

`lab0` opisuje środowisko: zawartość `~/5gs`, profil Wiresharka, abonenta w WebUI i sprawdzenie zestawu.
