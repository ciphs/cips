Title: CHIPS Code Improvement Proposal #1
Issue: ttps://github.com/ciphs/cryptocurrency/issues/4
Status: In Progress
Proposal: To withdraw Ether from Contract

function sendEtherToOwner() public onlyOwner {                       
      owner.transfer(this.balance);
  }
