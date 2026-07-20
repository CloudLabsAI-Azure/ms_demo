<style>
  table {
    width: 80%;
    margin: 30px auto;
    border-collapse: collapse;
    font-family: 'Segoe UI', sans-serif;
    font-size: 15px;
  }

  th {
    background: #f2f2f2;
    padding: 10px;
    text-align: left;
    border: 1px solid #ddd;
  }

  td {
    width: 900px;
    height: 10px;
    padding: 10px;
    text-align: left;
    border: 1px solid #ddd;
  }

  .description {
    margin: 0 auto;
    font-family: 'Segoe UI', sans-serif;
    font-size: 14px;
    color: #444;
  }

  .highlight-box {
    background: #f8f9fa;
    padding: 12px 24px 12px 32px; /* Top, Right, Bottom, Left */
    border-left: 4px solid #0078d4;
    margin: 20px auto;
    font-size: 14px;
    text-align: left;
}


  }
</style>

<div class="description">
  <h2 style="color: #333;">📄 Description</h2>
  <p>
    Caldova has approved an accelerated Next Gen Pharma launch, and a competitor is targeting the same November launch window. The VP of Manufacturing needs one answer: can Caldova close a 7% capacity gap across three plants in time? This end-to-end demo follows that question from a single grounded agent to a governed fleet of agents.

First, Jordan, the Data Engineer, grounds a supply chain intelligence agent already running in Foundry and published to M365 Copilot across four Microsoft IQ dimensions - Fabric IQ for the live manufacturing ontology and competitive products data, Web IQ for cited market intelligence, Foundry IQ for GMP SOPs and changeover guidance, and Work IQ for the escalation path. Sam, the Operations Lead, gets cited, permission-aware answers in seconds to questions that used to take three days.
Next, when a second agent is needed to evaluate Contract Manufacturing Organizations(CMOs) that can close the gap fast, Jordan builds it in Foundry on the same Fabric IQ ontology, Foundry IQ knowledge base, Work IQ, and Web IQ - no new connectors, no new RAG - while Alex, the Procurement Manager, spins up a low-code CMO RFP tracking agent in Copilot Studio on the same intelligence. Two agents, almost no incremental cost, proving agent development now compounds rather than restarts.
Six weeks in, the fleet has grown to four agents making real decisions on shared Microsoft IQ. From a single control plane in Agent 365, the IT compliance lead turns sprawl into a governed portfolio - shadow agents surfaced, each agent carrying its own Entra ID, permission-scoped answers per user, and Purview blocking restricted R&D content while briefings stay complete and compliant. One set of policies covers every agent, and each new agent inherits that trust posture the moment it goes live. The foundation is modernized, the data is unified, agents are deployed across every function, and intelligence is grounded and compounding - trusted enough for leadership to bet the launch on it. That is how Caldova closed the gap.
  </p>
  
</div>

<div class="highlight-box">
  <strong>IMPORTANT:</strong><br>
  Please launch the demo <strong>15 minutes before presenting</strong>. Resources may take a few minutes to provision.<br>
  ODL access provisioning may take <strong>5–7 minutes</strong>.<br>
  If unauthorized errors occur, wait a few minutes and then press <strong>Ctrl + Shift + R</strong> to refresh.<br>
  For Microsoft Fabric, once you login with the ODL user, please wait <strong>5 minutes</strong> and refresh the screen to see the Workspaces.<br>
  <span style="color:red; font-weight:bold;">Note:</span>
  If you face any issues while accessing the demo environment, please reach out to
  <a href="mailto:mdxazuredemosupport@spektrasystems.com">mdxazuredemosupport@spektrasystems.com</a>
  and include the ODL username displayed in your lab environment details for faster assistance.
</div>

<!-- Auth Table -->

| **User Login Credentials** |                                       |
|-----------------|---------------------------------------|
| Username    | <inject key="AzureAdUserEmail" />     |
| Password   | <inject key="AzureAdUserPassword" />  |


<!-- Resource Details Table -->
<table>
  <thead>
    <tr>
      <th>Resources</th>
      <th>Links</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Microsoft Fabric Workspace</td>
      <td>
        <a href="https://app.fabric.microsoft.com/" target="_blank">
          https://app.fabric.microsoft.com/
        </a>
      </td>
    </tr>
    <tr>
      <td>Microsoft Foundry</td>
      <td>
        <a href="https://ai.azure.com/nextgen/r/UG6G_IU8RVem5a1yEU79Kw,rg-ops-intelligence-prod-001,,foundry-ops-intelligence-prod-001,proj-ops-intelligence-prod-001/home" target="_blank">
          https://ai.azure.com/nextgen/r/UG6G_IU8RVem5a1yEU79Kw,rg-ops-intelligence-prod-001,,foundry-ops-intelligence-prod-001,proj-ops-intelligence-prod-001/home
        </a>
      </td>
    </tr>
    <tr>
      <td>Microsoft 365 Copilot</td>
      <td>
        <a href="https://m365.cloud.microsoft/" target="_blank">
          https://m365.cloud.microsoft/
        </a>
      </td>
    </tr>
    <tr>
      <td>Copilot Studio</td>
      <td>
        <a href="https://copilotstudio.preview.microsoft.com/" target="_blank">
          https://copilotstudio.preview.microsoft.com/
        </a>
      </td>
    </tr>
  </tbody>
</table>
