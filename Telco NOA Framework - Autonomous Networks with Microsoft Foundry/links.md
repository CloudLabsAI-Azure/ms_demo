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
    In this demo, a telecom Network Operations Center uses a governed, multi-agent AI system to accelerate incident triage and resolution across complex network environments. A Supervisor Agent (Niobe) coordinates specialized agents for telemetry analysis, troubleshooting and remediation, security/compliance validation, and ticketing/ITSM, so operators can move from alert detection to diagnosis, recommended actions, execution, and post-fix verification with human-in-the-loop approvals at key steps. The solution is built on the Microsoft Agent Framework and Microsoft Foundry (orchestration, guardrails, evaluations), uses Microsoft Fabric (Eventhouse/KQL) and enterprise knowledge sources, Foundry IQ, storage-based SOPs to ground decisions, and integrates with operational systems like ServiceNow via MCP/TM Forum APIs to keep tickets updated and auditable end to end.
  </p>
  
</div>

<div class="highlight-box">
  <strong>IMPORTANT:</strong><br>
  Please launch the demo <strong>15 minutes before presenting</strong>. Resources may take a few minutes to provision.<br>
  ODL access provisioning may take <strong>5–7 minutes</strong>.<br>
  If unauthorized errors occur, wait a few minutes and then press <strong>Ctrl + Shift + R</strong> to refresh.
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
      <td>Web App Link</td>
      <td>
        <a href="https://app-network-ops-agentic-demo.azurewebsites.net/" target="_blank">
          https://app-network-ops-agentic-demo.azurewebsites.net/
        </a>
      </td>
    </tr>
    <tr>
      <td>Microsoft Fabric Workspace</td>
      <td>
        <a href="https://app.powerbi.com/home?experience=fabric" target="_blank">
          https://app.powerbi.com/home?experience=fabric
        </a>
      </td>
    </tr>
    <tr>
      <td>Microsoft Foundry Project</td>
      <td>
        <a href="https://ai.azure.com/nextgen/r/PwGrSaVvTueX-tIxVRVrQg,rg-network-ops-agentic-dev,,proj-telco-noa-demo-resource,proj-telco-noa-demo/build/agents" target="_blank">
          https://ai.azure.com/nextgen/r/PwGrSaVvTueX-tIxVRVrQg,rg-network-ops-agentic-dev,,proj-telco-noa-demo-resource,proj-telco-noa-demo/build/agents
        </a>
      </td>
    </tr>
  </tbody>
</table>

