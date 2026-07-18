# Cloud Security with AWS IAM
<p>Love Alexa M. Lazo | July 2026 </p>

<br>

<img width="245" height="230" alt="image" src="https://github.com/user-attachments/assets/9e3b4ec0-52d5-4bbf-bffd-66b0d39fe491" />

## Introducing Today's Project!
### Project overview
<p>In this project, I will demonstrate IAM. I'm doing this project to learn authentication in my account.</p>

### Tools and concepts
<p>I learned concepts about EC2, IAM user, and IAM groups.</p>

### Project reflection
<p>This project took me approximately an hour.</p>

<br>

## Tags
### What I did in this step
<p>In this step, I will launch two Amazon EC2 instances to increase because it should boost the computing power.</p>

### Understanding tags. 
<p>Tags are used for organization and labeling.</p>

### My tag configuration
<p>The tag I’ve used on my EC2 instances is called env. The value I’ve assigned for my instances are production and development.</p>
<img width="312" height="65" alt="image" src="https://github.com/user-attachments/assets/0083c835-f380-4c8d-b53b-240b1823af20" />

<br>

## IAM Policies
### What I did in this step
<p>In this step, I will create an IAM policy because it gives access to the development instance.</p>

### Understanding IAM policies
<p>IAM Policies are rules on what to do with the AWS account and its resources. It gives permissions on what to do on certain resources.</p>

### The policy I set up
<p>For this project, I’ve set up a policy using JSON.</p>

### Policy effect
<p>I’ve created a policy that allows all EC2 instances under "Action". </p>

### Understanding Effect, Action, and Resource
<p>The Effect, Action, and Resource attributes of a JSON policy means that it is a set of rules that allows for an action to take place through a step-by-step syntax.</p>

### My JSON Policy
<img width="200" height="188" alt="image" src="https://github.com/user-attachments/assets/8dbe353a-5bdc-4c20-8eae-cb8bceb1282f" />

<br>

## Account Alias
### What I did in this step
<p>In this step, I will log in to my AWS account using an Account Alias because it simplifies user login.</p>

### Understanding account aliases
<p>An account alias is used to simplify log in.</p>

### Setting up my account alias
<p>Creating an account alias took me a few minutes. Now, my new AWS console sign-in URL is https://230352786467.signin.aws.amazon.com/console</p>
<img width="309" height="180" alt="image" src="https://github.com/user-attachments/assets/e6ffe078-f1c3-4ba2-a151-385aa1b8e021" />

<br>

## IAM Users and User Groups
### What I did in this step
<p>In this step, I will setup a dedicated IAM group and user because it manages permissions and have a way to log in.</p>

### Understanding user groups
<p>IAM user groups are is a collection/folder of IAM users.</p>

### Attaching policies to user groups
<p>I attached the policy I created to this user group, which means it can manage permissions to my AWS account.</p>

### Understanding IAM users
<p>IAM users are people that will get access to the AWS account.</p>

<br>

## Logging in as an IAM User
### Sharing sign-in details
<p>The first way is  setting up an IAM group and IAM user.</p>

### Observations from the IAM user dashboard
<p>Once I logged in as my IAM user, I noticed some of the dashboard panels are showing access denied. This was because the user does not have permission.</p>
<img width="314" height="154" alt="image" src="https://github.com/user-attachments/assets/e5a3d677-2397-4d79-88ab-1a95d8bf8730" />

<br>

## Testing IAM Policies
### What I did in this step
<p>In this step, I will log into AWS using IAM user because I need to test the intern's access to production and development instance.</p>

### Testing policy actions
<p>I tested my JSON IAM policy by managing the instance state.</p>

### Stopping the production instance
<p>When I tried to stop the production instance it had an error. This was because we are not authorized.</p>
<img width="314" height="88" alt="image" src="https://github.com/user-attachments/assets/24a70d2a-e6df-47d0-ae71-53080b404c84" />

### Stopping the development instance
<p>Next, when I tried to stop the development instance, it had no errors. This was because we have permissions.</p>
<img width="317" height="68" alt="image" src="https://github.com/user-attachments/assets/f4be1b6f-f7c8-46ee-8bcf-38ac0f277c4b" />



