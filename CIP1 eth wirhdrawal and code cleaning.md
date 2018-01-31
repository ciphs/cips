#### Title: CHIPS Code Improvement Proposal #1
#### Issue: [read here](https://github.com/ciphs/cryptocurrency/issues/4)
#### Status: In Progress
#### Proposal 1: To withdraw Ether from Contract

function sendEtherToOwner() public onlyOwner {                       
      owner.transfer(this.balance);
  }

#### Proposal 2: Increase setRate to 

1000000e18
