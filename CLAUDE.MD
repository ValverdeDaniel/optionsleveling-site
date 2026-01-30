================================================================================
DEVELOPER SPEC: OPTIONS LEVELING LANDING PAGE
================================================================================

OVERVIEW
--------
This document outlines the content and messaging strategy for the Options
Leveling landing page, which will serve as the informational gateway to the
main application at app.optionsleveling.com.


================================================================================
PLATFORM VALUE PROPOSITION
================================================================================

THE CORE PROBLEM WE SOLVE
-------------------------
Investors face a fundamental question when considering any stock:
"Should I buy the stock, buy an options contract, or not invest at all?"

Traditional approaches make this decision difficult because:

1. OPPORTUNITY COST IS INVISIBLE
   Comparing stock returns vs. options returns requires complex calculations

2. TIME DECAY IS MISUNDERSTOOD
   Options lose value daily, but how does this affect different strategies?

3. SCENARIO ANALYSIS IS TEDIOUS
   "What if the stock goes up 20%? What about 10%?"

4. POSITION TRACKING IS FRAGMENTED
   No centralized way to track options positions against cost basis


OUR SOLUTION
------------
Options Leveling provides CLARITY THROUGH SIMULATION. We show you exactly
what your options position would be worth under any market scenario, helping
you make data-driven decisions about where to allocate capital.


================================================================================
LANDING PAGE CONTENT STRUCTURE
================================================================================

--------------------------------------------------------------------------------
SECTION 1: HERO - THE HOOK
--------------------------------------------------------------------------------

HEADLINE: "Know Your Options Before You Trade"

SUBHEADLINE: "Compare potential returns between stocks and options.
Simulate scenarios. Make informed decisions."

SUPPORTING COPY:
- Stop guessing whether buying the stock or the option is the better play
- See exactly how your investment would perform under different market conditions
- Track your positions and know when to exit

CTA: "Start Analyzing" (links to app.optionsleveling.com)


--------------------------------------------------------------------------------
SECTION 2: THE PROBLEM STATEMENT
--------------------------------------------------------------------------------

HEADLINE: "The Hidden Cost of Guessing"

CONTENT POINTS:

1. THE STOCK VS. OPTIONS DILEMMA
   - Buying 100 shares of AAPL at $200 = $20,000 investment
   - Buying 1 call option might cost $1,500
   - But which one makes more money if AAPL goes up 15%?
   - What if it only goes up 5%? Or takes 6 months instead of 3?

2. TIME WORKS AGAINST YOU
   - Options contracts lose value every single day (theta decay)
   - A 90-day option and a 365-day option behave completely differently
   - Without simulation, you're flying blind

3. SCENARIOS MATTER
   - "I think the stock will go up" is not a strategy
   - How MUCH will it go up? Over WHAT timeframe?
   - Different scenarios require different contract selections


--------------------------------------------------------------------------------
SECTION 3: FEATURE - THE SCREENER
--------------------------------------------------------------------------------

HEADLINE: "Find the Right Contract"

WHAT IT DOES:
The Options Screener helps you discover options contracts that match your
market thesis by simulating potential returns before you buy.

KEY CAPABILITIES:

1. THREE MODES FOR EVERY EXPERIENCE LEVEL
   - BASIC MODE: Choose from 6 pre-built strategies (Short-term ITM, LEAPS OTM, etc.)
   - INTERMEDIATE MODE: Mix and match expiration windows, strike positions, and expected moves
   - ADVANCED MODE: Full control over every parameter for sophisticated analysis

2. SCENARIO-BASED ANALYSIS
   - Input your expected stock movement (+10%, +25%, +50%, etc.)
   - Set your target timeframe (when do you expect the move?)
   - See projected option values using Black-Scholes pricing

3. COMPARE ACROSS CONTRACTS
   - View results sorted by potential % gain
   - Compare ITM vs OTM vs ATM strikes
   - See how different expirations affect returns
   - Export to CSV for further analysis

VISUAL SUGGESTION: Screenshot showing the screener results table with
simulated gains highlighted


--------------------------------------------------------------------------------
SECTION 4: FEATURE - THE WATCHLIST
--------------------------------------------------------------------------------

HEADLINE: "Track Your Positions Like a Pro"

WHAT IT DOES:
The Watchlist lets you save contracts you own (or are considering), track
their performance over time, and simulate how they would perform under
different market conditions.

KEY CAPABILITIES:

1. PORTFOLIO TRACKING
   - Save contracts with your actual cost basis
   - See real-time premium and underlying price changes
   - Track % change from your entry point
   - Organize contracts into groups (by strategy, sector, or timeframe)

