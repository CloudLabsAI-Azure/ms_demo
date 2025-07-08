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
    This demo showcases how Contoso, a medium-scale enterprise, built a unified, lake-centric foundation to streamline and manage its growing data estate. Contoso utilizes Task Flow to visualize workflows and Fast Copy to efficiently handle large datasets, improving operational efficiency. Discover how Contoso ingests data from diverse sources like SQL, SaaS applications, and Amazon S3, while external sources are integrated using Shortcuts and Mirroring. Real-time intelligence processes IoT sensor data and Azure EventHub streams for instant insights. Data is curated through medallion architecture using pipelines, notebooks, and Copilot for automation. Advanced analytics leverage ML models and AI-powered conversational Q&A. Enhanced Data Warehousing with Copilot further optimizes performance. Finally, Power BI Reports are seamlessly generated with Direct Lake and Copilot, delivering actionable insights.
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
        <a href="https://app-fabric-demo-3-smcc.azurewebsites.net" target="_blank">
          https://app-fabric-demo-3-smcc.azurewebsites.net
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
  </tbody>
</table>
