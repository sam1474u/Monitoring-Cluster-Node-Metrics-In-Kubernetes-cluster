<!DOCTYPE html>
<!-- saved from url=(0122)https://oracle.github.io/learning-library/oci-library/oci-hol/cloud-native/workshops/freetier/index.html?lab=prerequisites -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<head>
</head>

<body style="">








<section><div name="STEP1:CreateYourFreeTrialAccount" data-unique="STEP1:CreateYourFreeTrialAccount"></div><h2 id="step1createyourfreetrialaccount" class="minus" tabindex="0"><strong>STEP 1</strong>: Create Your Free Trial Account</h2><p style="display: block;">If you already have a cloud account, skip to <strong>STEP 2</strong>.</p><ol style="display: block;">
<li><p>Open up a web browser to access the Oracle Cloud account registration form at <a href="https://myservices.us.oraclecloud.com/mycloud/signup?language=en" target="_blank">oracle.com/cloud/free</a>.</p></li>
<li><p>You will be presented with a registration page.
   <figure><img src="https://user-images.githubusercontent.com/42166489/108174321-4c22a680-7125-11eb-8d4d-9cba33694730.png" alt=""></figure></p></li>
<li><p>Enter the following information to create your Oracle Cloud Free Tier account.</p>
<ul>
<li>Choose your <strong>Country</strong></li>
<li>Enter your <strong>Name</strong> and <strong>Email</strong>.</li></ul></li>
<li><p>Once you have entered a valid email address, select the <strong>Verify my email</strong> button.
The screen will appear as follows after you select the button:
   <figure><img src="https://oracle.github.io/learning-library/common/labs/cloud-login/images/verify-email.png alt=""></figure></p></li>
<li><p>Go to your email. You will see an account validation email from Oracle in your inbox. The email will be similar to the following:
   <figure><img src="https://oracle.github.io/learning-library/common/labs/cloud-login/images/verification-mail.png" alt=""></figure></p></li>
<li><p>Select the link (if possible) or copy and paste the link into your browser.</p></li>
<li><p>Enter the following information to create your Oracle Cloud Free Tier account.</p>
<ul>
<li>Choose a <strong>Password</strong></li>
<li>Enter your <strong>Company Name</strong></li>
<li>Your <strong>Cloud Account Name</strong> will generate automatically based on your inputs, you can change that name by entering a new value. Remember what you wrote. You'll need this name later to sign in.</li>
<li>Choose a <strong>Home Region</strong>.  Your Home Region cannot be changed once you sign-up.</li>
<li>Click <strong>Continue</strong>
<figure><img src="https://oracle.github.io/learning-library/common/labs/cloud-login/images/account-info.png" alt=""></figure></li></ul></li>
<li><p>Enter your Address information.  Click <strong>Continue</strong>.
      <figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/cloud-native/setup-cloud-env/images/Introduction to Cloud Native _ Prerequisites_files/free-tier-address.png" alt=""></figure></p></li>
<li><p>Choose your country and enter a mobile member for verification.   Click the <strong>Text me a code</strong> button.</p>
<p><figure><img src="https://oracle.github.io/learning-library/common/labs/cloud-login/images/free-tier-address-2.png" alt=""></figure></p></li>
<li><p>Once you receive your code, enter it and click <strong>Verify My Code</strong>.
   <figure><img src="https://oracle.github.io/learning-library/common/labs/cloud-login/images/free-tier-address-4.png" alt=""></figure></p></li>
<li><p>Click the <strong>Add payment verification method</strong> button.
   <figure><img src="https://oracle.github.io/learning-library/common/labs/cloud-login/images/free-tier-payment-1.png" alt=""></figure>  </p></li>
<li><p>Choose the verification method.  In this case click the <strong>Credit Card</strong> button. Enter your information and payment details.  <em>Note: This is a free credit promotion account. You will not be charged unless you elect to upgrade the account</em>.
   <figure><img src="https://oracle.github.io/learning-library/common/labs/cloud-login/images/free-tier-payment-2.png" alt=""></figure></p></li>
<li><p>Once your payment verification is complete.  Review and accept the agreement by clicking the check box.  Click the <strong>Start my free trial</strong> button.
   <figure><img src="https://oracle.github.io/learning-library/common/labs/cloud-login/images/free-tier-agreement.png" alt=""></figure></p></li>
