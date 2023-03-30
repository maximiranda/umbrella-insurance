---
title: "Platform Application"
description: "Welcome to Slingr - the ultimate platform to create cloud apps that integrate with other SaaS solutions seamlessly! If you're wondering what Slingr is, then look no further. "
lead: "Our Slingr-based platform offers efficient management of multiple funcionalities"
date: 2020-10-06T08:48:57+00:00
lastmod: 2020-10-06T08:48:57+00:00
draft: false
images: []
menu:
  docs:
    parent: "prologue"
weight: 40
toc: true
---


<style>
.centerimage {
  padding-top: 1em;
  display: flex;
  justify-content: center;
  padding-bottom: 2em;

}
</style>

<style>
  .emoji-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
  }

<style>
  .emoji-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
  }
  
  .emoji-grid span {
    font-size: 3rem;
    line-height: 3rem;
    padding: 1rem; /* increased padding to space emojis apart */
    display: flex;
    justify-content: center;
    align-items: center;
  }
</style>


{{< callout type="default" contend="" >}}
{{< callout type="default" contend="" >}}
<b>Goal</b>
{{< /callout >}}


The <code>aim</code> of the platform is to consolidate all the essential features into an integrated solution for a hypothetical insurance company.
<br>

<div class="emoji-grid">
  <span>📃</span>
  <span>📢</span>
  <span>✉️</span>
  <span>📊</span>
</div>
{{< /callout >}}

{{< callout type="default" contend="" >}}
{{< callout type="default" contend="" >}}
<b>Features</b>
{{< /callout >}}
<ul class="list-group">
<li class="list-group-item" >Users groups</li>

<li class="list-group-item" >Policies management</li>
<li class="list-group-item" >Claims management</li>
<li class="list-group-item" >Metrics dashboard</li>
</ul>
<div class="summary2">
    <b><h5>Users groups 👱🏼</h5></b>
    <div  class="centerimage">
    <img width="auto" height="auto" src="/images/vendor/1.png">
    </div>
    <ul>
        <b><li><h6> Administrators:</h6></b>
        The admin is a user with full control over the insurance app's functionality and data. This user has access to <code>all features </code> and can <code> manage </code> <code>user accounts</code>, <code>policies</code>, <code>claims</code>, and other <code>critical data</code>. The admin can add or remove agents, view reports, and configure system settings.<br><br>
        Admins have <code>access to all information</code> about <code>admins</code>, <code>agents</code>, and <code>customers</code>, as well as platform functionalities like <code>"restore data"</code>.

        <br><br><b>❇️  Restore Data - the process of copying <code>backup data </code> from secondary storage and <code>restoring it </code> to its <code>original location</code> or a new location. </b><br><br>
         The Admin Panel includes a metrics dashboard, policies section, claims section with standard and workflow views, customers section, and administration section. The settings section has "restore data" functionality to reset the app data to default values.</li>
        <b><li><h6>Agents:</h6></b>
        An agent is a user who is responsible for selling and managing insurance policies on behalf of the insurance company. This user typically has access to specific parts of the app, such as customer information, policy information, and  claims. The agent can create and manage policies, track claims, and communicate with customers.<br>
        Although agents have a smaller scope of functionalities compared to administrators, they play an important role in the app.<br> Agents have access to the claims panel, but only for their respective customers' claims. They can also access a view that lists all their customers to have a global view of them. In the administrator section, agents can view all types of coverages.
        <br>Agents have access only to their own information, while global information is exclusively available to administrators.
        <b><li><h6>Customers:</h6></b>
        The customer is a user who purchases insurance policies from the insurance company through the app. This user can browse available policies, request quotes, purchase policies, and file claims. The customer can view policy details, premiums, and claim history. They can also communicate with agents or customer support for assistance.<br>
        Customers are the clients of the app. Everything is done for simplifing their user interface. They have access to a 	policies view and a claims managment view where they can report claims of their policies

</div>
<div class="summary2">
    <b><h5>Policies management 📃</h5></b>