2. MULTI-SCENARIO SIMULATION
   - Each saved contract shows performance under 7 scenarios:
     +/-5%, +/-10%, +/-20%, +/-35%, +/-50%, +/-100%, +/-200%
   - See both upside potential and downside risk at a glance
   - Calculate exact P&L based on your position size

3. TIME-BASED TRACKING
   - Set target exit dates and watch the countdown
   - See how time decay affects your positions daily
   - Reset countdowns when you adjust your thesis

4. HISTORICAL PREMIUM TRACKING
   - View charts showing option premium history
   - Compare current price to your entry price
   - Make informed decisions about when to exit

VISUAL SUGGESTION: Screenshot showing watchlist groups with contract cards
and simulation results


--------------------------------------------------------------------------------
SECTION 5: FEATURE - OPTIONS PREMIUM CHARTS
--------------------------------------------------------------------------------

HEADLINE: "See the Full Picture"

WHAT IT DOES:
View historical option premium prices alongside the underlying stock.
Understand how your contract's value has changed over time.

KEY POINTS:
- Charts show premium history for any saved contract
- Compare option price movement to underlying stock movement
- Identify patterns and optimal entry/exit points
- Track implied volatility changes over time

VISUAL SUGGESTION: Screenshot of the premium chart view within watchlist


--------------------------------------------------------------------------------
SECTION 6: HOW IT WORKS (USER FLOW)
--------------------------------------------------------------------------------

HEADLINE: "From Thesis to Trade in 3 Steps"

STEP 1: DEFINE YOUR THESIS
- Pick your tickers (AAPL, MSFT, NVDA, etc.)n
- Set your expected stock movement (+20% gain? -10% pullback?)
- Choose your timeframe (30 days? 6 months? LEAPS?)

STEP 2: FIND MATCHING CONTRACTS
- The screener finds options that match your criteria
- Compare projected returns across strikes and expirations
- See Greeks (delta, theta, gamma) for each contract
- Identify which contract maximizes your risk/reward

STEP 3: TRACK AND ADJUST
- Save contracts to your watchlist
- Monitor real-time performance vs. your cost basis
- Run simulations as market conditions change
- Know exactly when to exit based on your targets


--------------------------------------------------------------------------------
SECTION 7: WHO THIS IS FOR
--------------------------------------------------------------------------------

HEADLINE: "Built for Options Traders Who Want Clarity"

TARGET AUDIENCES:

1. STOCK INVESTORS CONSIDERING OPTIONS
   - "I want to try options but don't know where to start"
   - "I want to amplify my returns without betting the farm"
   - Perfect for: Long calls on stocks you're already bullish on

2. ACTIVE OPTIONS TRADERS
   - "I need a faster way to screen contracts"
   - "I want to compare scenarios without spreadsheets"
   - Perfect for: Swing trading options, earnings plays

3. LONG-TERM INVESTORS USING LEAPS
   - "I want leveraged exposure with minimal time decay"
   - "I'm looking for stock replacement strategies"
   - Perfect for: Deep ITM LEAPS as stock alternatives


--------------------------------------------------------------------------------
SECTION 8: KEY DIFFERENTIATORS
--------------------------------------------------------------------------------

HEADLINE: "Why Options Leveling?"

POINTS TO EMPHASIZE:

1. SIMULATION-FIRST APPROACH
   - Every analysis shows projected values under your specific scenario
   - Not just current prices - future prices based on your thesis

2. MULTIPLE SCENARIOS AT ONCE
   - Watchlist shows 7 different outcomes simultaneously
   - Understand your best case AND worst case

3. REAL DATA, REAL-TIME
   - Powered by Polygon.io for accurate market data
   - Greeks calculated using industry-standard Black-Scholes

4. POSITION TRACKING WITH COST BASIS
   - Track actual P&L against what you paid
   - See % change from your entry, not just market price

5. NO COMPLEXITY HIDDEN
   - See all Greeks (delta, theta, gamma, vega, rho)
   - View bid/ask spreads, volume, open interest
   - Export everything to CSV for your own analysis


--------------------------------------------------------------------------------
SECTION 9: PRICING & CTA
--------------------------------------------------------------------------------

HEADLINE: "Ready to Level Up Your Options Game?"

CONTENT:
- Free tier available (details TBD)
- Premium features for serious traders (details TBD)

PRIMARY CTA: "Get Started Free" (links to app.optionsleveling.com/signup)
SECONDARY CTA: "See Pricing" (links to pricing page - TBD)


--------------------------------------------------------------------------------
SECTION 10: FOOTER
--------------------------------------------------------------------------------

- Link to app: app.optionsleveling.com
- About (TBD)
- Pricing (TBD)
- Contact/Support (TBD)
- Legal disclaimers about options trading risks


================================================================================
KEY MESSAGING THEMES
================================================================================