<li><p>Your account is provisioning and should be available in a few seconds! When it's ready, you're automatically taken to a sign-in page. You'll also receive two emails from Oracle. One email will be the initial notification that provisioning is underway. The other email will be notification that provisioning is complete. Here is a copy of the final notification:
   <figure><img src="https://oracle.github.io/learning-library/common/labs/cloud-login/images/account-provisioned.png" alt=""></figure></p></li>
</ol></section>

<section><div name="STEP2:SignintoYourAccount" data-unique="STEP2:SignintoYourAccount"></div><h2 id="step2signintoyouraccount" class="minus" tabindex="0"><strong>STEP 2</strong>: Sign in to Your Account</h2><p style="">If you've signed out of the Oracle Cloud, use these steps to sign back in.</p><ol style="">
<li><p>Go to <a href="https://cloud.oracle.com" target="_blank">cloud.oracle.com</a> and Enter your Cloud Account Name and click <strong>Next</strong>. This is the name you chose while creating your account in the previous section. It's NOT your email address. If you've forgotten the name, see the confirmation email.</p>
<p><figure><img src="https://oracle.github.io/learning-library/common/labs/cloud-login/images/cloud-oracle.png" alt=""></figure></p></li>
<li><p>Expand the arrow after <em>"Oracle Cloud Infrastructure Direct Sign-In"</em> to reveal the login input fields.</p>
<p><figure><img src="https://oracle.github.io/learning-library/common/labs/cloud-login/images/cloud-login-tenant.png" alt=""></figure></p></li>
<li><p>Enter your Cloud Account credentials and click <strong>Sign In</strong>. Your username is your email address. The password is what you chose when you signed up for an account.</p>
<p><figure><img src="https://oracle.github.io/learning-library/common/labs/cloud-login/images/oci-signin.png" alt=""></figure></p></li>
<li><p>You are now signed in to Oracle Cloud!</p>
<p><figure><img src="https://oracle.github.io/learning-library/common/labs/cloud-login/images/oci-console-home-page.png" alt=""></figure></p></li>
</ol><p style="">You may now <a href="#next">proceed to the next lab</a>.</p></section>

<main class="hol-Content" id="module-content"><article><h1 id="setupcloudenvironment">Setup Cloud Environment</h1>
<section><div name="Introduction" data-unique="Introduction"></div><h2 id="introduction">Introduction</h2><p>You will take on the persona of an Operations Engineer. You will initiate the Oracle cloud environment that will be used to create and deploy your microservices applications. This environment will be contained within a cloud Compartment, and communication within the Compartment will be via a Virtual Cloud Network (VCN). The Compartment and VCN will isolate and secure the overall environment. You will deploy the Oracle Cloud Infrastructure Container Engine for Kubernetes(OKE).</p><p>Estimated time: 20 minutes</p><h3 id="objectives">Objectives</h3><ul>
<li>Log into OCI Tenancy.</li>
<li>Setup Oracle Cloud Infrastructure (OCI) components.  </li>
</ul><p><strong><em>We recommend that you create a notes page to write down all of the credentials you will need.</em></strong></p><h3 id="prerequisites">Prerequisites</h3><ul>
<li>Your Oracle Cloud Trial Account</li>
<li>You have already applied for and received your Oracle Cloud Free Tier Account.</li>
</ul><p><em>In addition to the workshop</em>, feel free to watch the walkthrough companion video by clicking on the following image:
<div class="video-container"><iframe src="https://www.youtube.com/embed/wIoLDX7iWXo?start=0&amp;end=60" frameborder="0" allowfullscreen=""></div></iframe></div></p></section>








<section><div name="STEP1:LogintoOCITenancy" data-unique="STEP1:LogintoOCITenancy"></div><button id="btn_toggle" class="hol-ToggleRegions minus">Collapse All Steps</button><h2 id="step1logintoocitenancy" class="minus" tabindex="0"><strong>STEP 1:</strong> Log into OCI Tenancy</h2><p style="">Log in to your OCI dashboard and retrieve information required to create resources.</p><ol style="">
<li><p>From any browser go to oracle.com to access the Oracle Cloud.</p>
<p><a href="https://www.oracle.com/" target="_blank">https://www.oracle.com/</a></p>
<p><figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/cloud-native/setup-cloud-env/images/login-screen.png" alt="Login Screen"></figure></p></li>
<li><p>Click the icon in the upper right corner.  Click on <strong>Sign in to Cloud</strong>.</p>
<p><figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/cloud-native/setup-cloud-env/images/signup.png" alt="Signup"></figure></p></li>
<li><p>Enter your <strong>Cloud Account Name</strong> in the input field and click the <strong>Next</strong> button.  <em>NOTE: this is NOT your email. This is the name of your tenancy noted in the email you received during signup. Do NOT click the Sign-In button, this will take you to Single Sign-On, not the Oracle Cloud.</em></p>
<p><figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/cloud-native/setup-cloud-env/images/cloud-login-tenant.png" alt="Cloud Login"></figure></p></li>
<li><p>Enter your username (this may be your email address) and password and click on <strong>Sign In</strong>.  </p>
<p><figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/cloud-native/setup-cloud-env/images/username.png" alt="Username"></figure></p></li>
<li><p>Once you log in you will see a page similar to the one below. Click on "Infrastructure Dashboard."</p>
<p><figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/cloud-native/setup-cloud-env/images/landingScreen2.png" alt="Landing Screen"></figure></p></li>
</ol></section>


