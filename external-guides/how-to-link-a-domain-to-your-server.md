---
description: >-
  This is how to link to a domain like example.com to connect to your Minecraft
  server!
---

# 🔗 How to Link a Domain to Your Server

{% hint style="success" %}
**Difficulty Level**: 3/10
{% endhint %}

You will need a domain purchased before proceeding, you can get a domain from [https://namecheap.com/](https://namecheap.com/)

Once your domain is purchased, follow this guide on how to link a domain to Cloudflare for optimal speed and performance. Cloudflare also offers DDoS protection, however, this is only for websites and does not apply to your Minecraft Network (unless you're using a host that states that they are DDoS protected by Cloudflare)

{% tabs %}
{% tab title="Linking Domain to Cloudflare" %}
**1)** Once your domain is purchased, login into your Namecheap Dashboard and under domains, click **** `Manage`

**2)** On your domain management page, there should be a section called `Nameservers`, take note of where it is and leave the tab open in your browser

**3)** Go to [https://dash.cloudflare.com/](https://dash.cloudflare.com/) and Sign Up for an account

**4)** Once you're signed up and your email is verified, on right there should be a button called `Add Site`, click the button and put in the domain you just purchased on Namecheap

**5)** Follow through with the steps, pick the free plan when it asks you what plan you wish to purchase. Skip any DNS Record setup and enable any security settings.

**6)** Once you've gone through with the setup, you should receive two name servers (ex. `anna.ns.cloudflare.com`) Copy the first nameserver and go back to the Namecheap Dashboard

**7)** Under `Nameservers` on Namecheap, click the dropbox and select `Custom Nameservers`, then for Nameserver One put the first Nameserver you copied.

**8)** Go back to Cloudflare, copy the second nameserver, and put that for Nameserver Two.

**9)** Click the Check Button on Namecheap's Dashboard.

**10)** Nameservers may take up to 24 hours to update, once it does, you'll recieve a checkbox stating that your domain has been moved to Cloudflare. For now, you can move onto the next guide to setup a link between your Minecraft server and your Domain. Once your Nameservers update, the links will automatically apply if they're configured.
{% endtab %}
{% endtabs %}

{% hint style="info" %}
Server Domain Links can be done in **Vanilla Minecraft** (meaning no plugins/mods/addons are necessary to utilize this in-game system for your network
{% endhint %}

{% embed url="https://youtu.be/j9wC3AJWzQo" %}
Credit: Slick\_Torpedo
{% endembed %}
