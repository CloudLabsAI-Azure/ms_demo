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
    This demo showcases how Contoso, a large enterprise, utilized this integration to create an outside-in view with an enterprise chatbot, build a personalized shopping assistant, analyze customer interactions, and customize machine learning models. Highlights include indexing files in Fabric with Azure AI Search, vectorizing user queries using the OpenAI ada-002 model, and generating cohesive answers through Azure GPT-4 Turbo. The query is sent to Azure AI Search to perform a hybrid search over Cosmos DB to retrieve relevant products. Additionally, the demo develops a chat assistant combining Azure AI Speech, GPT-4, and RAG with OneLake customer data, featuring sentiment analysis and visualizing customer satisfaction in Power BI. It leverages Microsoft Fabric's capabilities for model development, feature engineering, and integration with Azure AI Model Catalog's large language models.
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
        <a href="https://app-azure-openai-demo-2-prod.azurewebsites.net/" target="_blank">
          https://app-azure-openai-demo-2-prod.azurewebsites.net/
        </a>
      </td>
    </tr>
    <tr>
      <td>Azure AI Foundry</td>
      <td>
        <a href="https://ai.azure.com/?tid=f94768c8-8714-4abe-8e2d-37a64b18216a" target="_blank">
          https://ai.azure.com/?tid=f94768c8-8714-4abe-8e2d-37a64b18216a
        </a>
      </td>
    </tr>
    <tr>
    <td>Azure ML Studio</td>
    <td>
      <a href="https://ml.azure.com/home?tid=f94768c8-8714-4abe-8e2d-37a64b18216a" target="_blank">
        https://ml.azure.com/home?tid=f94768c8-8714-4abe-8e2d-37a64b18216a
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
  </tbody>
</table>
