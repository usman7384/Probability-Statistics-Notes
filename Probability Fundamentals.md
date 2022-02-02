
<body>
    <div id="doc" class="markdown-body container-fluid comment-enabled" data-hard-breaks="true"><h1 id="Probability-Fundamentals" data-id="Probability-Fundamentals"><a class="anchor hidden-xs" href="#Probability-Fundamentals" title="Probability-Fundamentals"><span class="octicon octicon-link"></span></a><span>Probability Fundamentals</span></h1><h2 id="Table-of-Contents" data-id="Table-of-Contents"><a class="anchor hidden-xs" href="#Table-of-Contents" title="Table-of-Contents"><span class="octicon octicon-link"></span></a><span>Table of Contents</span></h2><p><span class="toc"><ul>
<li><a href="#Probability-Fundamentals" title="Probability Fundamentals">Probability Fundamentals</a><ul>
<li><a href="#Table-of-Contents" title="Table of Contents">Table of Contents</a></li>
<li><a href="#Introduction" title="Introduction">Introduction</a></li>
<li><a href="#Starting-With-Probability" title="Starting With Probability">Starting With Probability</a><ul>
<li><a href="#Using-Outcomes" title="Using Outcomes">Using Outcomes</a></li>
<li><a href="#Outcome-Distributions" title="Outcome Distributions">Outcome Distributions</a></li>
<li><a href="#Complements" title="Complements">Complements</a></li>
<li><a href="#Expected-Value" title="Expected Value">Expected Value</a></li>
<li><a href="#Games-amp-Gambling" title="Games &amp; Gambling">Games &amp; Gambling</a></li>
</ul>
</li>
<li><a href="#Roll-the-Dice" title="Roll the Dice">Roll the Dice</a><ul>
<li><a href="#The-Rules-of-Sum-and-Product" title="The Rules of Sum and Product">The Rules of Sum and Product</a></li>
<li><a href="#Common-Intuitive-Fallacies" title="Common Intuitive Fallacies">Common Intuitive Fallacies</a></li>
<li><a href="#Complementary-Probabilities" title="Complementary Probabilities">Complementary Probabilities</a></li>
<li><a href="#Using-Symmetry" title="Using Symmetry">Using Symmetry</a></li>
<li><a href="#Endgame-Strategy" title="Endgame Strategy">Endgame Strategy</a></li>
</ul>
</li>
<li><a href="#Fairness-and-Expected-Value" title="Fairness and Expected Value">Fairness and Expected Value</a><ul>
<li><a href="#Introduction-to-Fairness" title="Introduction to Fairness">Introduction to Fairness</a></li>
<li><a href="#Barbotte" title="Barbotte">Barbotte</a></li>
<li><a href="#Roulette" title="Roulette">Roulette</a></li>
<li><a href="#Piglet" title="Piglet">Piglet</a></li>
<li><a href="#Linearity-of-Expectation" title="Linearity of Expectation">Linearity of Expectation</a></li>
<li><a href="#Bunco" title="Bunco">Bunco</a></li>
<li><a href="#Symmetry" title="Symmetry">Symmetry</a></li>
<li><a href="#Stein’s-Game" title="Stein’s Game">Stein’s Game</a></li>
<li><a href="#Information-Asymmetry" title="Information Asymmetry">Information Asymmetry</a></li>
</ul>
</li>
<li><a href="#Appendix-and-FAQ" title="Appendix and FAQ">Appendix and FAQ</a></li>
<li><a href="#References" title="References">References</a></li>
</ul>
</li>
</ul>
</span></p><h2 id="Introduction" data-id="Introduction"><a class="anchor hidden-xs" href="#Introduction" title="Introduction"><span class="octicon octicon-link"></span></a><span>Introduction</span></h2><p><strong><span>Probability</span></strong><span> is the likelihood of something happening. For example, A is likely to occur, B is definitely happening, there is a 40% chance of C, etc.</span></p><p><span>You’ll need to be able to work through paradoxes to make the best possible decisions and predictions when things are left up to random chance.</span></p><ul>
<li><span>Simpson’s Paradox</span><br>
<a href="https://www.britannica.com/topic/Simpsons-paradox" target="_blank" rel="noopener"><span>https://www.britannica.com/topic/Simpsons-paradox</span></a></li>
</ul><p><span>Probability lets us reason not only about the most likely future events but also about possible causes of past events.</span></p><h2 id="Starting-With-Probability" data-id="Starting-With-Probability"><a class="anchor hidden-xs" href="#Starting-With-Probability" title="Starting-With-Probability"><span class="octicon octicon-link"></span></a><span>Starting With Probability</span></h2><h3 id="Using-Outcomes" data-id="Using-Outcomes"><a class="anchor hidden-xs" href="#Using-Outcomes" title="Using-Outcomes"><span class="octicon octicon-link"></span></a><span>Using Outcomes</span></h3><p><img src="https://i.imgur.com/7bkzI4K.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/ICm2QzS.png" alt="" loading="lazy"><br>
<strong><span>Explanation</span></strong><br>
<span>Given the answer choices, it is much more likely that Katie, despite her past history, is only one of these rather than both of these. There is some probability that Katie does not help with the school’s music club. In addition, the event that Katie is both a teacher and helps with the music club is a subset of the event that Katie is a teacher. (A subset is a set contained within another set.) Thus, it cannot be more likely than the event that Katie is a teacher.</span></p><p><span>While we can’t predict most events with absolute certainty, we can try to estimate how likely they are to happen using probability.e.g. Usually, if I do not eat breakfast, I get a headache mid-morning. This morning I did not eat breakfast, so I will probably get a headache.This  statement somehow seems to be reasonable</span></p><p><img src="https://i.imgur.com/QenQ4xQ.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/1jqusRU.png" alt="" loading="lazy"><br>
<span>The sum of all of the probabilities for the different colors in each bag must sum to exactly 100%. It can’t be more than that.</span></p><p><span>Before diving any further into probability, let’s review some fundamental properties of probability:</span></p><ul>
<li><span>Probability is a number between 00 and 11, usually indicated with a capital P. For example, P(heads) indicates the probability of getting heads.</span></li>
<li><span>Probability can be expressed as a fraction, decimal, or percent.</span></li>
<li><span>The set of all possible outcomes is called the sample space. The sum of the probabilities of all outcomes in a sample space is exactly 1,1, or 100%.100%. For example, the probability of a coin landing on heads plus the probability of a coin landing on tails must equal exactly 11 because a coin cannot land on both heads and tails.</span></li>
<li><span>The most straightforward probability calculation is by outcomes. When there are some number of equally likely outcomes, the probability of a “successful” outcome can be calculated as --&gt; no. of successful Outcomes/no. of total Outcomes</span></li>
</ul><h3 id="Outcome-Distributions" data-id="Outcome-Distributions"><a class="anchor hidden-xs" href="#Outcome-Distributions" title="Outcome-Distributions"><span class="octicon octicon-link"></span></a><span>Outcome Distributions</span></h3><p><span>For some probability problems, it might be difficult to count all possible outcomes. For this reason, we represent the outcomes with lists and tables that make counting easier.</span><br>
<span>When faced with a tricky probability question, creating an outcome distribution chart can help show all of the possible outcomes.</span><br>
<em><span>Look at the example below:</span></em><br>
<img src="https://i.imgur.com/Q9aHzGm.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/LGOK2PH.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/90FDPbP.png" alt="" loading="lazy"></p><p><em><span>A handy solving technique in probability is to note when there is some sort of symmetry which causes two or more probabilities to be equal.</span></em></p><h3 id="Complements" data-id="Complements"><a class="anchor hidden-xs" href="#Complements" title="Complements"><span class="octicon octicon-link"></span></a><span>Complements</span></h3><p><span>Sometimes, it’s easier to count what did not happen than what did.</span><br>
<span>We explore how complements help us simplify and solve probability problems. Together, an event and its complement create all possible outcomes. The probability that something doesn’t happen is 11 minus the probability that it does happen.</span></p><p><span>We use complements to solve problems in probability. Because the probability that something happens and that it doesn’t happen add up to one, we can compute the one that’s easier to find.</span></p><h3 id="Expected-Value" data-id="Expected-Value"><a class="anchor hidden-xs" href="#Expected-Value" title="Expected-Value"><span class="octicon octicon-link"></span></a><span>Expected Value</span></h3><p><span>When making difficult decisions, we often consider best-possible and worst-possible outcomes. Is there a better way to make choices?</span><br>
<span>Now we’ll see how long-run averages can help us reason through making decisions when outcomes are uncertain.</span><br>
<span>The </span><strong><span>expected value</span></strong><span> (EV) is an anticipated value for an investment at some point in the future. In statistics and probability analysis, the expected value is calculated by multiplying each of the possible outcomes by the likelihood each outcome will occur and then summing all of those values.</span><br>
<em><span>Look at the example below:</span></em><br>
<img src="https://i.imgur.com/8AT96y8.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/MXbR4gi.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/oa1etnN.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/0h1rLVg.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/rtaxchO.png" alt="" loading="lazy"><br>
<em><span>We were trying to determine not only if we should expect to gain or lose money in the long run, but how much. This number is called expected value and tells us what to expect, on average, in the long run.</span></em></p><p><span>While we often can’t predict the consequences of our decisions, expected values let us see which choice would give us a better outcome in the long run.</span></p><h3 id="Games-amp-Gambling" data-id="Games-amp-Gambling"><a class="anchor hidden-xs" href="#Games-amp-Gambling" title="Games-amp-Gambling"><span class="octicon octicon-link"></span></a><span>Games &amp; Gambling</span></h3><p><span>Many gambling games are based on probability and expected values. We can apply the ideas we’ve been using to analyze outcomes for lotteries, coin tosses, and other games of pure chance.</span></p><h2 id="Roll-the-Dice" data-id="Roll-the-Dice"><a class="anchor hidden-xs" href="#Roll-the-Dice" title="Roll-the-Dice"><span class="octicon octicon-link"></span></a><span>Roll the Dice</span></h2><h3 id="The-Rules-of-Sum-and-Product" data-id="The-Rules-of-Sum-and-Product"><a class="anchor hidden-xs" href="#The-Rules-of-Sum-and-Product" title="The-Rules-of-Sum-and-Product"><span class="octicon octicon-link"></span></a><span>The Rules of Sum and Product</span></h3><ul>
<li><strong><span>The Rule of Product</span></strong><span>: When calculating the probability that multiple independent events will all occur, the probabilities are multiplied.</span><br>
<em><strong><span>Example:</span></strong></em><br>
<span>What is the chance of rolling a sum of 99 followed by a sum of 1010 on a pair of standard dice?</span><br>
<span>The probability of a sum of 9 is 4/36. The probability of a sum of 3/36.The overall probability of a 9 followed by a 10 is (4/36)*(3/36)</span><br>
<span>Because two die rolls do not affect each other (they are independent), multiplication is allowed.</span></li>
</ul><p><span>Two events are </span><em><strong><span>independent</span></strong></em><span> if the probability of one of them occurring does not affect the probability of the other occurring.</span></p><ul>
<li><strong><span>The Rule of Sum</span></strong><span>: the probability the event as a whole will occur is a sum of the probabilities of each individual part, as long as the parts cannot occur at the same time.</span></li>
</ul><p><span>A good rule of thumb (given independence) is the Rule of Product applies when an event </span><strong><span>and</span></strong><span> another event occur, while the Rule of Sum applies when an event </span><strong><span>or</span></strong><span> another event occurs.</span></p><h3 id="Common-Intuitive-Fallacies" data-id="Common-Intuitive-Fallacies"><a class="anchor hidden-xs" href="#Common-Intuitive-Fallacies" title="Common-Intuitive-Fallacies"><span class="octicon octicon-link"></span></a><span>Common Intuitive Fallacies</span></h3><p><span>The goal is to compare two events in each problem and identify the event that’s more likely.</span><br>
<span>Avoid the pitfalls of probability in situations where mistakes are common.</span></p><h3 id="Complementary-Probabilities" data-id="Complementary-Probabilities"><a class="anchor hidden-xs" href="#Complementary-Probabilities" title="Complementary-Probabilities"><span class="octicon octicon-link"></span></a><span>Complementary Probabilities</span></h3><p><span>In games with no possible draws, the probability of winning and the probability of losing add up to one. So, it’s enough to find just the simpler of the two!</span></p><p><span>The </span><strong><span>Rule of 1</span></strong><span> states that if the Rule of Sum is applied and every individual part of an event is accounted for, the probabilities ought to add up to 1, or 100%.</span></p><p><span>The </span><strong><span>complementary probability</span></strong><span> of an event is the probability that something </span><strong><span>doesn’t</span></strong><span> occur. Assuming there are only two choices (occurrence or non-occurrence) by the Rule of 1 the probability of an event not happening is 1 minus the probability of it happening. (Note: 1 also means 100% .)</span></p><p><strong><span>Example</span></strong><span>: If you know a certain strategy has a 10% chance of winning and there are no ties, it has a 100% - 10% = 90% chance of losing.</span></p><p><span>Finding the complementary probability — the probability of the opposite event — is easier than computing the relevant probability directly. Thanks to the rules of probability it’s enough to find one of them!</span></p><h3 id="Using-Symmetry" data-id="Using-Symmetry"><a class="anchor hidden-xs" href="#Using-Symmetry" title="Using-Symmetry"><span class="octicon octicon-link"></span></a><span>Using Symmetry</span></h3><p><span>Sometimes symmetry causes two or more probabilities to be equal, which reduces the number of overall probabilities you need to calculate.</span></p><p><img src="https://i.imgur.com/RIV2Y4h.png" alt="" loading="lazy"></p><p><span>In a number of dice games we found symmetry that made some probabilities equal. This useful shortcut allowed us to quickly solve these probability problems.</span></p><h3 id="Endgame-Strategy" data-id="Endgame-Strategy"><a class="anchor hidden-xs" href="#Endgame-Strategy" title="Endgame-Strategy"><span class="octicon octicon-link"></span></a><span>Endgame Strategy</span></h3><p><img src="https://i.imgur.com/R75D01h.png" alt="" loading="lazy"></p><p><span>In the game of Shut the Box, one needs to think ahead to find the optimal strategy.</span></p><p><img src="https://i.imgur.com/e1mcI2c.png" alt="" loading="lazy"></p><p><span>We saw that playing Shut the Box optimally comes down to comparing the probabilities of rolling different sums on a pair of dice.</span></p><h2 id="Fairness-and-Expected-Value" data-id="Fairness-and-Expected-Value"><a class="anchor hidden-xs" href="#Fairness-and-Expected-Value" title="Fairness-and-Expected-Value"><span class="octicon octicon-link"></span></a><span>Fairness and Expected Value</span></h2><h3 id="Introduction-to-Fairness" data-id="Introduction-to-Fairness"><a class="anchor hidden-xs" href="#Introduction-to-Fairness" title="Introduction-to-Fairness"><span class="octicon octicon-link"></span></a><span>Introduction to Fairness</span></h3><p><span>In a fair game, all players involved have an equal chance of winning, or if it’s a solo game, the player has an equal chance of winning and losing.</span></p><p><img src="https://i.imgur.com/08Y1DEr.png" alt="" loading="lazy"><br>
<span>If we determine a game is not entirely fair, we can try and determine what our chances are of winning. This can help us decide whether we want to play or not.</span></p><h3 id="Barbotte" data-id="Barbotte"><a class="anchor hidden-xs" href="#Barbotte" title="Barbotte"><span class="octicon octicon-link"></span></a><span>Barbotte</span></h3><p><span>In the game of Barbotte, each of the two players is assigned four winning combinations of two dice.</span></p><p><span>You are playing Barbotte with a friend using a pair of standard, six-sided dice. You take turns rolling both dice. According to the rules, you or your opponent win the round by rolling one of these four combinations: (3,3), (5,5), (6,6), or (6,5).</span></p><p><span>You lose the round if you or your opponent roll these combinations: (1,1), (2,2), (4,4), or (2,1). All other pairs result in neither a win nor a loss and the game continues.</span><br>
<span>You lose the round if you or your opponent roll these combinations: (1,1), (2,2), (4,4), or (2,1). All other pairs result in neither a win nor a loss and the game continues.</span></p><p><span>The game is fair two-fold: not only do you have an equal chance to win or lose against your opponent, but there are equal chances of rolling a winning or losing combo.</span></p><h3 id="Roulette" data-id="Roulette"><a class="anchor hidden-xs" href="#Roulette" title="Roulette"><span class="octicon octicon-link"></span></a><span>Roulette</span></h3><p><span>Roulette is a game of chance with many different kinds of bets.</span><br>
<img src="https://i.imgur.com/W0J4cZo.png" alt="" loading="lazy"><br>
<span>The “RED” bet wins on numbers colored red and “BLACK” bet wins on numbers colored black. They return 1:1 odds—that is, if a player wins, they win as much as they bet, doubling their money pile of that bet.</span></p><p><span>Is betting on red a fair bet? In other words, in the long run would you expect to break even betting on red only?</span><br>
<img src="https://i.imgur.com/uqWBjgQ.png" alt="" loading="lazy"></p><p><img src="https://i.imgur.com/Zn0RkFe.png" alt="" loading="lazy"></p><p><img src="https://i.imgur.com/PvXGMcI.png" alt="" loading="lazy"></p><p><span>We found that on average, roulette players are expected to lose money. This makes roulette an unfair game — the house is expected to win in the long run.</span></p><h3 id="Piglet" data-id="Piglet"><a class="anchor hidden-xs" href="#Piglet" title="Piglet"><span class="octicon octicon-link"></span></a><span>Piglet</span></h3><p><span>In the game of piglet, the player rolls a six-sided die and can either win or lose money depending on what they roll.</span></p><p><img src="https://i.imgur.com/VKkAiPH.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/guQGZNn.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/HcUhvfC.png" alt="" loading="lazy"></p><p><span>The key to winning the game of piglet is deciding when to quit and when to keep rolling the die. We established optimal strategies for different variations of the game using expected values.</span></p><h3 id="Linearity-of-Expectation" data-id="Linearity-of-Expectation"><a class="anchor hidden-xs" href="#Linearity-of-Expectation" title="Linearity-of-Expectation"><span class="octicon octicon-link"></span></a><span>Linearity of Expectation</span></h3><p><span>Linearity of expectation lets us compute the expected value of the sum of several outcomes, like the sum of dice rolls.</span></p><p><span>This concept is a general result called linearity of expectation. It means that if you are adding up two unknown quantities (for example the values of two dice), the expected value of their sum equals the sum of their expected values.</span></p><p><span>Thanks to the linearity of expectation, we can compute the expectation of a sum by adding individual expectations. This concept let us find the best strategy in a more complicated variation of the game of piglet.</span></p><h3 id="Bunco" data-id="Bunco"><a class="anchor hidden-xs" href="#Bunco" title="Bunco"><span class="octicon octicon-link"></span></a><span>Bunco</span></h3><p><span>Given a choice between different variations of the same game, one should pick the one with the highest expected value.</span><br>
<img src="https://i.imgur.com/mBCiKnZ.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/z11izA4.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/h78LNa3.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/WzUIBUa.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/jXeboBt.png" alt="" loading="lazy"></p><h3 id="Symmetry" data-id="Symmetry"><a class="anchor hidden-xs" href="#Symmetry" title="Symmetry"><span class="octicon octicon-link"></span></a><span>Symmetry</span></h3><p><span>When two or more outcomes are equally likely, you can take advantage of this to compute the expected value.</span></p><p><span>One of the most powerful arguments in probability and combinatorics is that of symmetry. If we can match up equally likely possibilities from two different cases, then we can say that these two cases have the same probability of happening.</span></p><p><span>This also works with expected value. For instance, because heads and tails are symmetric, if we flip many coins, we expect half of them to land on heads.</span></p><p><img src="https://i.imgur.com/bNhGmme.png" alt="" loading="lazy"></p><p><img src="https://i.imgur.com/2HvVv0g.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/28fAWbg.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/4HyjNdN.png" alt="" loading="lazy"></p><h3 id="Stein’s-Game" data-id="Stein’s-Game"><a class="anchor hidden-xs" href="#Stein’s-Game" title="Stein’s-Game"><span class="octicon octicon-link"></span></a><span>Stein’s Game</span></h3><p><span>Stein’s game can be played with different numbers of cards, and this choice impacts the probability of winning and the expected returns.</span></p><p><span>To play Stein’s game with NN cards, a dealer takes NN cards numbered 1, 2, \ldots, N1,2,…,N and shuffles them. Then, the player flips them over one by one, and they will be paid \dollar 1$1 every time a new highest card shows up. (The first card always counts as a highest card, since you haven’t seen any cards yet.)</span></p><p><img src="https://i.imgur.com/0HWC9vA.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/8iM6tX0.png" alt="" loading="lazy"></p><p><img src="https://i.imgur.com/PSxTGs4.png" alt="" loading="lazy"></p><h3 id="Information-Asymmetry" data-id="Information-Asymmetry"><a class="anchor hidden-xs" href="#Information-Asymmetry" title="Information-Asymmetry"><span class="octicon octicon-link"></span></a><span>Information Asymmetry</span></h3><p><span>The expected value of a game can be different depending on how much a player knows, and it can even change for the same person as they get more information.</span></p><p><span>In games, different players often have different information available to them. For example, in a game of poker, each player knows their own cards, but they do not know the other players’ cards.</span></p><p><span>This has a significant implication: the expected value of something can be different depending on how much you know, and it can even change for the same player as they get more information.</span></p><p><img src="https://i.imgur.com/Hsawqtq.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/ujPPJwB.png" alt="" loading="lazy"></p><h2 id="Appendix-and-FAQ" data-id="Appendix-and-FAQ"><a class="anchor hidden-xs" href="#Appendix-and-FAQ" title="Appendix-and-FAQ"><span class="octicon octicon-link"></span></a><span>Appendix and FAQ</span></h2><div class="alert alert-info">
<p><strong><span>Find this document incomplete?</span></strong><span> Leave a comment!</span></p>
</div><h2 id="References" data-id="References"><a class="anchor hidden-xs" href="#References" title="References"><span class="octicon octicon-link"></span></a><span>References</span></h2><p><a href="https://brilliant.org/courses/probability-fundamentals/" target="_blank" rel="noopener"><span>https://brilliant.org/courses/probability-fundamentals/</span></a></p></div>
    <div class="ui-toc dropup unselectable hidden-print" style="display:none;">
        <div class="pull-right dropdown">
            <a id="tocLabel" class="ui-toc-label btn btn-default" data-toggle="dropdown" href="#" role="button" aria-haspopup="true" aria-expanded="false" title="Table of content">
                <i class="fa fa-bars"></i>
            </a>
            <ul id="ui-toc" class="ui-toc-dropdown dropdown-menu" aria-labelledby="tocLabel">
                <div class="toc"><ul class="nav">
