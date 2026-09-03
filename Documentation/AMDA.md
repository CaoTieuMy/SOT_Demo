# AMDA

| Field | Details |
|---|---|
| Created | 2026/09/03 |
| Last Reviewed | 2026/09/03 |
| Author | Tieu My |

## General Information

| Field | Details |
|---|---|
| **Project Name** | AMDA |
| **Project Owner, Co-Owner** | Andrea Patelli, OFFEN |
| **Customer** | VW |
| **Visibility** | no |
| **Industry** | Automotive |
| **Topic / Area** | Monitoring and Observability |
| **From** | Nov 2022 |
| **To** | Mar 2025 |

---

## Project Insights
> Laufendes DevOps-Projekt für Custom Application Monitoring von Workloads auf einer Big-Data-Plattform basierend auf OpenShift. Ziel war die Verbesserung des Entwicklungs- und Deployment-Prozesses für Monitoring, Alerting und Visualisierung von Metrics und Logs zur Effizienzsteigerung des Monitoring-Teams. Die Lösung wurde für 3 produktive Anwendungen der Data Analytics Platform ausgerollt; weitere Rollouts laufen oder sind geplant.

## Business Needs

#### 1. Transparenz und frühzeitige Fehlererkennung
Im Projektkontext war immer wieder zu spüren, dass wir mehr Transparenz darüber brauchen, was in den einzelnen Systemen eigentlich passiert, vor allem wenn mehrere Komponenten zusammenspielen und Fehler nicht sofort eindeutig zuordenbar sind. Es geht weniger darum, einfach nur zusätzliche technische Metriken zu sammeln, sondern eher darum, ein gemeinsames Verständnis zu schaffen, wie stabil die Plattform läuft, wo Engpässe entstehen und welche Auffälligkeiten sich frühzeitig erkennen lassen. Gerade im Automotive-Umfeld mit OnPrem-Hosting und längeren Betriebszeiträumen ist es wichtig, dass Betrieb, Entwicklung und fachliche Ansprechpartner nicht erst bei akuten Incidents reagieren, sondern idealerweise schon vorher Hinweise bekommen, wenn sich ein Problem anbahnt. In den Gesprächen wurde deutlich, dass aktuell viele Informationen zwar irgendwo vorhanden sind, aber nicht immer zentral, konsistent oder verständlich genug aufbereitet werden. Deshalb besteht der Bedarf, Monitoring und Observability so auszubauen, dass technische Zustände nachvollziehbarer werden und alle Beteiligten schneller erkennen können, ob ein Problem infrastrukturell, applikativ oder prozessual verursacht wird.

#### 2. Effiziente Fehleranalyse und reduzierte Ausfallzeiten
Ein wiederkehrendes Thema war, dass bei Störungen oder unerwartetem Verhalten oft zu viel Zeit verloren geht, bis klar ist, wo die Ursache liegt und wer konkret reagieren muss. Besonders bei komplexeren Systemlandschaften ist es schwierig, einzelne Logs, Metriken und Events manuell zusammenzubringen, wenn diese nicht sauber korreliert oder einheitlich strukturiert sind. Daraus ergibt sich der Bedarf, die Observability-Fähigkeiten so zu verbessern, dass Fehlerbilder schneller eingegrenzt werden können und man im Betrieb nicht jedes Mal bei null anfangen muss. Wichtig ist dabei nicht nur die reine technische Überwachung, sondern auch die Möglichkeit, Abläufe rückwirkend nachvollziehen zu können: Was ist wann passiert, welche Komponente war betroffen, welche Abhängigkeiten gab es und ob es ähnliche Muster bereits früher gegeben hat. Gerade für ein langfristig laufendes Projekt wie AMDA ist es aus Business-Sicht relevant, Ausfallzeiten zu reduzieren, Reaktionszeiten zu verbessern und die Abstimmung zwischen den beteiligten Teams effizienter zu machen. Ziel ist also eine bessere Entscheidungsgrundlage im Incident-Fall, ohne dass sich die Teams mühsam Informationen aus verschiedenen Systemen zusammensuchen müssen.

#### 3. Konsistente Sicht auf Betriebsqualität zur kontinuierlichen Verbesserung
In den Abstimmungen wurde außerdem deutlich, dass Monitoring nicht nur als rein technisches Kontrollinstrument verstanden werden soll, sondern auch als Grundlage, um den Betrieb langfristig gezielter zu steuern und Verbesserungen ableiten zu können. Es besteht der Bedarf, relevante Informationen so aufzubereiten, dass sie sowohl für technische Teams als auch für Projektverantwortliche verständlich und nutzbar sind. Dabei geht es beispielsweise um Stabilität, Verfügbarkeit, Performance, Fehlerhäufigkeiten und wiederkehrende Auffälligkeiten, aber auch um die Frage, wie gut bestehende Prozesse im Alltag funktionieren. Aktuell wirken viele Informationen eher verteilt oder situationsbezogen, wodurch es schwierig ist, ein einheitliches Bild über den tatsächlichen Projekt- und Systemzustand zu erhalten. Für VW beziehungsweise das AMDA-Projekt wäre es deshalb wichtig, eine konsistente Sicht auf die Betriebsqualität zu schaffen, um Risiken früher zu erkennen, Maßnahmen besser zu priorisieren und technische Optimierungen nachvollziehbar gegenüber Stakeholdern begründen zu können. Insgesamt soll Observability damit nicht nur beim Troubleshooting helfen, sondern auch eine belastbare Basis für kontinuierliche Verbesserung und langfristige Betriebsstabilität liefern.

## Provided Services
### Cloud/ onPrem: OnPrem

#### 1. CI/CD-Pipeline
CI/CD-Pipeline für automatisches Deployment von Dashboards, Alerts und Workloads.

#### 2. Infrastructure-as-Code Workspace
Infrastructure-as-Code Workspace mit Helm Packages und Docker Images.

#### 3. Custom Monitoring Tool & Grafana Dashboards
Custom Monitoring Tool für Trino Queries. Grafana Dashboards für Metrikenvisualisierung mit Echtzeit-Sichtbarkeit auf System Health und Ressourcenverbrauch.

## Frameworks & Tech Stack

- OpenShift
- Helm
- Prometheus
- Grafana Loki
- Grafana
- Kubernetes
- Bamboo

## Working methodology
- OFFEN

## Mastering Challenges

#### 1. DevOps-Struktur aufsetzen
DevOps-Struktur von Grund auf für bestehende manuell erstellte Ressourcen aufsetzen.

#### 2. Lösung optimieren und refactoren
Lösung optimieren und refactoren, um Onboarding und Support weiterer Anwendungen zu ermöglichen.

#### 3. Besonderheiten spezifischer Anwendungen verstehen
Besonderheiten spezifischer Anwendungen verstehen, um stabile generische und zugleich angepasste Lösung zu liefern.
