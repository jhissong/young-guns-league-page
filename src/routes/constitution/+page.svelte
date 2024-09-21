<script>
    import { dues } from '$lib/utils/helper';
    let one, oneOne, oneOneOne, oneTwo, oneTwoOne, oneTwoTwo, oneTwoThree, oneTwoFour, oneTwoFive, oneThree;
    let two, twoOne, twoTwo, twoThree;
    let three, threeOne;
    let four, fourOne, fourTwo;
    let five, fiveOne;
    let six, sixOne, sixTwo, sixThree;
    let seven, sevenOne, sevenTwo, sevenThree;

    const goToSection = (section) => {
        const top = section.getBoundingClientRect().top + window.pageYOffset;
        window.scrollTo({left: 0, top, behavior: 'smooth'});
    }
</script>

<style>
    .constitution {
        position: relative;
        z-index: 1;
        width: 92%;
        max-width: 800px;
        margin: 8em auto 10em;
    }

    h1 {
        font-size: 2em;
        line-height: 1.2em;
        text-align: center;
        margin: 2em 0 1.5em;
    }

    h2 {
        font-size: 1.5em;
        line-height: 1.2em;
    }

    h3 {
        text-decoration: underline;
        font-size: 1.3em;
        line-height: 1.2em;
    }

    h4 {
        text-decoration: underline;
        margin-left: 2em;
        font-size: 1.2em;
        line-height: 1.2em;
    }

    h5 {
        margin-left: 6em;
        font-size: 0.8em;
        line-height: 1.1em;
    }

    .subBlock {
        margin-left: 2.4em;
    }

    .sectionHeading {
        margin: 4em 0 1.5em;
    }

    .subSectionHeading {
        margin: 1.5em 0 1.5em;
    }

    .underscore {
        text-decoration: underline;
    }

    .right {
        text-align: right;
    }

    .positionMaximums td {
        min-width: 3em;
    }

    .noUnderscore {
        text-decoration: none;
    }

    .clickable {
        cursor: pointer;
    }

    .clickable:hover {
        color: #00316b;
    }

    p {
        color: #777;
    }
</style>