<li><a href="#Probability-Fundamentals" title="Probability Fundamentals">Probability Fundamentals</a><ul class="nav">
<li><a href="#Table-of-Contents" title="Table of Contents">Table of Contents</a></li>
<li><a href="#Introduction" title="Introduction">Introduction</a></li>
<li><a href="#Starting-With-Probability" title="Starting With Probability">Starting With Probability</a><ul class="nav">
<li><a href="#Using-Outcomes" title="Using Outcomes">Using Outcomes</a></li>
<li><a href="#Outcome-Distributions" title="Outcome Distributions">Outcome Distributions</a></li>
<li><a href="#Complements" title="Complements">Complements</a></li>
<li><a href="#Expected-Value" title="Expected Value">Expected Value</a></li>
<li><a href="#Games-amp-Gambling" title="Games &amp; Gambling">Games &amp; Gambling</a></li>
</ul>
</li>
<li><a href="#Roll-the-Dice" title="Roll the Dice">Roll the Dice</a><ul class="nav">
<li><a href="#The-Rules-of-Sum-and-Product" title="The Rules of Sum and Product">The Rules of Sum and Product</a></li>
<li><a href="#Common-Intuitive-Fallacies" title="Common Intuitive Fallacies">Common Intuitive Fallacies</a></li>
<li><a href="#Complementary-Probabilities" title="Complementary Probabilities">Complementary Probabilities</a></li>
<li><a href="#Using-Symmetry" title="Using Symmetry">Using Symmetry</a></li>
<li><a href="#Endgame-Strategy" title="Endgame Strategy">Endgame Strategy</a></li>
</ul>
</li>
<li><a href="#Fairness-and-Expected-Value" title="Fairness and Expected Value">Fairness and Expected Value</a><ul class="nav">
<li><a href="#Introduction-to-Fairness" title="Introduction to Fairness">Introduction to Fairness</a></li>
<li><a href="#Barbotte" title="Barbotte">Barbotte</a></li>
<li><a href="#Roulette" title="Roulette">Roulette</a></li>
<li><a href="#Piglet" title="Piglet">Piglet</a></li>
<li><a href="#Linearity-of-Expectation" title="Linearity of Expectation">Linearity of Expectation</a></li>
<li><a href="#Bunco" title="Bunco">Bunco</a></li>
<li><a href="#Symmetry" title="Symmetry">Symmetry</a></li>
<li><a href="#Stein’s-Game" title="Stein’s Game">Stein’s Game</a></li>
<li><a href="#Information-Asymmetry" title="Information Asymmetry">Information Asymmetry</a></li>
</ul>
</li>
<li><a href="#Appendix-and-FAQ" title="Appendix and FAQ">Appendix and FAQ</a></li>
<li><a href="#References" title="References">References</a></li>
</ul>
</li>
</ul>
</div><div class="toc-menu"><a class="expand-toggle" href="#">Expand all</a><a class="back-to-top" href="#">Back to top</a><a class="go-to-bottom" href="#">Go to bottom</a></div>
            </ul>
        </div>
    </div>
    <div id="ui-toc-affix" class="ui-affix-toc ui-toc-dropdown unselectable hidden-print" data-spy="affix" style="top:17px;display:none;" null null>
        <div class="toc"><ul class="nav">
