[![Download App](https://img.shields.io/badge/Download_App-Latest-brightgreen?logo=download)](https://github.com/Phenisys/microsoft-teams-observability-dynatrace-app/releases/download/v2.3.1/ms-teams-dynatrace-app-v2.3.1.zip)
[![All Releases](https://img.shields.io/badge/Releases-All-blue?logo=github)](https://github.com/Phenisys/microsoft-teams-observability-dynatrace-app/releases)
[![App Source](https://img.shields.io/badge/App_Repo-GitHub-lightgrey?logo=github)](https://github.com/Phenisys/microsoft-teams-observability-dynatrace-app)
[![Agent Collector](https://img.shields.io/badge/Teams_Observability_Agent-Repo-ffcc00?logo=github)](https://github.com/Phenisys/microsoft-teams-observability)
[![Dynatrace Hub](https://img.shields.io/badge/Dynatrace-Hub-1e8c8f)](https://www.dynatrace.com/hub/detail/microsoft-teams-observability/)

---

# Microsoft Teams Observability for Dynatrace — Quickstart

<p align="center">
  <img
    alt="image"
    src="https://github.com/user-attachments/assets/f9bd096b-5b7f-43e3-b634-b3f0becd4930"
    style="width:5%;"
  />
</p>

Monitor Microsoft Teams call quality, performance, outages, and user experience directly inside **Dynatrace**.

---

## 1. Prerequisites

- Access to a **Dynatrace environment** (SaaS or Managed)
- Permissions to **upload/install custom apps**
- _(Optional for Live mode)_ Ability to deploy the **MS Teams Observability Agent**

---

## 2. Install the Dynatrace App

1. **Download the latest app package**

   [![Download App](https://img.shields.io/badge/Download_App-Latest-brightgreen?logo=download)](https://github.com/Phenisys/microsoft-teams-observability-dynatrace-app/releases/download/v2.3.1/ms-teams-dynatrace-app-v2.3.1.zip)

3. In Dynatrace, go to:  
   **Hub → Upload app → Select the ZIP file**

4. After installation, open:  
   **Apps → Microsoft Teams Observability**

You can now use **Demo mode** immediately.

![Gif](https://github.com/user-attachments/assets/ac2db50e-7fc5-4402-a8eb-0c368bd2c0d8)

> Install the app in less than 1 minute

---

## 3. Demo or Live Mode

The application supports two modes:

### **Demo Mode (default)** — no setup required  
Ideal for quick evaluation, PoCs, or demos.

- The app starts in **Demo mode by default**
- Sample Teams calls, locations and users are loaded
- Lets you explore:
  - **Overview** (usage & performance)
  - **Calls**
  - **Call Details**
  - **Locations**
  - **Microsoft Issues**

Use this to understand how the app works before integrating real data.

---

### **Live Mode (full capabilities)** — requires a license  
To monitor your own Teams environment and unlock full functionality, two steps are required:

1. **Deploy the MS Teams Observability Agent**  
   → Collects enriched Microsoft Teams call metrics and pushes them to Dynatrace  
   Agent repo: https://github.com/Phenisys/microsoft-teams-observability

2. **Obtain a License from Phenisys**  
   → Start with a **[Free Trial](https://www.phenisys.com/ms-teams-observability-free-trial/)** or contact Phenisys to enable live data for production usage and full feature set

Once the agent is connected and licensed, your own calls, users, segments and locations will automatically populate the dashboards.

---

## 4. Troubleshooting

**No data appearing in Live mode?**  
- The app is in **Demo mode by default** — deploy the Agent and enable licensing for real data

**Demo mode empty?**  
- Ensure **Demo mode** is enabled in the app

**Unable to upload/install the app?**  
- Check Dynatrace permissions for custom app installation

---

## 5. Resources & Support

- App releases & source:  
  https://github.com/Phenisys/microsoft-teams-observability-dynatrace-app

- Agent (telemetry collector):  
  https://github.com/Phenisys/microsoft-teams-observability

- Dynatrace Hub listing:  
  https://www.dynatrace.com/hub/detail/microsoft-teams-observability/

- **Free Trial:**  
  https://www.phenisys.com/ms-teams-observability-free-trial/

- Licensing / Enterprise usage:  
  **Contact Phenisys**  
  https://www.phenisys.com/contact/#contact

- Issues & feature requests:  
  Open a GitHub Issue in the app repository