<div class="constitution">
    <h1 class="noUnderscore">YOUNG GUNS DYNASTY CONSTITUTION</h1>
    
    <h2 class="noUnderscore">TABLE OF CONTENTS</h2>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(one)}>Section 1: Roster Construction</h3>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneOne)}>1.1 Positional Breakdown</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneTwo)}>1.2 Trading</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneThree)}>1.3 Waiver Wire</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(two)}>Section 2: Drafting</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(twoOne)}>2.1 Draft Order</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(twoTwo)}>2.2 Draft Mechanics</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(twoThree)}>2.3 Draft Clock Management and In-Draft Trades</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(three)}>Section 3: Scoring System</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(threeOne)}>3.1 Voting on Scoring System</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(four)}>Section 4: Postseason</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourOne)}>4.1 Playoffs</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourTwo)}>4.2 Seeding and Tiebreakers</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(five)}>Section 5: Tanking Policy</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fiveOne)}>5.1 League Tanking Policy</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(six)}>Section 6: Replacing Managers</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixOne)}>6.1 Removing Managers</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixTwo)}>6.2 Replacing Managers</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixThree)}>6.3 Replacement Incentive</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 7: League Finances</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sevenOne)}>7.1 League Dues</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixTwo)}>7.2 Payout</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixThree)}>7.3 Raising Dues</h4>
    
    
    <hr />
    
    <h2 class="sectionHeading" bind:this={one}>Section 1 Roster Construction</h2>
    
    <h3 class="subSectionHeading" bind:this={oneOne}>1.1 Positional Breakdown</h3>
    
    <p>28 Total Players</p>
    
    <p class="underscore">Starters</p>
    <ul>
        <li>QB</li>
        <li>QB</li>
        <li>RB</li>
        <li>RB</li>
        <li>WR</li>
        <li>WR</li>
        <li>WR</li>
        <li>TE</li>
        <li>FLEX (RB/WR/TE)</li>
        <li>D/ST</li>
        <li>K</li>
    </ul>
    
    <p>12 Bench </p>

    <p>1 IR Spots (To be eligible, a player must be designated as IR or Out in the Sleeper App. Players that miss time due to suspension, 
        COVID, holdout/opt-out, or otherwise not active are not eligible for the Injured Reserve. Doubtful health 
        designations are not eligible for IR.)</p>
    <p> No active position maximums exist. Managers may roster any number of players at any position. </p>
       
    <h3 class="subSectionHeading" bind:this={oneTwo}>1.2 Trading</h3>
    
    <p>Tradable assets include players, draft picks, and FAAB dollars.</p>
    <p>Trades will be processed after 24 hours or immediately with action from the commissioner.</p>
    <p>Trading of players and draft picks (up to 3 drafts away) is allowed, however, draft picks beyond the picks available for trade in the Sleeper App are not permitted.</p>
    <p>The trade deadline will be set for week 12 of the NFL season. All trades must be accepted within the Sleeper app by the conclusion of the final game of the week.</p>
    <p>FAAB dollars for the current season only may be traded. If FAAB dollars are not available in the Sleeper App, they are not available for trade. The maximum FAAB available for trade within a single transaction is $100.</p>
    <p>No veto process exists. If all parties agree to the terms of a trade, and the trade is processed in the Sleeper App, the trade cannot be reversed unless another rule within the league constitution has been compromised with the trade.</p>
         
       
    <h3 bind:this={oneThree}>1.3 Waiver Wire</h3>
    
    <p>FAAB bidding provides managers with a budget during the season for free agents and uses a blind bidding process to select people off free agency each week. As waivers are processed weekly, the highest bidder for each player wins the claim.</p>
    <p>Each team will receive $100 FAAB at the beginning of the season (immediately following the draft). Managers may re-load their FAAB budget with a league payment of $100. FAAB budgets can never exceed $100 FAAB dollars. Additional funds added to the FAAB budget will be added to the current season funds paid to the end-of-year winners.</p>
    <p>If two or more teams bid the same amount, the tiebreaker comes down to waiver wire priority, which acts as rolling waivers. The waiver wire priority can be found in your league's standings and can be adjusted by the commissioner if desired.</p>
    <p>During the regular season (following the draft), waivers will clear on Wednesdays at 2 AM CST. During the offseason (Beginning week 18 through the next draft), all waivers will be locked, and no players will be eligible to be picked up in free agency.</p>
    <p>A player dropped in the middle of the week will be held on waivers for two days. Managers may bid on the dropped player. That player's waiver holding will clear at 2 AM CST the day following a two-day hold. A player added from free agency must be owned by a manager for 24 hours before being released for the two-day waiver wire hold to exist.</p>
    <p>Players will be in free agency (available to be added immediately) until the NFL kicks off their teams' weekly matchup.</p>
    
    
    <h2 class="sectionHeading" bind:this={two}>Section 2 Drafting</h2>
    
    <h3 bind:this={twoOne}>2.1 Draft Order</h3>
    <p>Each year's draft order will be linear, in reverse order of the previous year’s regular season standings for teams finishing 7th-12th place and in reverse order of playoff finish for teams participating in the previous season’s playoff bracket.</p>
    
    <h3 bind:this={twoTwo}>2.2 Draft Mechanics</h3>
    <p>The draft will be conducted virtually through the Sleeper App and will consist of four rounds in total. The draft will begin at a predetermined date and time, which will be communicated each season by the conclusion of the NFL Draft in April. The draft start time will be communicated through league chat in the Sleeper App.</p>
    <p>All unowned players are eligible to be drafted. This includes rookies and veterans in free agency.</p>
    <p>Managers do not have to drop players from their existing roster before the draft (to make room for new additions), but following the draft, managers will be required to make cuts to match the total roster limit by the kick-off of the first game of the NFL regular season. Managers cannot set lineups within the Sleeper App when roster limits are exceeded.</p>
    <p>Managers will be allotted 5 minutes to execute a pick. When the time expires, picks will default to an automatic pick made by the Sleeper App or any prioritized picks set by the manager prior to the clock expiration (players in cue).</p>
  
    <h3 bind:this={twoThree}>2.3 Draft Clock Management and In-Draft Trades</h3>
    <p>The draft clock may be paused at any time at the discretion of the commissioner.</p>
    <p>If a trade is made during the draft that affects a pick currently on the clock, the commissioner will pause the draft clock. A manager inheriting the pick will inherit the time remaining on the existing clock, however, managers will be guaranteed a minimum of 30 seconds following an accepted trade within the Sleeper App. Additional time to negotiate the terms of the trade for a pick on the clock will not be afforded.</p>
   
    <h2 class="sectionHeading" bind:this={three}>Section 3 Scoring System</h2>

    <h3 bind:this={threeOne}>3.1 Scoring System</h3>
    <p>In addition to standard fantasy football scoring mechanics, the league employs bonuses based on total yards, points per reception, and penalties for special teams players.</p>
    <p>Details of the current league scoring system can be found within the Sleeper App.</p>
    
    <h2 class="sectionHeading" bind:this={four}>Section 4 Postseason</h2>
    
    <h3 bind:this={fourOne}>4.1 Playoffs</h3>
    <p>The regular season will end with the conclusion of games in week 14. The top 6 teams will enter the league playoff championship bracket.</p>
    <p>The first round of playoffs will commence in week 15.</p>
    <p>Each playoff matchup (including the championship game) will last only one week, and the winner will advance. No re-seeding will occur in the playoffs.</p>

    <h3 bind:this={fourTwo}>4.2 Seeding and Tiebreakers</h3>
    <p>Match-ups and byes will be dictated by the end of the regular season standings. The first-place and second-place regular season finishers will have a bye in week 1. The remaining postseason matchups will also be determined by regular season finish. The 6th-place finisher will play the 3rd-place finisher and the 5th-place finisher will play the 4th-place finisher.</p>
    <p>If two teams finish with the same regular season record the tiebreakers will go as followed:</p>

    <ol>
        <li>Points For</li>
        <li>Head 2 Head Record</li>
        <li>Division Record</li>
        <li>Total Points Against</li>
        <li>Coin Flip</li>
        <li>Duel to the death</li>
    </ol>
    <p>If a weekly playoff matchups end with a tie score, the winner is automatically the higher seed.</p> 
    <h2 class="sectionHeading" bind:this={five}>Section 5 Tanking Policy</h2>
    
    <h3 bind:this={fiveOne}>5.1 League Tanking Policy</h3>
    <p>No team may intentionally leave starting roster spots empty. Any evidence of intentionally leaving roster spots empty in order to improve your draft position may be subject to punishment, including but not limited to the forfeiture of draft selections.</p>

    <h2 class="sectionHeading" bind:this={six}>Section 6 Replacing Managers</h2>
    
    <h3 bind:this={sixOne}>6.1 Removing Managers</h3>
    <p>Short of continuously failing to set a valid lineup, or confirmed collusion, no manager can be removed against their will. Participation, through the league chat, trade offers, and the waiver wire, is strongly encouraged but generally grounds for removal.</p>
    
    <h3 bind:this={sixTwo}>6.2 Replacing Managers</h3>
    <p>When a manager needs to be replaced, the commisiooners will try to find a suitable candidate with some connection to at least a portion of the existing managers. Priority will be placed on managers who are eager to take on a dynasty commitment and will be very active within the league.</p>
    
    <h3 bind:this={sixThree}>6.3 Replacement Incentive</h3>
    <p>In the event that a manager chooses to quit the league or is removed by a comissioner, an incoming manager is offered a 50% reductioon on their first year buy-in.</p>

    <h2 class="sectionHeading" bind:this={seven}>Section 7 League Finances</h2>
    
    <h3 bind:this={sevenOne}>7.1 League Dues</h3>
    <p>League dues are set at {dues}$. Dues are collected through <a href="https://www.leaguesafe.com/league/3949641">LeagueSafe</a> and collection will be sent out no later than the first of August. All managers must be fully paid up before the start of regular season. In the event that a manager fails to pay before the deadline, a 10% penalty will be addd to their payment and will go towards the payouts at the end of the year.</p>
    
    <h3 bind:this={sevenTwo}>7.2 Payout</h3>
    <p>League payout is structured as follows:</p>
    <ul>
        <li>1st place: {dues * 8}$</li>
        <li>2nd place: {dues * 3}$</li>
        <li>3rd place: {dues}$</li>
    </ul>
    <p>In the event that a manager was fined due to late payment, their extra fee will be added to the winner's payout. Similarly, if new managers come into the league and the payout is smaller, the difference will come out of the winner's prize.</p>
    
    <h3 bind:this={sevenThree}>7.3 Raising Dues</h3>
    <p>A ⅔ majority vote is required in order to raise league dues. In the event that a manager is no longer financially comfortable with the buyin, finding a co-manager to split the cost is reccomended.</p>

</div>