<section><div name="STEP2:BasicOCIInfrastructureSetup" data-unique="STEP2:BasicOCIInfrastructureSetup"></div><h2 id="step2basicociinfrastructuresetup" class="minus" tabindex="0"><strong>STEP 2:</strong> Basic OCI Infrastructure Setup</h2><ol style="">
<li><p>Open the navigation menu. Under Governance and Administration, go to <strong>Identity</strong> and click <strong>Compartments</strong>. From this screen, you will see a list of compartments, click <strong>Create Compartment</strong>.</p>
<p><figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/cloud-native/setup-cloud-env/images/OCI-1.png" alt="Menu Compartments"></figure></p>
<p><figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/cloud-native/setup-cloud-env/images/compartmentScreen.png" alt="Compartment Screen"></figure></p></li>
<li><p>Enter the following:</p>
<ul>
<li>Name: Enter <strong>"AppDev".</strong></li>
<li>Description: Enter a description (required), for example: "AppDev compartment for the getting started tutorial". Avoid entering confidential information.</li>
<li>Parent Compartment: Select the compartment you want this compartment to reside in. Defaults to the root compartment (or tenancy).</li>
<li>Click <strong>Create Compartment</strong>.</li>
<li>Your compartment is displayed in the list.</li></ul>
<p><figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/cloud-native/setup-cloud-env/images/compartment-create.png" alt="AppDev Compartment"></figure></p></li>
<li><p>Click the Cloud Shell icon in the Console header. Note that the OCI CLI running in the Cloud Shell will execute commands against the region selected in the Console's Region selection menu when the Cloud Shell was started.</p>
<p><figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/cloud-native/setup-cloud-env/images/cloudshell-1.png" alt="CloudShell"></figure></p>
<p><figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/cloud-native/setup-cloud-env/images/cloudshell-2.png" alt="CloudShell"></figure></p></li>
</ol><p style="">Now you are ready to move on to Step 3.</p></section>


<section><div name="STEP3:CreateOKEKubernetesCluster" data-unique="STEP3:CreateOKEKubernetesCluster"></div><h2 id="step3createokekubernetescluster" class="minus" tabindex="0"><strong>STEP 3:</strong> Create OKE Kubernetes Cluster</h2><ol style="">
<li><p>To create an OKE cluster, open up the hamburger button in the top-left corner of the Console and go to <strong>Developer Services</strong> &gt;   <strong>Kubernetes Clusters</strong>.</p>
<p><figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/cloud-native/setup-cloud-env/images/OKE-clusters-menu.png" alt="Kubernetes Clusters Menu"></figure></p></li>
<li><p>Verify you are in the <strong>AppDev</strong> Compartment and click <strong>Create Cluster</strong>.</p>
<p><figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/cloud-native/setup-cloud-env/images/createCluster.png" alt="Compartment"></figure></p></li>
<li><p>Choose Quick Create as it will create the new cluster along with the new network resources such as Virtual Cloud Network (VCN), Internet Gateway (IG), NAT Gateway (NAT), Regional Subnet for worker nodes, and a Regional Subnet for load balancers. Select <strong>Launch Workflow</strong></p>
<p><figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/cloud-native/setup-cloud-env/images/OKE-create-cluster.png" alt="Quick Create Cluster"></figure></p></li>
<li><p>Keep the name to <strong>cluster1</strong> and the other default values, click Next to review the cluster settings<br>
<sup><em>Optionally choose visibility type to <strong>Public</strong> if you want public access to your nodes and number of nodes to <strong>2</strong> or <strong>1</strong> if you want reduced number of nodes</em></sup></p>
<p><figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/cloud-native/setup-cloud-env/images/OKE-create-cluster-details.png" alt="Cluster Details"></figure></p></li>
<li><p>Review the the Cluster Creation and then select <strong>Create Cluster</strong>.</p>
<p><figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/cloud-native/setup-cloud-env/images/OKE-create-cluster-details-review.png" alt="Cluster Info"></figure></p></li>
<li><p>Once launched it should usually take around 5-10 minutes for the cluster to be fully provisioned and display an Active.</p></li>
</ol></section>

