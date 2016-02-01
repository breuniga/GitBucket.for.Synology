# GitBucket.for.Synology

[GitBucket](https://github.com/gitbucket/gitbucket) is a GitHub clone powered by Scala which has easy installation and high extensibility.

GitBucket.for.Synology packages the gitbucket.war file from https://github.com/gitbucket/gitbucket into a spk-package for installation in the Synology NAS.
## GitBucket's license
see https://github.com/takezoe/gitbucket

## Installation
GitBucket requires Java installed on the Synology NAS. You can install Java7 via the Java Manager from Synology Inc.

1. Download the latest [release](https://github.com/breuniga/GitBucket.for.Synology/releases/tag/v3.10.1_h2-1.4.180_syno-01)
2. Login to your Synology NAS with administrator rights
3. Open the Package Manager
4. Click on *Manual Install* and select the downloaded package.
5. When installation is completed, you can access GitBucket via the Synology Main Menu or directly by http(s)://yourNAS:8080
