# Configure GIT
<p>We are going to learn about how to configure Git.</p>

### Introduction
<p>You must have an account on github.com to perform the git configure.</p>

This lab has three subsection, namely:
<li>Configuring Git with username and email id</li>
<li>Confirming the username and email id</li>
<li>Enabling credentials storage globally</li>


#### <b>Step 1:</b> Configuring the username and email id. (Execute the following commands in the terminal)
`$ git config --global user.name "USERNAME"`<br>
`$ git config --global user.email "USERMAIL"`

![git config user.name](https://github.com/prakashgkhaire/SimplilearnGitHubProject/blob/main/images/step%201.jpg)

<p>After successfully configuring username and email id. Let us verify it, perform the step 2 as given below.</p>

#### <b>Step 2:</b> Confirming the username and email id
`$ git config --global user.name`<br>
`$ git config --global user.email`

![git global user.name](https://github.com/prakashgkhaire/SimplilearnGitHubProject/blob/main/images/step%202.jpg)

<p>When Git needs authentication for a particular URL context, credential-store will consider that context a pattern to match against each entry in the credentials file. If the protocol, hostname, and username (if we already have one) match, then the password is returned to Git.</p>

#### <b>Step 3:</b> Enabling credentials storage globally
`$ git config --global credential.helper store`

![git credential](https://github.com/prakashgkhaire/SimplilearnGitHubProject/blob/main/images/step%203.jpg)
