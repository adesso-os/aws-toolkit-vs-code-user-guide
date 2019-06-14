# Configure Your Toolchain<a name="setup-toolchain"></a>

AWS Toolkit for Visual Studio Code supports multiple languages that can be used to interact with AWS\. The following sections, "Configure Your Toolchain\.\.\.", describe how to set up the toolchain for each of these languages\.

## Configure Your Toolchain for \.NET Core<a name="setup-toolchain-for-net"></a>

1. Ensure that the AWS Toolkit for Visual Studio Code is [installed](setup-toolkit.md#setup-install)\.

1. Install the [C\# extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode.csharp)\. This extension gives VS Code the ability to debug \.NET Core applications\.

1. Launch VS Code and open a SAM application or [create a new one](create-sam.md#create-serverless-app)\.
**Note**  
Open the folder that contains `template.yaml`\.

## Configure Your Toolchain for Node\.js<a name="setup-toolchain-for-node"></a>

1. Ensure that the AWS Toolkit for Visual Studio Code is [installed](setup-toolkit.md#setup-install)\.

1. Launch VS Code and open a SAM application or [create a new one](create-sam.md#create-serverless-app)\.
**Note**  
Open the folder that contains `template.yaml`\.

## Configure Your Toolchain for Python<a name="setup-toolchain-for-python"></a>

1. Ensure that the AWS Toolkit for Visual Studio Code is [installed](setup-toolkit.md#setup-install)\.

1. Install the [Python extension for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-python.python)\. This extension gives VS Code the ability to debug Python applications\.

1. Launch VS Code and open a SAM application or [create a new one](create-sam.md#create-serverless-app)\.
**Note**  
Open the folder that contains `template.yaml`\.

1. Open a terminal at the root of your application and configure `virtualenv` by running `python -m venv ./.venv`\.
**Note**  
`virtualenv` needs to be configured only once per system\.

1. Activate `virtualenv` by running one of the following:
   + Bash shell: `./.venv/Scripts/activate`
   + PowerShell: `./.venv/Scripts/Activate.ps1`