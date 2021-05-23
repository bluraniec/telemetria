![Intro](/readme/main.png)
# O sesji
Celem tego warsztatu jest ukazanie przykładu zastosowania telemetrii opartej na modelach danych (ang. Model-Driven Telemetry) stosowanej m.in. do monitorowania sąsiedztw protokołu BGP (BGP Neighborship). W stabilnym środowisku, sąsiedztwa BGP nie powinny być niestabilne (flapping). Częste zmiany stanu mogą wskazywać na problem ze sprzętem, oprogramowaniem, okablowaiem lub konfiguracją urządzenia sieciowego. Chcemy monitorować te niestabilności. Możesz następnie skorzystać z tej informacji w celu wyłączenia sąsiedztwa w przypadku powtórzonego alarmu.  
<img align="center" width=90% src="/readme/topo.png"></img>

Po ukończeniu tego warsztatu, będziesz potrafić:
- Skonfigurować telemetrię opartą na modelach danych, na urządzeniach Cisco IOS-XR
- Odbierać strumienie danych z urządzeń sieciowych przy pomocy kolektora Pipeline
- Przechowywać odebrane dane w bazie danych, takiej jak InfluxDB
- Wizualizować dane w czasie rzeczywistym przy pomocy narzędzia Grafana

# Wprowadzenie
Telemetria oparta na modelach danych (MDT) pozwala na pomiary niemal w czasie rzeczywistym danych operacyjnych z urządzeń sieciowych. Wykonywanie zaawansowanego monitoringu może także wywołać zmianę konfiguracji, która zwykle wymaga udziału człowieka. Podczas sesji zostanie opisana architektura platformy analitycznej co powinno dać dobry punkt startowy w celu dalszego eksperymentowania z telemetrią. Wdrażanie rozwiązań MDT oferuje firmom możliwość na redukcję kosztów związanych z utrzymywaniem wielkich oddziałów IT i możliwość alokacji zasobów ludzkich bardziej strategicznie, redukując godziny spędzone na wykonywaniu pracy reaktywnej i skupianiu się na bardziej proaktywnych czynnościach.

Warsztat ten demonstruje jak telemetria strumieniowa może być stosowana w środowisku z urządzeniami Cisco IOS-XR. Uczestnicy będą mieli możliwość zbierania danych z urządzeń, analizowania ich i wizualizowania w czasie niemal rzeczywistym przy użyciu narzędzi typu open-source.

# Wymagania wstępne
- Podstawy języka SQL
- Podstawy systemu operacyjnego Linux

<h4 align="center">[1/6]</h4>
<h4 align="center"> <a href="/readme/theory.md"> Trochę teorii! :arrow_right: </a> </h4>