<li><a href="#Probability-Fundamentals" title="Probability Fundamentals">Probability Fundamentals</a><ul class="nav">
<li><a href="#Table-of-Contents" title="Table of Contents">Table of Contents</a></li>
<li><a href="#Introduction" title="Introduction">Introduction</a></li>
<li><a href="#Starting-With-Probability" title="Starting With Probability">Starting With Probability</a><ul class="nav">
<li><a href="#Using-Outcomes" title="Using Outcomes">Using Outcomes</a></li>
<li><a href="#Outcome-Distributions" title="Outcome Distributions">Outcome Distributions</a></li>
<li><a href="#Complements" title="Complements">Complements</a></li>
<li><a href="#Expected-Value" title="Expected Value">Expected Value</a></li>
<li><a href="#Games-amp-Gambling" title="Games &amp; Gambling">Games &amp; Gambling</a></li>
</ul>
</li>
<li><a href="#Roll-the-Dice" title="Roll the Dice">Roll the Dice</a><ul class="nav">
<li><a href="#The-Rules-of-Sum-and-Product" title="The Rules of Sum and Product">The Rules of Sum and Product</a></li>
<li><a href="#Common-Intuitive-Fallacies" title="Common Intuitive Fallacies">Common Intuitive Fallacies</a></li>
<li><a href="#Complementary-Probabilities" title="Complementary Probabilities">Complementary Probabilities</a></li>
<li><a href="#Using-Symmetry" title="Using Symmetry">Using Symmetry</a></li>
<li><a href="#Endgame-Strategy" title="Endgame Strategy">Endgame Strategy</a></li>
</ul>
</li>
<li><a href="#Fairness-and-Expected-Value" title="Fairness and Expected Value">Fairness and Expected Value</a><ul class="nav">
<li><a href="#Introduction-to-Fairness" title="Introduction to Fairness">Introduction to Fairness</a></li>
<li><a href="#Barbotte" title="Barbotte">Barbotte</a></li>
<li><a href="#Roulette" title="Roulette">Roulette</a></li>
<li><a href="#Piglet" title="Piglet">Piglet</a></li>
<li><a href="#Linearity-of-Expectation" title="Linearity of Expectation">Linearity of Expectation</a></li>
<li><a href="#Bunco" title="Bunco">Bunco</a></li>
<li><a href="#Symmetry" title="Symmetry">Symmetry</a></li>
<li><a href="#Stein’s-Game" title="Stein’s Game">Stein’s Game</a></li>
<li><a href="#Information-Asymmetry" title="Information Asymmetry">Information Asymmetry</a></li>
</ul>
</li>
<li><a href="#Appendix-and-FAQ" title="Appendix and FAQ">Appendix and FAQ</a></li>
<li><a href="#References" title="References">References</a></li>
</ul>
</li>
</ul>
</div><div class="toc-menu"><a class="expand-toggle" href="#">Expand all</a><a class="back-to-top" href="#">Back to top</a><a class="go-to-bottom" href="#">Go to bottom</a></div>
    </div>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.1/jquery.min.js" integrity="sha256-hVVnYaiADRTO2PzUGmuLJr8BLUSjGIZsDYGmIJLv2b8=" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha256-U5ZEeKfGNOja007MMD3YBI0A3OSZOQbeG6z2f2Y0hu8=" crossorigin="anonymous" defer></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gist-embed/2.6.0/gist-embed.min.js" integrity="sha256-KyF2D6xPIJUW5sUDSs93vWyZm+1RzIpKCexxElmxl8g=" crossorigin="anonymous" defer></script>
    <script>
        var markdown = $(".markdown-body");
        //smooth all hash trigger scrolling
        function smoothHashScroll() {
            var hashElements = $("a[href^='#']").toArray();
            for (var i = 0; i < hashElements.length; i++) {
                var element = hashElements[i];
                var $element = $(element);
                var hash = element.hash;
                if (hash) {
                    $element.on('click', function (e) {
                        // store hash
                        var hash = this.hash;
                        if ($(hash).length <= 0) return;
                        // prevent default anchor click behavior
                        e.preventDefault();
                        // animate
                        $('body, html').stop(true, true).animate({
                            scrollTop: $(hash).offset().top
                        }, 100, "linear", function () {
                            // when done, add hash to url
                            // (default click behaviour)
                            window.location.hash = hash;
                        });
                    });
                }
            }
        }

        smoothHashScroll();
        var toc = $('.ui-toc');
        var tocAffix = $('.ui-affix-toc');
        var tocDropdown = $('.ui-toc-dropdown');
        //toc
        tocDropdown.click(function (e) {
            e.stopPropagation();
        });

        var enoughForAffixToc = true;

        function generateScrollspy() {
            $(document.body).scrollspy({
                target: ''
            });
            $(document.body).scrollspy('refresh');
            if (enoughForAffixToc) {
                toc.hide();
                tocAffix.show();
            } else {
                tocAffix.hide();
                toc.show();
            }
            $(document.body).scroll();
        }

        function windowResize() {
            //toc right
            var paddingRight = parseFloat(markdown.css('padding-right'));
            var right = ($(window).width() - (markdown.offset().left + markdown.outerWidth() - paddingRight));
            toc.css('right', right + 'px');
            //affix toc left
            var newbool;
            var rightMargin = (markdown.parent().outerWidth() - markdown.outerWidth()) / 2;
            //for ipad or wider device
            if (rightMargin >= 133) {
                newbool = true;
                var affixLeftMargin = (tocAffix.outerWidth() - tocAffix.width()) / 2;
                var left = markdown.offset().left + markdown.outerWidth() - affixLeftMargin;
                tocAffix.css('left', left + 'px');
            } else {
                newbool = false;
            }
            if (newbool != enoughForAffixToc) {
                enoughForAffixToc = newbool;
                generateScrollspy();
            }
        }
        $(window).resize(function () {
            windowResize();
        });
        $(document).ready(function () {
            windowResize();
            generateScrollspy();
        });

        //remove hash
        function removeHash() {
            window.location.hash = '';
        }

        var backtotop = $('.back-to-top');
        var gotobottom = $('.go-to-bottom');

        backtotop.click(function (e) {
            e.preventDefault();
            e.stopPropagation();
            if (scrollToTop)
                scrollToTop();
            removeHash();
        });
        gotobottom.click(function (e) {
            e.preventDefault();
            e.stopPropagation();
            if (scrollToBottom)
                scrollToBottom();
            removeHash();
        });

        var toggle = $('.expand-toggle');
        var tocExpand = false;

        checkExpandToggle();
        toggle.click(function (e) {
            e.preventDefault();
            e.stopPropagation();
            tocExpand = !tocExpand;
            checkExpandToggle();
        })

        function checkExpandToggle () {
            var toc = $('.ui-toc-dropdown .toc');
            var toggle = $('.expand-toggle');
            if (!tocExpand) {
                toc.removeClass('expand');
                toggle.text('Expand all');
            } else {
                toc.addClass('expand');
                toggle.text('Collapse all');
            }
        }

        function scrollToTop() {
            $('body, html').stop(true, true).animate({
                scrollTop: 0
            }, 100, "linear");
        }

        function scrollToBottom() {
            $('body, html').stop(true, true).animate({
                scrollTop: $(document.body)[0].scrollHeight
            }, 100, "linear");
        }
    </script>
</body>

</html>
