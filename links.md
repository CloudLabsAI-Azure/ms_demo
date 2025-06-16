# 🏥 Data & AI Healthcare Industry Scenario DREAM Demo 2.0

<div style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white; padding: 20px; border-radius: 10px; margin-bottom: 30px;">
  <h2 style="margin: 0; color: white;">🎯 Demo Overview</h2>
  <p style="margin: 10px 0 0 0; font-size: 16px; line-height: 1.5;">This demo showcases how Modern Analytics in MIDP and Azure OpenAI Service can revolutionize the healthcare industry. The demo includes healthcare use cases and Payor scenarios, such as Call Center report analysis, transcript improvisation, and Member experience.</p>
</div>

## 📋 Description

This comprehensive demonstration leverages the trusted and integrated capabilities of **Microsoft Cloud for Healthcare** to:

- 🔍 **Manage health data at scale**
- 🤖 **Apply machine learning and AI automation**
- ⚡ **Deploy easy-to-use AI tools for efficiency**
- 🔄 **Implement workflows specifically designed for health data**

These technologies work together to **accelerate clinical analysis**, **improve patient engagement**, and **accelerate data value**.

---

## ⚠️ Important Setup Instructions

<div style="background-color: #fff3cd; border: 1px solid #ffeaa7; border-radius: 8px; padding: 15px; margin: 20px 0;">
  <h3 style="margin-top: 0; color: #856404;">🕐 Pre-Demo Setup</h3>
  <ul style="margin-bottom: 0;">
    <li><strong>Launch the demo 15 minutes prior to presenting</strong></li>
    <li>Some resources may take a few minutes to provision</li>
    <li>ODL user access provisioning: <strong>5-7 minutes</strong></li>
    <li>If you encounter unauthorized errors, wait and hard refresh (<code>Ctrl + Shift + R</code>)</li>
  </ul>
</div>

---

## 🔐 Authentication Credentials

<div style="background-color: #e3f2fd; border-left: 4px solid #2196f3; padding: 15px; margin: 20px 0;">
  <h3 style="margin-top: 0;">Azure and Microsoft Fabric Login</h3>
  <table style="width: 100%; border-collapse: collapse;">
    <tr>
      <td style="padding: 8px; font-weight: bold; width: 30%;">📧 Email/Username:</td>
      <td style="padding: 8px; background-color: #f5f5f5; border-radius: 4px;"><code>&lt;inject key="AzureAdUserEmail"&gt;&lt;/inject&gt;</code></td>
    </tr>
    <tr>
      <td style="padding: 8px; font-weight: bold;">🔑 Password:</td>
      <td style="padding: 8px; background-color: #f5f5f5; border-radius: 4px;"><code>&lt;inject key="AzureAdUserPassword"&gt;&lt;/inject&gt;</code></td>
    </tr>
  </table>
</div>

---

## 🌐 Demo Resources & Quick Links

### 🏥 Healthcare 2.0 WebApp
<div style="background-color: #f8f9fa; border: 1px solid #dee2e6; border-radius: 8px; padding: 15px; margin: 10px 0;">
  <p style="margin: 0;"><strong>Primary Demo Interface</strong></p>
  <p style="margin: 5px 0 0 0;"><a href="https://app-health-care-demo-v2prod.azurewebsites.net/" target="_blank" style="color: #0066cc; text-decoration: none; font-weight: bold;">🔗 Healthcare Demo App</a></p>
</div>

### 📊 Microsoft Fabric Workspace
<div style="background-color: #f8f9fa; border: 1px solid #dee2e6; border-radius: 8px; padding: 15px; margin: 10px 0;">
  <p style="margin: 0;"><strong>Analytics & Power BI Dashboard</strong></p>
  <p style="margin: 5px 0 0 0;"><a href="https://app.powerbi.com/groups/9e83dec4-28ba-480d-920e-09b24bfd475a/list?experience=power-bi" target="_blank" style="color: #0066cc; text-decoration: none; font-weight: bold;">🔗 Fabric Workspace</a></p>
