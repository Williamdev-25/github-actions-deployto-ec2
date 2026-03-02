This repository was used during the teaching of GITHUB ACTIONS
So, do not expect any serious information or deployments here.
It is made public for the reference of Students




For the ECR private pipeline, you put in permissions with a comment that "Required for OIDC authentication with AWS" but you're not using OIDC for authentication. You're actually using Access Keys and ID. 

More so, you did not integrate SAST scan into the pipelines and matched the various obfuscations to the various SOC 2 controls. 
