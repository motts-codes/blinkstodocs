# 🌐 Custom Domain

Manage Your [Custom Domains](what-are-custom-domains.md) in the 'Custom Domain' Section of My Account. Add and Configure Your Own Branded Domains for a Personalized URL Shortening Experience

<figure><img src="../.gitbook/assets/Custom Domain - 1.jpg" alt=""><figcaption><p>Img 1 - Custom Domain Section under My Account</p></figcaption></figure>

Adding a [custom domain](what-are-custom-domains.md) to your Blinks.to account is a premium feature available to all users on our premium plan. Here's a step-by-step guide to setting up your custom domain:

1. Add a custom domain
2. Configure DNS records
3. Verify domain
4. Activate domain with SSL certificate



### <mark style="color:purple;">A. Adding Custom Domain</mark>

1. **Add Custom Domain:**
   * Click on 'Add Domain' to initiate the process.

<figure><img src="../.gitbook/assets/Custom Domain - 2 (1).jpg" alt=""><figcaption><p>Img 2 - Add Custom Domain</p></figcaption></figure>

2. Provide the Domain You Own to Use as a Custom Domain for URL Shortening.

{% hint style="warning" %}
Please Note: If Your Domain Is Currently Hosting a Website or Services, Integrating it with Blinks.to Will Involve Significant Changes to Your DNS Records. This Action Redirects Traffic from Your Existing Website or Services to Blinks.to's URL Shortening Service
{% endhint %}

<figure><img src="../.gitbook/assets/Custom Domain - 3 (1).jpg" alt=""><figcaption><p>Img 2 - Enter domain you own</p></figcaption></figure>

3. The newly added domain shows up in the list of "My Branded Domains" that you own

<figure><img src="../.gitbook/assets/List of custom domains.jpg" alt=""><figcaption><p>Img 3 - List of custom domains you own</p></figcaption></figure>

4. Now that you've added your custom branded domain, the next step is to verify it by configuring the DNS records with the token provided next to your corresponding domain. After the domain is active and verified, the buttons will turn green, indicating that your custom domain is ready for use



### <mark style="color:purple;">B. Configuring your custom Domain</mark>

To configure the custom domain, you need to update DNS records in your domain. You need to create 3 records as shown below

1. **"A Record"** : To point to IP address  216.24.57.1.&#x20;
2. **"TXT Record"**: Create txt record and paste the token provided
3. **"CNAME Record"**: To point to blinks.to

To set up your DNS record, you'll require access to your domain service provider. The configuration process may vary slightly among different service providers such as GoDaddy, Digital Ocean, Bluehost, BigRock, NameCheap, etc. However, the underlying concepts remain the same. Here's an example of configuring DNS records with identiti.design on NameCheap.

#### <mark style="color:orange;">**1. Login in to your domain service provider**</mark>&#x20;

<figure><img src="../.gitbook/assets/namecheap login.jpg" alt=""><figcaption><p>Img 4 - Login with credentials</p></figcaption></figure>

#### 2. Click on <mark style="color:orange;">**Manage**</mark> next to your domain

<figure><img src="../.gitbook/assets/namecheap - manage.jpg" alt=""><figcaption><p>Img 5 - Manage your domain</p></figcaption></figure>

#### <mark style="color:orange;">**3. Click on Advanced DNS**</mark>&#x20;

<figure><img src="../.gitbook/assets/namecheap - dns (1).jpg" alt=""><figcaption><p>Img 6 - Advanced DNS</p></figcaption></figure>

#### <mark style="color:orange;">**4. Configure the DNS A Record:**</mark>

* Click on Add New Record. Select A Record under Type for Value use "216.24.57.1". (Host as @)  Click the green tick mark to confirm. This connection ensures that your custom domain links directly to Blinks.to's URL shortening service.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-23 at 1.44.56 PM.jpg" alt=""><figcaption><p>Img 7 - Add A Record</p></figcaption></figure>

#### <mark style="color:orange;">**5. Add a DNS TXT Record:**</mark>

* In the 'My Branded Domains' section, the token for the domain you want to verify will be displayed. Click 'Copy Token' &#x20;

<figure><img src="../.gitbook/assets/Custom domain - copy token.jpg" alt=""><figcaption><p>Img 7 - Copy Authorization token</p></figcaption></figure>

<figure><img src="../.gitbook/assets/Screenshot 2024-02-23 at 1.49.38 PM.jpg" alt=""><figcaption><p>Img 8 - Token is copied</p></figcaption></figure>

* In NameCheap or your domain service provider, Create a new record type "TXT" and copy the token as the value. (Host as @).  Click on green tick mark to confirm

<figure><img src="../.gitbook/assets/txt record (1).jpg" alt=""><figcaption><p>Img 9 - Updated TXT Record with Token</p></figcaption></figure>

#### <mark style="color:orange;">**6. Add a CNAME Record:**</mark>

* Create a new record type "CNAME" and copy the value as "**blinksto.onrender.com.**" (Host as www)

<figure><img src="../.gitbook/assets/cname record.jpg" alt=""><figcaption><p>Img 10 - Updated CNAME record</p></figcaption></figure>

The final updated records for A, TXT and CNAME are as follows

<figure><img src="../.gitbook/assets/final records (1).jpg" alt=""><figcaption><p>Img 11 - Records for Domain Verification</p></figcaption></figure>

#### <mark style="color:orange;">**7. Verify Domain:**</mark>

* Once the DNS records are updated return to the blinks.to app and under My Branded Domains, click on verify next to the custom domain recently updated

<figure><img src="../.gitbook/assets/verify domain.jpg" alt=""><figcaption><p>Img 12 - Verify branded domain</p></figcaption></figure>

* If the DNS records are accurately updated and propagated within a few hours, your domain will be verified, and the status will change to 'Verified' in green

<figure><img src="../.gitbook/assets/veriried domain (1).jpg" alt=""><figcaption><p>Img 13 - Verified Domain</p></figcaption></figure>

#### <mark style="color:orange;">**8. Branded Domain Activation:**</mark>

* Once verified, we'll activate your domain with a free SSL certificate. This process may take up to 24 hours. Once activated, you can start using your custom domain to create shortened links.

<figure><img src="../.gitbook/assets/Domain activated.jpg" alt=""><figcaption><p>Img 14 - Domain Activated and ready to use</p></figcaption></figure>

**Congratulations 🎉 It might have been a challenging process, but your perseverance has paid off, and now you're on your way to creating branded shortened links.**
