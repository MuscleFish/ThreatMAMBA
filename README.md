# What is ThreatMAMBA

ThreatMAMBA is an end-to-end HGNN cyber threat attribution model, which can provide attackers' TTPs and identification

# What we have here

In this library, we will provide the datasets we used.

- CTI2TTPs: the dataset includes the Mitre ATT&CK V14 procedure examples and their belonging techniques and tactics
- CTI2Attacker: this dataset includes the original Cyber Threat Intelligence Reports and their belonging attackers
- cleaned_CTI2Attacker: remove non-CTI documents
- CTI2Attacker_TTP: extract all TTPs in cleaned_CTI2Attacker
- TTP_Group_Contribution: the importance of TTPs in identifying Attackers extracted by ThreatMAMBA
- CTI2Attacker_TTP_GroupState: the group behavior patterns extracted by ThreatMAMBA.
-- You can edit the `pie-node-ttp-state-graph.temp.html` and replace `ttp_state_data` with the values from `CTI2Attacker_TTP_GroupState`'s column `group_state_ttp`
-- Some CTIs with less than 2 TTPs don't have their `group_state_ttp`
