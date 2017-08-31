# DASH

[White Paper](https://github.com/dashpay/dash/wiki/Whitepaper)

* Master nodes put up a 1000 DASH bond
* Provide services; recieve a dividend
* MasterNode paid via pool 
    * 45% of total block reward
* Cost of running a node has hard and soft limit
    * Hard
        * 5.3 mil DASH in circulation --> (<= 5,300 nodes)
    * Soft
         * price to be node
         * limited liquidity on exchanges (permits transactions?)
             * not held as an investment (less liquidity)
 * Formula:
     * Reward pool is a fixed percentage
     * Number of nodes flucuates
     * Rewards vary via total node count

~~~~
    PaymentsPerDay := (n/t)*r*b*a 
    ROI := ((n/t)*r*b*a*365) / 1000
    
    Where:
        n is num of nodes an operator controls
        t is the total num of nodes
        r is current block reward (currently 5 DASH)    * Master nodes put up a 1000 DASH bond
    * Provide services; recieve a dividend
    * MasterNode paid via pool 
        * 45% of total block reward
    * Cost of running a node has hard and soft limit
        * Hard
            * 5.3 mil DASH in circulation --> (<= 5,300 nodes)
        * Soft
            * price to be node
            * limited liquidity on exchanges (permits transactions?)
                * not held as an investment (less liquidity)
    * Formula:
        * Reward pool is a fixed percentage
        * Number of nodes flucuates
        * Rewards vary via total node count
        b is blocks in an avg day
        a is the average node payment (45% of avg block amount)
~~~~

* Masternodes perform "oracle" duties
    * Bond and reputation at stake to incentivize good behavior
    * Examples 
        * "PrivateSend"
        * "InstantSend"
        * decentralized oracle for 
            * financial markets
            * contracts
                * AAPL > $300; then pay pubkey A; else pay pubkey
    * Subset A checks services of subset B
        * ~ 1% of the network will be checked each block
            * entire network checked 6 times per day
        * 6 violations deactivates a node

* Token Distribution and Supply
    * Block reward split with MN
    * 7% reduction of supply rather than bitcoin's "halving"
    * Reward per block determined by reduction and difficulty rating
    * Difficulty rating determined by network hash rate
        * adjusted to maintain ~576 blocks/day
    
* Self Governing.. Self Funding
* Governing
    * Everyone has a voice
    * Everyone has ability to propose projects
        * Marketing
        * Development
    * Via tresury proposals
    * MasterNodes vote on proposals
        * MasterNodes vote and hence make all network decisions
        * (YES vote - NO vote) > (Num MN / 10)
* Funding
    * 10% of all block rewards funds DASH development
        * Only created at the end of the month
        * budget proposals are submitted during month
        * SuperBlocks are created for appoved proposals and paid out
    * 45% miner
    * 45% MN














































