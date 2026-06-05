
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

</style>

<div class="description">
  <h2 style="color: #333;">📄 Description</h2>
  <p>
    <br> This demonstration showcases the design, deployment, and orchestration of AI-powered hosted agents using the Microsoft Foundry Agent Service. It provides a technical walkthrough on creating and managing agents, integrating tools and APIs, and enabling multi-agent workflows for business use cases such as customer support and loyalty management. The use case highlights secure governance, scalability, and real-time execution, serving as a blueprint for building and managing production-ready AI agents in an enterprise environment.
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
      <td>Demo Web App</td>
      <td>
        <a href="https://app-azureherodreamdemos.azurewebsites.net/" target="_blank">
          https://app-azureherodreamdemos.azurewebsites.net/
        </a>
      </td>
    </tr>
    <tr>
    <td>Hosted Agent</td>
    <td>
        <a href="https://ai.azure.com/nextgen/r/PwGrSaVvTueX-tIxVRVrQg,rg-azurehero-demo-dev,,proj-azure-hero-demo-1a-resource-v2,proj-azure-hero-demo-1a-resource-v2/home" target="_blank">
          https://ai.azure.com/nextgen/r/PwGrSaVvTueX-tIxVRVrQg,rg-azurehero-demo-dev,,proj-azure-hero-demo-1a-resource-v2,proj-azure-hero-demo-1a-resource-v2/home
        </a>
    </td>
    </tr>
    <tr>
    <td>Container registry</td>
    <td>
      <a href="https://portal.azure.com/#@cloudlabsai.ms/resource/subscriptions/3f01ab49-a56f-4ee7-97fa-d23155156b42/resourceGroups/rg-azurehero-demo-dev/providers/Microsoft.ContainerRegistry/registries/acrherodemodev/overview" target="_blank">
        https://portal.azure.com/#@cloudlabsai.ms/resource/subscriptions/3f01ab49-a56f-4ee7-97fa-d23155156b42/resourceGroups/rg-azurehero-demo-dev/providers/Microsoft.ContainerRegistry/registries/acrherodemodev/overview
      </a>
    </td>
    </tr>
  </tbody>
</table>


