---
title: Pulumi Console
menu:
  intro:
    identifier: console
    weight: 1
no_on_this_page: true
aliases: [/docs/reference/service]
---

The [Pulumi Console](https://app.pulumi.com) is a web application that enables faster software collaboration. It provides the following features and benefits:

* Project and stack management
* Collaboration with teams across different organizations
* Protection against concurrent updates
* Detailed resource view and update history
* Integrations with your CI/CD system
* Extensions via webhooks and reusable project templates

<div class="md:flex flex-row mt-6 mb-6">
    <div class="w-1/2 border-solid border-t-2 border-gray-200">
        <h3 class="no-anchor pt-4"><i class="fas fa-angle-right pr-2"></i> Getting Started</h3>
        <p>
            In your browser, navigate to <a href="https://app.pulumi.com" target="_blank">app.pulumi.com</a> and sign up. The <a href="{{< relref "editions#community-edition" >}}">Pulumi Community Edition</a> is free forever
            for unlimited individual use.
        </p>
            <a class="btn btn-secondary" href="https://app.pulumi.com/signup" target="_blank">SIGN UP</a>
    </div>
    <div class="w-1/2 border-solid ml-4 border-t-2 border-gray-200">
        <h3 class="no-anchor pt-4"><i class="fas fa-user-circle pr-2"></i> Account Management</h3>
        <p>Learn about the Pulumi product editions, create a new organization, and link your account with a third party identity provider.
        <ul class="p2">
            <li><a href="{{< relref "editions" >}}">Plans and Editions</a></li>
            <li><a href="{{< relref "account" >}}">Accounts</a></li>
            <li><a href="{{< relref "organizations" >}}">Organizations</a></li>
            <li><a href="{{< relref "saml" >}}">Single Sign-on (SSO)</a></li>
        </ul>
    </div>
</div>

<div class="md:flex flex-row mt-6 mb-6">
    <div class="w-1/2 border-solid border-t-2 border-gray-200">
        <h3 class="no-anchor pt-4"><a href="{{< relref "collaboration" >}}"><i class="fas fa-users pr-2"></i> Collaboration</a></h3>
        <p>
            Collaborate with other developers and coordinate on updates. Manage access levels on your stacks.
        </p>
        <ul class="p2">
            <li><a href="{{< relref "stack-permissions" >}}">Stack Permissions</a></li>
            <li><a href="{{< relref "stack-management" >}}">Stack Management</a></li>
            <li><a href="{{< relref "organization-roles" >}}">Organization Roles</a></li>
            <li><a href="{{< relref "teams" >}}">Teams</a></li>
        </ul>
    </div>
    <div class="w-1/2 border-solid ml-4 border-t-2 border-gray-200">
        <h3 class="no-anchor pt-4"><a href="{{< relref "extensions" >}}"><i class="fab fa-connectdevelop pr-2"></i> Integrations and Extensions</a></h3>
        <p>Integrate Pulumi with your current continuous delivery pipeline, build your own extensions, and create reusable templates.
        <ul class="p2">
            <li><a href="{{< relref "/docs/guides/continuous-delivery" >}}">Continuous Delivery</a></li>
            <li><a href="{{< relref "webhooks" >}}">Webhooks</a></li>
            <li><a href="{{< relref "pulumi-button" >}}">"Deploy with Pulumi" Button</a></li>
        </ul>
    </div>
</div>