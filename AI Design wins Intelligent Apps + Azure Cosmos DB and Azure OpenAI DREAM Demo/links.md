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
    This demo shows how Contoso, a well-established retail company, is making big changes to its website using Azure Cosmos DB, Azure Kubernetes Services (AKS), and Azure OpenAI Services. Now, Contoso is entering a new era of connecting with customers. They're using advanced natural language processing and machine learning with the help of AI-powered Chatbot/Shopping Assistant "Cora" to give personalized shopping experiences. Additionally, Azure Cosmos DB, a worldwide NoSQL database service, is helping Contoso transform its operations. Azure Kubernetes Service (AKS) is providing a flexible platform for deploying and managing applications in containers, allowing Contoso to quickly create and launch apps. This ensures that both their online and in-store systems stay quick and adaptable to what customers want.
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
        <a href="https://app-intelligent-apps-web-prod.azurewebsites.net/" target="_blank">
          https://app-intelligent-apps-web-prod.azurewebsites.net/
        </a>
      </td>
    </tr>
    <tr>
    <td>Microsoft Fabric Workspace</td>
    <td>
        <a href="https://app.fabric.microsoft.com/home" target="_blank">
          https://app.fabric.microsoft.com/home
        </a>
    </td>
    </tr>
    <tr>
    <td>Resource Group</td>
    <td>
      <a href="https://portal.azure.com/#@cloudlabsai.ms/resource/subscriptions/506e86fc-853c-4557-a6e5-ad72114efd2b/resourceGroups/rg-intelligent-apps-cosmos-prod/overview" target="_blank">
          https://portal.azure.com/#@cloudlabsai.ms/resource/subscriptions/506e86fc-853c-4557-a6e5-ad72114efd2b/resourceGroups/rg-intelligent-apps-cosmos-prod/overview
      </a>
    </td>
    </tr>
  </tbody>
</table>