<section><div name="STEP4:SetupOKEKubernetesClusterCloudShellAccess" data-unique="STEP4:SetupOKEKubernetesClusterCloudShellAccess"></div><h2 id="step4setupokekubernetesclustercloudshellaccess" class="minus" tabindex="0"><strong>STEP 4:</strong> Setup OKE Kubernetes Cluster Cloud Shell Access</h2><ol style="">
<li><p>On the <strong>Clusters</strong> view, select the just created cluster and then click on the <strong>Access Cluster</strong> button.</p>
<p><figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/cloud-native/setup-cloud-env/images/OKE-access-cluster.png" alt="Access Cluster"></figure></p></li>
<li><p>Leave the <strong>Cloud Shell Access</strong> selected. If Cloud Shell is not already open, <strong>Launch Cloud Shell</strong>, copy the oci cli command to create the kubeconfig and paste on the Cloud Shell Terminal.</p>
<p><figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/cloud-native/setup-cloud-env/images/OKE-access-cluster-cli.png" alt="Access Cluster"></figure></p>
<p><figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/cloud-native/setup-cloud-env/images/OKE-cloud-shell-create-kubeconfig.png" alt="Access Cluster"></figure></p></li>
<li><p>Check if you have access to your cluster with <code>kubectl</code>.</p>
<pre><button class="copy-button" title="Copy text to clipboard">Copy</button><code class="shell language-shell"><span class="copy-code">kubectl get cs</span>
</code></pre>
<pre><code class="shell language-shell">NAME                 STATUS    MESSAGE             ERROR
scheduler            Healthy   ok
controller-manager   Healthy   ok
etcd-0               Healthy   {"health":"true"}
</code></pre></li>
<li><p>Check the version of your kubectl client and kubernetes server with <code>kubectl</code>.</p>
<pre><button class="copy-button" title="Copy text to clipboard">Copy</button><code class="shell language-shell"><span class="copy-code">kubectl version</span>
</code></pre></li>
<li><p>Get the nodes and check if they are <em>Ready</em> with <code>kubectl</code>.</p>
<pre><button class="copy-button" title="Copy text to clipboard">Copy</button><code class="shell language-shell"><span class="copy-code">kubectl get nodes</span>
</code></pre>
<pre><code class="shell language-shell">NAME        STATUS   ROLES   AGE   VERSION
10.0.10.2   Ready    node    1m    v1.17.9
10.0.10.3   Ready    node    1m    v1.17.9
10.0.10.4   Ready    node    1m    v1.17.9
</code></pre></li>
</ol><p style="">You may now <a href="#next">proceed to the next lab</a>.</p></section>


<section><div name="Acknowledgements" data-unique="Acknowledgements"></div><h2 id="acknowledgements" class="minus" tabindex="0">Acknowledgements</h2><ul style="">
<li><strong>Author</strong> - Satyajeet Joshi</li>
<li><strong>Contributors</strong> -  Kamryn Vinson, Adao Junior</li>
<li><strong>Last Updated By/Date</strong> - Adao Junior, October 2020</li>
</ul></section>

<section><div name="NeedHelp?" data-unique="NeedHelp?"></div><h2 id="needhelp" class="minus" tabindex="0">Need Help?</h2><p style="">Please submit feedback or ask for help using our <a href="https://community.oracle.com/tech/developers/categories/livelabsdiscussions" target="_blank">LiveLabs Support Forum</a>. Please click the <strong>Log In</strong> button and login using your Oracle Account. Click the <strong>Ask A Question</strong> button to the left to start a <em>New Discussion</em> or <em>Ask a Question</em>.  Please include your workshop name and lab name.  You can also include screenshots and attach files.  Engage directly with the author of the workshop.</p><p style="">If you do not have an Oracle Account, click <a href="https://profile.oracle.com/myprofile/account/create-account.jspx" target="_blank">here</a> to create one.   Please include the workshop name   and lab in your request.</p></section>

</article></main>

</article>
</body></html>
