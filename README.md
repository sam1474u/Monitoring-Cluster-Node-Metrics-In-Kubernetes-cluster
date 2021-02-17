# mushop
Prerequisites
Introduction
Before you get started, you will need an Oracle Cloud account. This 5-minute lab walks you through the steps of getting an Oracle Cloud Free Tier account and signing in.

Existing Cloud Accounts
If you already have access to an Oracle Cloud account, including an Oracle Cloud account using Oracle Universal Credits, skip to STEP 2 to sign in to your cloud tenancy.

Two Cloud Offers in One
Oracle Cloud Free Tier allows you to sign up for an Oracle Cloud account which provides a number of Always Free services and a Free Trial with US$300 of free credit to use on all eligible Oracle Cloud Infrastructure services for up to 30 days. The Always Free services are available for an unlimited period of time. The Free Trial services may be used until your US$300 of free credits are consumed or the 30 days has expired, whichever comes first.



What you will need
A valid email address
Ability to receive SMS text verification (only if your email isn't recognized)

STEP 1: Create Your Free Trial Account
If you already have a cloud account, skip to STEP 2.

Open up a web browser to access the Oracle Cloud account registration form at oracle.com/cloud/free.

You will be presented with a registration page.


Enter the following information to create your Oracle Cloud Free Tier account.

Choose your Country
Enter your Name and Email.
Once you have entered a valid email address, select the Verify my email button. The screen will appear as follows after you select the button:


Go to your email. You will see an account validation email from Oracle in your inbox. The email will be similar to the following:


Select the link (if possible) or copy and paste the link into your browser.

Enter the following information to create your Oracle Cloud Free Tier account.

Choose a Password
Enter your Company Name
Your Cloud Account Name will generate automatically based on your inputs, you can change that name by entering a new value. Remember what you wrote. You'll need this name later to sign in.
Choose a Home Region. Your Home Region cannot be changed once you sign-up.
Click Continue

Enter your Address information. Click Continue.


Choose your country and enter a mobile member for verification. Click the Text me a code button.



Once you receive your code, enter it and click Verify My Code.


Click the Add payment verification method button.

STEP 2: Sign in to Your Account
If you've signed out of the Oracle Cloud, use these steps to sign back in.

Go to cloud.oracle.com and Enter your Cloud Account Name and click Next. This is the name you chose while creating your account in the previous section. It's NOT your email address. If you've forgotten the name, see the confirmation email.



Expand the arrow after "Oracle Cloud Infrastructure Direct Sign-In" to reveal the login input fields.



Enter your Cloud Account credentials and click Sign In. Your username is your email address. The password is what you chose when you signed up for an account.



You are now signed in to Oracle Cloud!



Choose the verification method. In this case click the Credit Card button. Enter your information and payment details. Note: This is a free credit promotion account. You will not be charged unless you elect to upgrade the account.


Once your payment verification is complete. Review and accept the agreement by clicking the check box. Click the Start my free trial button.


Your account is provisioning and should be available in a few seconds! When it's ready, you're automatically taken to a sign-in page. You'll also receive two emails from Oracle. One email will be the initial notification that provisioning is underway. The other email will be notification that provisioning is complete. Here is a copy of the final notification:


Setup Cloud Environment
Introduction
You will take on the persona of an Operations Engineer. You will initiate the Oracle cloud environment that will be used to create and deploy your microservices applications. This environment will be contained within a cloud Compartment, and communication within the Compartment will be via a Virtual Cloud Network (VCN). The Compartment and VCN will isolate and secure the overall environment. You will deploy the Oracle Cloud Infrastructure Container Engine for Kubernetes(OKE).

Estimated time: 20 minutes

Objectives
Log into OCI Tenancy.
Setup Oracle Cloud Infrastructure (OCI) components.
We recommend that you create a notes page to write down all of the credentials you will need.

Prerequisites
Your Oracle Cloud Trial Account
You have already applied for and received your Oracle Cloud Free Tier Account.
In addition to the workshop, feel free to watch the walkthrough companion video by clicking on the following image:


STEP 1: Log into OCI Tenancy

Log in to your OCI dashboard and retrieve information required to create resources.

From any browser go to oracle.com to access the Oracle Cloud.

https://www.oracle.com/

Login Screen

Click the icon in the upper right corner. Click on Sign in to Cloud.

Signup

Enter your Cloud Account Name in the input field and click the Next button. NOTE: this is NOT your email. This is the name of your tenancy noted in the email you received during signup. Do NOT click the Sign-In button, this will take you to Single Sign-On, not the Oracle Cloud.

Cloud Login

Enter your username (this may be your email address) and password and click on Sign In.

Username

Once you log in you will see a page similar to the one below. Click on "Infrastructure Dashboard."

Landing Screen

STEP 2: Basic OCI Infrastructure Setup

STEP 2: Basic OCI Infrastructure Setup
Open the navigation menu. Under Governance and Administration, go to Identity and click Compartments. From this screen, you will see a list of compartments, click Create Compartment.

Menu Compartments

Compartment Screen

Enter the following:

Name: Enter "AppDev".
Description: Enter a description (required), for example: "AppDev compartment for the getting started tutorial". Avoid entering confidential information.
Parent Compartment: Select the compartment you want this compartment to reside in. Defaults to the root compartment (or tenancy).
Click Create Compartment.
Your compartment is displayed in the list.
AppDev Compartment

Click the Cloud Shell icon in the Console header. Note that the OCI CLI running in the Cloud Shell will execute commands against the region selected in the Console's Region selection menu when the Cloud Shell was started.

CloudShell

CloudShell

Now you are ready to move on to Step 3.

STEP 3: Create OKE Kubernetes Cluster
To create an OKE cluster, open up the hamburger button in the top-left corner of the Console and go to Developer Services > Kubernetes Clusters.

Kubernetes Clusters Menu

Verify you are in the AppDev Compartment and click Create Cluster.

Compartment

Choose Quick Create as it will create the new cluster along with the new network resources such as Virtual Cloud Network (VCN), Internet Gateway (IG), NAT Gateway (NAT), Regional Subnet for worker nodes, and a Regional Subnet for load balancers. Select Launch Workflow

Quick Create Cluster

Keep the name to cluster1 and the other default values, click Next to review the cluster settings
Optionally choose visibility type to Public if you want public access to your nodes and number of nodes to 2 or 1 if you want reduced number of nodes

Cluster Details

Review the the Cluster Creation and then select Create Cluster.

Cluster Info

Once launched it should usually take around 5-10 minutes for the cluster to be fully provisioned and display an Active.

STEP 4: Setup OKE Kubernetes Cluster Cloud Shell Access
On the Clusters view, select the just created cluster and then click on the Access Cluster button.

Access Cluster

Leave the Cloud Shell Access selected. If Cloud Shell is not already open, Launch Cloud Shell, copy the oci cli command to create the kubeconfig and paste on the Cloud Shell Terminal.

Access Cluster

Access Cluster

Check if you have access to your cluster with kubectl.

Copykubectl get cs
NAME                 STATUS    MESSAGE             ERROR
scheduler            Healthy   ok
controller-manager   Healthy   ok
etcd-0               Healthy   {"health":"true"}
Check the version of your kubectl client and kubernetes server with kubectl.

Copykubectl version
Get the nodes and check if they are Ready with kubectl.

Copykubectl get nodes
NAME        STATUS   ROLES   AGE   VERSION
10.0.10.2   Ready    node    1m    v1.17.9
10.0.10.3   Ready    node    1m    v1.17.9
10.0.10.4   Ready    node    1m    v1.17.9
