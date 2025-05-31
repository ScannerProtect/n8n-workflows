# n8n-workflows
n8n workflow json files and tutorial for scannerprotect.de

More information at https://scannerprotect.de and [the documentation on GitHub](https://github.com/ScannerProtect/scannerprotect-docs).

## How to set up your workflow

1) Create an account on n8n.io or on a self-hosted n8n instance.

2) Go to the n8n dashboard.

3) Create credentials for SMTP to be used in the "Send Email" node later.

4) Import the workflow file for your language.

5) Fill out the fields "from", "to" and optionally "bcc" in the "Edit Fields" node (aka the "Set" node).

6) Connect your SMTP credentials to the "Send Email" node. This may happen automatically upon just opening the edit dialog of the node if you created the credentials in n8n before importing the workflow file and if you only have one set of SMTP credentials. Otherwise, select the correct credentials from the dropdown list.

7) Test the node.
  
8) If everything worked: Save the workflow and set it to active.

9) Re-test with the "production" webhook (the same webhook without "-test").
