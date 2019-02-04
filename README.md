The goal of this repo is to serve as a starting point for comparison between existing file sharing services,
and as a place to outline the desired set of features.

* Version histories / snapshots with per folder configuration of frequency
* Per user permissions, where users are not tied to the local machine user but instead exist within the context of the service.
* Both local and cloud storage devices can be backup targets. In other words, I should be able to backup to S3, and the machine behind the couch.
* Per file / folder / machine selectivity for if that file should be synced or not
* Clear reporting of backup state of files across all systems
* Not cost $$$$, removing the cloud storage and instead just using the local machine is a valid option for this, as long as there is a way to make the local machine (given correct network setup etc) accessible as a backup location while on the road with the laptops.
* Cross platform support.
* Sharable link based file sharing for both files and folders in order to easily share media with people. Probably ok if links are read-only permissions.
* Bonus: Integrations with existing Drive / DropBox / iCloud / whatever you are already paying for. -> Not 100% sold on this, but I would be interested in your thoughts


**What already exisits?:**\
Listed below are short descriptions about the services that are offered at a varitity of cloud based storage (and more) providers.

Summery table of results:
service | per user permissions | version history | local and cloud targets | per folder | per machine | sharable link |
|--|--|--|--|--|--|--|
| GCS | ? | ? | ? | ? | ? | ?
| AWS | ? | ? | ? | ? | ? | ?
| Next cloud | ? | ? | ? | ? | ? | ?
| DropBox | ? | ? | ? | yes | yes | ?
| Box | yes | yes | no | yes | yes* | yes
| Google Drive | ? | ? | ? | ? | ? | yes
| Amazon Cloud Drive | ? | ? | ? | ? | ? | yes
| OneDrive | ? | ? | ? | ? | ? | ?
| BackBlaze | ? | ? | ? | ? | ? | ?

*only if you adjust the setting locally

***Google Cloud Services***

***Amazon AWS Microsoft Azure***

***Next Cloud***

***DropBox***
Dropbox is possibly the original file sharing tool. It requres installing the dropbox utility on each machine, but once setup allows for syncing files between all computers, as well as allowing for setting sync status of each file.

***Box***


***Google Drive***

***Amazon Cloud Drive***

***Microsoft One Drive***

***Backblaze***

