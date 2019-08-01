# aws-pwsh
Powershell with AWSPowershell and other tools to help with debugging. Some of the things configured are as follows

* bash
* AWSPowershell
* curl
* jq
* vim-tiny

## Build

```
docker build -t alchen99/aws-pwsh .
```

Automated build on Docker Hub

[![DockerHub Badge](http://dockeri.co/image/alchen99/aws-pwsh)](https://hub.docker.com/r/alchen99/aws-pwsh/)

## Usage

Configure:

```
Set-AWSCredential -AccessKey AKIAIOSFODNN7EXAMPLE -SecretKey wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY -StoreAs default
```

## References

* AWS Tools for Windows Powershell: https://docs.aws.amazon.com/powershell/latest/userguide/pstools-getting-started.html
* jq Manual: https://stedolan.github.io/jq/manual/
* jq Tutorial: https://stedolan.github.io/jq/tutorial/
