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
  <h2 style="color: #333;">📄 Description</h2><br>
  <p>
    This Demo offers a practical experience into the backend of the AIDW Telecom DREAM Demo featuring Agentic AI. The demo highlights how Contoso, a leading telecom provider, revolutionized its customer service operations using a multi-agent Azure AI solution that handles customer calls related to billing issues, network problems, and plan inquiries.<br>
    The solution is powered by a multi-agent architecture comprising five specialized Azure AI Agents, built with the Azure AI Foundry SDK and orchestrated using Microsoft AutoGen 0.4. These agents are equipped with tools to perform create, read, update, and delete (CRUD) operations on customer data stored in Azure Cosmos DB. Leveraging the natural language and generative AI capabilities of the GPT-4o model via Azure OpenAI Service, the agents offer intelligent, conversational support. <br>
    The backend is developed using FastAPI and deployed on Azure App Service, ensuring a scalable and resilient infrastructure. Contoso’s implementation serves as a reference architecture for building Azure AI-powered customer engagement solutions, applicable across telecom and other customer-centric industries.<br>

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
        <a href="https://app-aidw-telco-prod.azurewebsites.net/" target="_blank">
          https://app-aidw-telco-prod.azurewebsites.net/
        </a>
      </td>
    </tr>
    <tr>
      <td>Azure AI Foundry</td>
      <td>
        <a href="https://ai.azure.com/playground/agentsList?wsid=/subscriptions/506e86fc-853c-4557-a6e5-ad72114efd2b/resourceGroups/rg-telcoagenticdemo-prod/providers/Microsoft.MachineLearningServices/workspaces/prj-call-center-with-agents-prod&tid=f94768c8-8714-4abe-8e2d-37a64b18216a" target="_blank">
          https://ai.azure.com/playground/agentsList?wsid=/subscriptions/506e86fc-853c-4557-a6e5-ad72114efd2b/resourceGroups/rg-telcoagenticdemo-prod/providers/Microsoft.MachineLearningServices/workspaces/prj-call-center-with-agents-prod&tid=f94768c8-8714-4abe-8e2d-37a64b18216a
        </a>
      </td>
    </tr>
    <tr>
      <td>Azure Portal</td>
      <td>
        <a href="https://portal.azure.com/#@CloudLabsAIoutlook.onmicrosoft.com/resource/subscriptions/506e86fc-853c-4557-a6e5-ad72114efd2b/resourceGroups/rg-telcoagenticdemo-prod/overview" target="_blank">
          https://portal.azure.com/#@CloudLabsAIoutlook.onmicrosoft.com/resource/subscriptions/506e86fc-853c-4557-a6e5-ad72114efd2b/resourceGroups/rg-telcoagenticdemo-prod/overview
        </a>
      </td>
    </tr>
  </tbody>
</table>
