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
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(threeOne)}>3.1 Scoring System</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(four)}>Section 4: Postseason</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourOne)}>4.1 Playoffs</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourTwo)}>4.2 Seeding and Tiebreakers</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(five)}>Section 5: New Rules or Managers </h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fiveOne)}>5.1 Rule Changes</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fiveOne)}>5.2 Replacing Managers</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(six)}>Section 6: Tanking Policy</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixOne)}>6.1 Definition</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixTwo)}>6.2 Penalty</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixThree)}>6.3 Replacement Incentive</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 7: League Finances</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sevenOne)}>7.1 League Dues</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixTwo)}>7.2 Payout</h4>
        
    
    
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
    <p>Each year's draft rounds will be linear (non-snaking).</p>
    <p>For teams ending the regular season 7-12 (non-playoff contenders) the prior season, the draft order will be determined by their Max Points For (the points a team would have scored each week if they started the optimal roster). The reverse of total Max Points For standing will be used for draft order. The manager with the least Max Points For will draft 1st, the player with the second least Max Points For will draft 2nd, and so on.</p>
    <p>For teams ending the regular season 1-6 (playoff contenders) the prior season, the draft order will be determined by reverse playoff finishing place. The prior season league champion will draft 12th, the runner up will draft 11th, and so on.</p>

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
    <h2 class="sectionHeading" bind:this={five}>Section 5 New Rules or Managers</h2>
    
    <h3 bind:this={fiveOne}>5.1 Rule Changes</h3>
    <p>No in-season rule changes will take place. This means rules are locked from the beginning of the regular season draft through the end-of-season championship game.</p>
    <p>Proposals for rule changes can be submitted at any time. A vote on rule change proposals will occur on the day of next season's draft. All proposals must be structured with an affirmative/negative response for participating voters.</p>
    <p>Rule proposals receiving an affirmative vote of 2/3 of participants will pass and be in effect for the following season. An abstain of vote on any single proposal will reduce the number of voting participants the 2/3 threshold will be based on.</p>

    <h3 bind:this={fiveOne}>5.2 Replacing Managers</h3>
    <p>This league looks to be a fun outlet for like-minded managers who engage in year-long fantasy team management. Participation through the league chat and in-person draft events is encouraged, but failing to do so is not grounds for manager removal.</p>
    <p>In the event a manager elects to retire from the league, the commissioners will work to find a suitable candidate with some connection to existing managers (no strangers) who is willing to take on a dynasty commitment and be active throughout the year.</p>
    <p>Recommendations for future manager prospects are highly encouraged. We want to fill league spots with prospects who have heard about our league and wanted to join for a while.</p>
    <p>Incoming managers will inherit the roster and draft picks left by the retiring manager. A one-time league discount (affecting the end-of-season payout) may be afforded to an incoming manager at the commissioner's discretion.</p>


    <h2 class="sectionHeading" bind:this={six}>Section 6 Tanking Policy</h2>
    
    <h3 bind:this={sixOne}>6.1 Definition</h3>
    <p>Tanking is the practice of intentionally losing games or fielding a non-competitive team to take advantage of league rules and attempt to inherit a better draft position in the following season draft.</p>
    <p>A league vote was conducted prior to the 2024 season determining that any of the actions (or inactions) below are an indication of tanking, and subject to a league penalty:</p>
        <ul>
        <li>Submission of a weekly starting roster with a player on Injured Reserve (IR) or Not Available (NA)</li>
        <li>Submission of a weekly starting roster spot that is unoccupied (completely open)</li>
        <li>Submission of a weekly starting roster with a player (or defense) on a Bye</li>
        </ul>
    <p>If a manager has no roster depth at the position in which a tanking indicator appears, then no taking offense will apply, as the rule is intended to penalize team management mismanagement and not force managers to drop players to free agency.</p>
    <p>Consider the scenarios below as reference:</p>
    <p>A manager has a team defense that is currently on a bye. Adding an alternative defense would require either dropping their rostered defense or another rostered skill player. <em>This manager would be permitted to leave the defense position open or start the defense on a bye this week as there is no depth behind their current rostered defense on a bye.</em></p>
    <p>A manager has an elite WR dealing with a reported injury all week and determined to be a game-time decision. The manager did not utilize the Sleeper autosub feature and the WR was determined to be OUT minutes before kickoff. The OUT WR was submitted in the manager's starting roster. The manager had one additional WR on their bench that was not started. <em>This manager would be subject to a tanking offense.</em></p>
    
    <h3 bind:this={sixTwo}>6.2 Penalty</h3>
    <p>A tanking offense will result in the automatic end-of-first-round pick (1.12) in the next draft to immediately follow the offense. Later rounds (2-4) will be unaffected. In the event multiple managers are subject to tanking offenses, the penalized drafting order will be determined by the date of the infraction.</p>
    
    <h3 bind:this={sixThree}>6.3 Replacement Incentive</h3>
    <p>In the event that a manager chooses to quit the league or is removed by a comissioner, an incoming manager is offered a 50% reductioon on their first year buy-in.</p>

    <h2 class="sectionHeading" bind:this={seven}>Section 7 League Finances</h2>
    
    <h3 bind:this={sevenOne}>7.1 League Dues</h3>
    <p>League dues are set at $200 per manager. They are due in advance of the kick-off of the first game of the current NFL season.</p>
    <p>Any manager failing to pay their fee prior to the season kick-off will experience a ‘roster-lock’ which will prevent changes to their weekly line-up. Losses resulting from a ‘roster-lock’ will not be reversed.</p>

    <h3 bind:this={sevenTwo}>7.2 Payout</h3>
    <p>The league payout will reward first, second and third place playoff finishers. The payout will be comprised of all current season dues and all current season FAAB budget reloads.</p>
    <p>League payout is structured as follows:</p>
    <ul>
        <li>1st place: 70% of total season funds collected</li>
        <li>2nd place: 20%</li>
        <li>3rd place: 10%</li>
    </ul>

</div>