CLARITY OVER COMPLEXITY
-----------------------
The platform takes complex options math and makes it visual and intuitive.
Users don't need to understand Black-Scholes - they just need to see the
projected outcomes.

OPPORTUNITY COST AWARENESS
--------------------------
The recurring theme should be: "Know what you're giving up." Whether it's
comparing stock returns to option returns, or comparing different option
strategies, the platform reveals the true opportunity cost of each decision.

SCENARIO-DRIVEN DECISIONS
-------------------------
Emphasize that markets are unpredictable, but scenarios are plannable.
Users define their expectations, and the platform shows what happens under
those conditions.

TRACK PERFORMANCE, NOT JUST PRICES
----------------------------------
The watchlist isn't just a price tracker - it's a performance tracker against
your actual cost basis. This is the "true P&L" that matters to traders.


================================================================================
TECHNICAL TERMS TO EXPLAIN (GLOSSARY)
================================================================================

For users who may be new to options, consider explaining:

1. CALL OPTION - The right to BUY a stock at a set price
2. PUT OPTION - The right to SELL a stock at a set price
3. STRIKE PRICE - The price at which you can buy/sell
4. PREMIUM - The cost of the option contract
5. EXPIRATION - When the option contract expires
6. ITM/ATM/OTM - In/At/Out of the Money - where strike is vs. current price
7. GREEKS - Metrics showing option sensitivity (delta, theta, gamma, vega)
8. BLACK-SCHOLES - Industry-standard formula for pricing options
9. LEAPS - Long-term options (1+ year expirations)


================================================================================
RECOMMENDED VISUAL ASSETS
================================================================================

1. HERO SECTION - Abstract visualization of options profit/loss curves
2. SCREENER FEATURE - Screenshot of results table with highlighted gains
3. WATCHLIST FEATURE - Screenshot of groups with contract cards
4. CHARTS FEATURE - Screenshot of premium history chart
5. HOW IT WORKS - Simple 3-step icons/illustrations
6. COMPARISON - Side-by-side visual of stock investment vs. options investment


================================================================================
PAGE STRUCTURE RECOMMENDATIONS
================================================================================

NAVIGATION
----------
- Logo (links to landing page)
- Features (anchor to features section)
- How It Works (anchor)
- Pricing (links to pricing page - TBD)
- Login (links to app.optionsleveling.com/login)
- Get Started (CTA button, links to signup)

MOBILE CONSIDERATIONS
---------------------
- Collapse navigation to hamburger menu
- Stack feature sections vertically
- Ensure screenshots are readable on mobile
- CTA buttons should be full-width on mobile


================================================================================
FUTURE PAGES (OUT OF SCOPE FOR THIS SPEC)
================================================================================

1. PRICING PAGE - Tier comparison, feature matrix
2. PROFILE PAGE - User settings, preferences
3. ABOUT PAGE - Company story, team
4. BLOG/EDUCATION - Options tutorials, market analysis


================================================================================
IMPLEMENTATION NOTES
================================================================================

This landing page should be built as a separate static site or marketing site
that links users to the main application at app.optionsleveling.com.

The landing page's primary goal is:
1. Explain the platform's value proposition
2. Educate potential users on what they can accomplish
3. Drive signups/conversions to the main app

All actual functionality (screener, watchlist, charts) lives in the main
application - the landing page is purely informational and marketing-focused.


================================================================================
DATA FLOW REFERENCE (FOR DEVELOPERS)
================================================================================

SCREENER DATA FLOW:
1. User selects strategy parameters (tickers, strike %, expiration, expected move)
2. Frontend sends POST to /api/run-screener/ with param_sets array
3. Backend calls run_multiple_analyses() which iterates through scenarios
4. For each scenario, analyze_options_unicorn() fetches real-time data via Polygon.io
5. Black-Scholes calculates projected option values at target date
6. Results returned with: contract details, current premium, simulated premium,
   % gain, Greeks, market data
7. Frontend displays sortable/filterable table with export capability

WATCHLIST DATA FLOW:
1. User saves contract with cost basis (ticker, strike, expiration, # contracts, avg cost)
2. Backend captures initial snapshot (underlying_price_at_add, initial_premium, initial_equity)
3. On simulation, whole_watchlist() creates 7 scenarios per contract (+/-5% to +/-200%)
4. Black-Scholes projects option value at each scenario
5. Results include: simulated premiums, equity values, % changes from cost basis
6. Frontend displays contract cards with real-time tracking and scenario tables

KEY MODELS:
- SavedContract: Tracks individual positions with cost basis and % change calculations
- WatchlistGroup: Organizes contracts into portfolios (many-to-many)
- SavedScreenerParameter: Saves user's screening configurations for reuse


================================================================================
END OF SPEC
================================================================================
