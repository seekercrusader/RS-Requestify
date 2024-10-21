RS: Requestify is an addon to Refined Storage that currently adds one block, the Requester. The Requester is a rs network block where you can specify how many of 1 item you want to keep stocked in your system. For example, if you want to have a stack of chest always in your rs system the Requester will do that for you by automatically creating crafting jobs for you. 

In the config you can specify how big crafting batches can be.

general {
    # The maximum amount requested as a craft by the Requester. It will still achieve the desired amount but in smaller crafting batches. 
    # Min: 1
    # Max: 2147483647
    I:MAX_CRAFT_AMOUNT=1000
}