In the context of insurance, a policy is a contract between an insurance company and an individual or organization that outlines the terms and conditions of the insurance coverage. It specifies the type of coverage being provided, the amount of coverage, the cost of the coverage , the length of time the policy is in effect, and any other relevant details of the agreement. <br> The policy serves as a legal document that both the insurer and the insured must adhere to.Depending on the user's group, they can create, edit, delete, and read their own policies or policies of others within their panel. These policies can cover various areas such as home, health, or car insurance.
<br>
In the policies management of an insurance app, the roles and permissions of admin, agent, and customer typically differ as follows:
<ul>
<b><li>Admin: </li></b>The admin user has full control over policies management in the insurance app. They can create, edit, delete, and manage policies as well as policyholders. The admin can also view reports and analytics related to policies, such as premiums collected and claims filed. Additionally, they can configure system settings and manage user accounts, including agents and customers.

<b><li>Agent:</li></b> The agent user typically has limited control over policies management, as their primary role is to sell and manage policies on behalf of the insurance company. They can create new policies and manage policyholders, such as adding or removing beneficiaries, updating contact information, and processing policy renewals. Agents can also view policy details and premiums, track claims, and communicate with customers regarding policy-related inquiries.

<b><li>Customer:</li></b> The customer can only manage their own policies and policyholders. They can view their policy details, make premium payments, file claims, and communicate with agents or customer support for assistance. The customer can also initiate policy changes, such as adding or removing beneficiaries, updating contact information, and making policy renewals.
</ul>
Overall, the admin has the highest level of control, followed by agents and then customers, who have the most limited access to policy management features.


</div>

<div class="summary2">
    <b><h5>Claims management 📢</h5></b>
An insurance claim is a formal request made by a policyholder to an insurance company, asking for compensation or coverage for a loss or damage covered by the policy.<br>

In the claims management of an insurance app, the roles and permissions of admin, agent, and customer typically differ as follows:<br>
<ul>
<b><li> Admin: </li></b>The admin user has full control over claims management in the insurance app. They can view and manage all claims filled by customers, assign claims to agents for review and processing, and make claim-related decisions, such as approving or denying claims. The admin can also generate reports and analytics related to claims, such as the number of claims filed, amount paid out, and claim processing times. <br><br><b>
📌 access to claim's workflow view - Includes claim's of <code>all Customers</code></b><br><br>

<div  class="centerimage">
<img width="auto" height="auto" src="/images/vendor/workflow.gif">
</div>
<b><li>Agent:</li></b> The agent user can assist in the claims process by reviewing claims assigned to them by the admin, communicating with customers regarding claims, and updating claims statuses. They can also provide recommendations to the admin on whether to approve or deny claims based on their expertise.

<br><br><b>📌 access to claim's workflow view - Includes claim's of <code>their own Customers</code></b><br><br>

<b><li>Customer:</li></b> The customer can file claims, provide supporting documentation, and track the progress of their claims. They can communicate with agents or customer support for assistance or updates on the claims process.
</ul>
Overall, the admin has the highest level of control, followed by agents and then customers, who have the most limited access to claims management features.

Customers can submit insurance claims to their respective agents, who manage the claims process.


</div>



<div class="summary2">
    <b><h5>Metrics dashboard 📊</h5></b>

A metric dashboard is a tool used by businesses to track important metrics and make data-driven decisions. It uses charts and graphs to display key performance indicators and trends in an easy-to-understand way.<br> The dashboard can be customized to focus on specific metrics and provides a quick overview of performance.<br>

Our app has a customized metric dashboard that covers the important areas of the insurance industry. This feature, powered by Slingr technology, helps admins analyze data and make informed decisions to improve app performance. <br> The dashboard provides a simplified view of key metrics, making it easy to monitor performance and understand the app's functionality. <br>This is a testament to our commitment to providing the best tools and resources for admins to excel in the fast-paced and dynamic insurance industry.
<div  class="centerimage">
<img width="auto" height="auto" src="/images/vendor/metrics.png">
</div>
</div>
