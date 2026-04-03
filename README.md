[![Download Latest](https://img.shields.io/badge/Download-Latest-brightgreen?logo=download)](https://github.com/Phenisys/microsoft-teams-observability-dynatrace-app/releases/latest)
[![All Releases](https://img.shields.io/badge/Releases-All-blue?logo=github)](https://github.com/Phenisys/microsoft-teams-observability-dynatrace-app/releases)
[![Documentation](https://img.shields.io/badge/Documentation-Online-blueviolet?logo=gitbook)](https://phenisys.github.io/microsoft-teams-observability-documentation/backends/dynatrace/app/)
[![Dynatrace Hub](https://img.shields.io/badge/Dynatrace-Hub-1e8c8f)](https://www.dynatrace.com/hub/detail/microsoft-teams-observability/)
[![Microsoft Teams Observability](https://img.shields.io/badge/Microsoft_Teams_Observability-Agent-blue)](https://github.com/Phenisys/microsoft-teams-observability)


# MS Teams Observability — Dynatrace Application

The **MS Teams Observability Dynatrace Application** provides ready-to-use visualizations to monitor Microsoft Teams inside **Dynatrace**.

Installed in a Dynatrace environment, the application provides operational visibility into Microsoft Teams activity and quality using telemetry collected by the agent and stored in Dynatrace Grail. It helps organizations monitor collaboration experience, investigate service degradations, analyze call quality, and support operational troubleshooting workflows across engineering, operations, and support teams.

The application is designed to work with the [**Microsoft Teams Observability Agent**](https://github.com/Phenisys/microsoft-teams-observability), which collects and forwards the data used by the dashboards and investigation views.

The application also supports a **Demo Mode** with built-in sample data, allowing evaluation, testing, or demonstrations without requiring a live collector connection.

---

## Downloads

To obtain the application:

- **Latest release (recommended)** — see release notes and package: [here](https://github.com/Phenisys/microsoft-teams-observability-dynatrace-app/releases/latest)

- **All releases** — browse all available versions: [here](https://github.com/Phenisys/microsoft-teams-observability-dynatrace-app/releases)

---

## Documentation

Full documentation for the application is available here:

- **Application overview**: [MS Teams Observability Application](https://phenisys.github.io/microsoft-teams-observability-documentation/backends/dynatrace/app/)
- **Installation guide**: [Installation](https://phenisys.github.io/microsoft-teams-observability-documentation/backends/dynatrace/app/installation/)
- **Home page**: [Home](https://phenisys.github.io/microsoft-teams-observability-documentation/backends/dynatrace/app/home/)
- **Sites page**: [Sites](https://phenisys.github.io/microsoft-teams-observability-documentation/backends/dynatrace/app/sites/)
- **Calls page**: [Calls](https://phenisys.github.io/microsoft-teams-observability-documentation/backends/dynatrace/app/calls/)
- **Call Overview page**: [Call Overview](https://phenisys.github.io/microsoft-teams-observability-documentation/backends/dynatrace/app/call-overview/)
- **Users page**: [Users](https://phenisys.github.io/microsoft-teams-observability-documentation/backends/dynatrace/app/users/)
- **Issues page**: [Issues](https://phenisys.github.io/microsoft-teams-observability-documentation/backends/dynatrace/app/issues/)
- **Configuration page**: [Configuration](https://phenisys.github.io/microsoft-teams-observability-documentation/backends/dynatrace/app/configuration/)

---

## Installation

The application can be installed from **Dynatrace Hub** or by uploading the application ZIP package manually. After installation, it can run immediately in **Demo Mode**, while **Live Mode** requires a configured collector and a valid license. Detailed installation and activation steps are documented in the installation guide.

- [Install the Dynatrace Application](https://phenisys.github.io/microsoft-teams-observability-documentation/backends/dynatrace/app/installation/)

---

## Visualizations

The application provides several views addressing different operational needs:

### 1. Home

High-level observability cockpit for Microsoft Teams, showing a 7-day summary of call activity and quality with KPI cards, call health distribution, and platform distribution.

<img width="1744" height="1042" alt="image" src="https://github.com/user-attachments/assets/f3d07bb4-a512-4bbd-8cc0-22cc0fde767d" />

---

### 2. Calls

Searchable and filterable list of recorded Microsoft Teams calls, used to locate calls quickly, investigate quality problems, and navigate to a detailed call analysis view.

<img width="1744" height="1047" alt="image" src="https://github.com/user-attachments/assets/4cab13a2-3960-4504-961c-4a308dd6d6c3" />

---

### 3. Users

Per-user analytics across the Microsoft Teams environment, including identity, call statistics, network information, device details, and recent activity.

<img width="1746" height="1048" alt="image" src="https://github.com/user-attachments/assets/6b4fd5d3-f740-49e5-a3db-e9f8d963a060" />

---

### 4. Call Overview

Detailed analysis of a single Microsoft Teams call, including participants, locations, quality indicators, stream-level metrics, timeline data, and optional AI-generated root cause analysis.

<img width="1728" height="921" alt="image" src="https://github.com/user-attachments/assets/fc1e834d-7ad7-4e8c-9dd6-0372427cc537" />

---

### 5. Issues

Displays Microsoft service health incidents affecting the tenant, including active and recently resolved issues, to help correlate degradations with known Microsoft outages.

<img width="1732" height="1045" alt="image" src="https://github.com/user-attachments/assets/d029f5fa-0cd7-41a5-80bc-7cdc16088157" />

---

### 6. Sites

Aggregated analysis of call quality and network performance by geographic location and subnet, helping identify localised degradations and network-related patterns.

<img width="1741" height="1045" alt="image" src="https://github.com/user-attachments/assets/35cc9c0b-759e-41b6-9806-ed8e7b74550e" />

---

### 7. Configuration

Central configuration area for the application, including license management, demo mode, feature status, outgoing connections, bucket and pipeline settings, site file management, AI analysis, Microsoft configuration, domain filters, and permissions.

---

## Operating Modes

The application supports two operating modes:

- **Demo Mode** — uses built-in sample data and can be used immediately after installation
- **Live Mode** — uses real tenant data sent by the collector and requires a valid configuration and license

This makes it possible to evaluate the UI and workflows before switching to production data.

---

## Related Components

### Teams Observability Agent

Collector project used to send Microsoft Teams observability data to Dynatrace:

- https://github.com/Phenisys/microsoft-teams-observability

### Dynatrace Extension

Dynatrace extension packaging and deployment for the collector:

- https://github.com/Phenisys/dynatrace-extension-teams-observability-agent

---

## Additional Information

Dynatrace Hub listing:

- https://www.dynatrace.com/hub/detail/microsoft-teams-observability/

Issues and feature requests can be submitted by opening a GitHub Issue.
