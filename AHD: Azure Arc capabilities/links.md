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
    <br> This demo focuses on hybrid and multi-cloud management using Azure Arc. Specifically, it showcases how organizations can unify their infrastructure management by bringing non-Azure assets under the Azure control plane. The session highlights the practical implementation of Azure Arc by detailing the steps to onboard and govern AWS EC2 instances, ensuring consistent security, compliance, and operational visibility across diverse environments.
  </p>
</div>

<div class="highlight-box">
  <strong>IMPORTANT:</strong><br>
  Please launch the demo <strong>15 minutes before presenting</strong>. Resources may take a few minutes to provision.<br>
  ODL access provisioning may take <strong>5–7 minutes</strong>.<br>
  If unauthorized errors occur, wait a few minutes and then press <strong>Ctrl + Shift + R</strong> to refresh.<br>
  Databricks may take around <strong>30–40 minutes</strong> to become available to the ODL user. This is due to Databricks default behavior of syncing users every 40 minutes.<br>
 For Microsoft Fabric, once you login with the ODL user, please wait <strong>5 minutes</strong> and refresh the screen to see the Workspaces.
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
    <td>Azure ARC</td>
    <td>
      <a href="https://portal.azure.com/#view/Microsoft_Azure_ArcCenterUX/ArcCenterMenuBlade/~/allresources" target="_blank">
        https://portal.azure.com/#view/Microsoft_Azure_ArcCenterUX/ArcCenterMenuBlade/~/allresources
    </td>
    </tr>
  </tbody>
</table>

