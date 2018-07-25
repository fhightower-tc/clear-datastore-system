# Clear Datastore Contents Playbook System

This system provides a playbook and component which lets you delete all of the data from the datastore at a given store name<sup>[1](#footnote1)</sup>

## Installation

To install this system, download the playbook (`[utility] [clear datastore] Clear Entry from Datastore.pbx`) and the component (`[utility] [clear datastore] Clear Datastore.pbx`) which are in this repository and import them into your instance of ThreatConnect. Refer to the next section for usage instructions.

## Usage

Once you have the playbook and component from this repository installed in ThreatConnect, there are three steps to make use this system.

1. Turn on the playbook (`[utility] [clear datastore] Clear Entry from Datastore`) - this may require you to fill out some of the values in some of the apps (especially the datastore app).
2. Turn on the component (`[utility] [clear datastore] Clear Datastore`) - this may require you to fill out some of the values in some of the apps (especially the datastore app).
3. Use the component in a playbook by adding it and providing the name of the datastore you would like to clear.

## Caveat Emptor (or "Caveat User") ~ Warnings

This system will **permanently** delete everything in the **organization's** datastore from the store name you provide (this is like an `rm -fr` command on the datastore at `/organization/{store name}/`). I am not responsible for any damages caused by using this system. You use it at your own risk. Wisdom would suggest that you check the contents of the datastore before clearing it.

## Footnotes

<a id="footnote1">1. </a>You can find more details about what a datastore store name is and how the datastore works [here](https://pb-constructs.hightower.space/playbooks/introductions/datastore).
