#### Title: CHIPS Code Improvement Proposal #1
#### Issue: [read here](https://github.com/ciphs/cryptocurrency/issues/4)
#### PR/Commit Ref: 
1. [COMMIT](https://github.com/ciphs/cryptocurrency/commit/5a16c0a8b416ff0205fbb5424e3884239d749440)
2. [CRC#6](https://github.com/ciphs/cryptocurrency/pull/6)
#### Status: Complete
#### Proposal 1: To withdraw Ether from Contract

function sendEtherToOwner() public onlyOwner {                       
      owner.transfer(this.balance);
  }

#### Proposal 2: Increase setRate to 

1000000e18

#### Proposal 3: Additional consensus function as propose on:

[CRC#6](https://github.com/ciphs/cryptocurrency/pull/6)
