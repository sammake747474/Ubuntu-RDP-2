# [GitHub Action CRD (Chrome Remote Desktop)](https://github.com/r3xzt/GitHub-Action-CRD)

## **!!! IMPORTANT !!!**
Actions should not be used for:
* Cryptomining
* Using our servers to disrupt, or to gain or to attempt to gain unauthorized access to, any service, device, data, account, or network (other than those authorized by the GitHub Bug Bounty program)
* The provision of a stand-alone or integrated application or service offering Actions or any elements of Actions for commercial purposes
* Any activity that places a burden on our servers, where that burden is disproportionate to the benefits provided to users (for example, don't use Actions as a content delivery network or as part of a serverless application, but a low benefit Action could be ok if it’s also low burden)
* Any other activity unrelated to the production, testing, deployment, or publication of the software project associated with the repository where GitHub Actions are used.

I don't accept any responsibility.

## Available VMs
* Ubuntu 20.04
* Ubuntu 18.04
* Windows Server 2019
* Windows Server 2016

## Usage
### First use
1. Click `Fork` to create a new repository from GitHub-Action-VM.

### Start
1. Go to [https://remotedesktop.google.com/headless](https://remotedesktop.google.com/headless).
2. `Begin` > `Next` > `Authorize` > Copy command. ( [Which command?](#which-command) )
3. Go to `Actions` > (The VM you want to use. ex. Windows Server 2019) > `Run workflow` > `Run workflow`.
4. Reload and click the latest Workflow runs.
5. Wait until `Start Chrome Remote Desktop` end.
6. Done! You can see the machine in list now.
* When you're done introspecting, cancel the job.

### Which command?
* Windows Server 2019 > `Windows (PowerShell)`
* Windows Server 2016 > `Windows (PowerShell)`
* Ubuntu 20.04 > `Debian Linux`
* Ubuntu 18.04 > `Debian Linux`
