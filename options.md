* Some Thoughts on Options Trading

At the outset of Covid -- once the stock market had suffered its first large drop -- I began to trade options. Not as an investment strategy (and certainly not to finance consumption), but as way to teach myself how options work and to follow the dynamics of the market during one of the stranger episodes in its history. Evidently I wasn't the only retail investor to have this idea, and my lesson in options trading did not come cheap, but it did give rise to some interesting thoughts. I add the obvious disclaimer that I have never studied options in any formal setting, and so these observations may seem rudimentary to anyone with a modicum of academic or professional experience.

First, a motivating question: suppose you knew for a fact that company XYZ, currently trading at $90 per share, will rise to $100 in the next week. (Perhaps you have a strong prior that the new product will be a success, or you came across some material non-public information; the important thing is that the rest of the market does not know). What options position should you take to maximize your profits? 

The standard objects of interest in options trading are the so-called "greeks", mathematical objects that give the change in the price of an option corresponding to changes in some underlying features of the security. Formally, the give partial derivatives of option value with respect to other parameters. Three main three (``first order greeks'') are delta, vega, and theta, which tell how the value of an option change with (respectively) the price of the underlying, the volatility of the underlying, and the time until expiration. Clearly, very in-the-money options have a very high delta, since a $1 increase in the underlying stock will almost certainly translate into $1 additional option value. So one way to take a position would be to purchase a very in-the-money option of XYZ, say at a strike of $2. With a delta close to 1, each option would net ~$10 in profit in the next week. 

But investors don't care about absolute profits, they care about returns. The delta of an option gives 

![equation](http://latex.codecogs.com/gif.latex?%5CDelta%20%3D%5Cfrac%7B%5Cpartial%20V%7D%7B%5Cpartial%20S%7D)

Investors presumably care about
![equation](http://latex.codecogs.com/gif.latex?O_t%3D%5Ctext%20%7B%20Onset%20event%20at%20time%20bin%20%7D%20t)

I assume this latter quantity would be the basic object of interest to any options trader: it quite literally gives the elasticity of option value with respect to prive. But I could find very little about it online. Wikipedia described the object in question as Lambda (with no additional description) and Investopedia had a short writeup.