</div>

---

## ⚙️ Azure Services & Tools

<div style="display: grid; gap: 15px; margin-top: 20px;">

### 🗄️ Data Services
<div style="background-color: #e8f5e8; border: 1px solid #c3e6c3; border-radius: 8px; padding: 15px;">
  
**Azure Synapse Analytics**  
*Data warehousing and big data analytics*  
[🔗 Open Synapse Workspace](https://web.azuresynapse.net/en/home?workspace=%2Fsubscriptions%2F506e86fc-853c-4557-a6e5-ad72114efd2b%2FresourceGroups%2Frg-healthcare2-prod%2Fproviders%2FMicrosoft.Synapse%2Fworkspaces%2Fsynhealthcare2prod)

**Azure Cosmos DB**  
*NoSQL database for healthcare data*  
[🔗 Open Cosmos DB](https://portal.azure.com/#@CloudLabsAIoutlook.onmicrosoft.com/resource/subscriptions/506e86fc-853c-4557-a6e5-ad72114efd2b/resourceGroups/rg-healthcare2-prod/providers/Microsoft.DocumentDB/databaseAccounts/cosmos-healthcare2-prod/dataExplorer)

</div>

### 🔒 Governance & Security
<div style="background-color: #fff3e0; border: 1px solid #ffcc80; border-radius: 8px; padding: 15px;">

**Microsoft Purview**  
*Data governance and compliance*  
[🔗 Open Purview Portal](https://web.purview.azure.com/resource/purviewhealthcare2prod/main/catalog/home?feature.tenant=f94768c8-8714-4abe-8e2d-37a64b18216a)

</div>

### 🤖 AI & Machine Learning
<div style="background-color: #f3e5f5; border: 1px solid #ce93d8; border-radius: 8px; padding: 15px;">

**Azure ML Workspace**  
*Machine learning model development and deployment*  
[🔗 Open ML Studio](https://ml.azure.com/?tid=f94768c8-8714-4abe-8e2d-37a64b18216a&wsid=/subscriptions/506e86fc-853c-4557-a6e5-ad72114efd2b/resourcegroups/rg-healthcare2-prod/providers/Microsoft.MachineLearningServices/workspaces/mlw-healthcare2-prod)

**Azure Databricks**  
*Collaborative analytics platform*  
[🔗 Open Databricks](https://adb-6711778118362600.0.azuredatabricks.net/?o=6711778118362600#)

</div>

### 📡 Real-time Data
<div style="background-color: #e1f5fe; border: 1px solid #81d4fa; border-radius: 8px; padding: 15px;">

**Event Hub**  
*Real-time patient monitoring data streaming*  
[🔗 Open Event Hub](https://portal.azure.com/#@CloudLabsAIoutlook.onmicrosoft.com/resource/subscriptions/506e86fc-853c-4557-a6e5-ad72114efd2b/resourceGroups/rg-healthcare2-prod/providers/Microsoft.EventHub/namespaces/evh-patient-monitoring-prod/overview)

</div>

</div>

---

## 💡 Pro Tips

<div style="background-color: #e8f4fd; border: 1px solid #bee5eb; border-radius: 8px; padding: 15px; margin: 20px 0;">
  <h3 style="margin-top: 0; color: #0c5460;">🎯 Best Practices</h3>
  <ul style="margin-bottom: 0;">
    <li><strong>Sign out</strong> of any personal Microsoft accounts before using demo credentials</li>
    <li><strong>Test all links</strong> 15 minutes before your presentation</li>
    <li>Keep the <strong>Healthcare WebApp</strong> as your primary demo interface</li>
    <li>Use <strong>hard refresh</strong> (Ctrl + Shift + R) if you encounter any loading issues</li>
  </ul>
</div>

---

<div style="text-align: center; padding: 20px; background-color: #f8f9fa; border-radius: 10px; margin-top: 30px;">
  <p style="margin: 0; color: #6c757d; font-style: italic;">Ready to transform healthcare with the power of Microsoft Cloud! 🚀</p>
</div>
