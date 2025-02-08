java c
MTH 360 - Project 1 
Introduction 
Personal finance,   investing, and overall financial literacy are some of the   most   directly impactful applications of the topics   in this course.    Most   notably, saving   and   investing   for   retirement   is extremely important but often scary   because of the   uncertainty   of the market.    While this   project aims to help alleviate some   of the   nervousness,   it   should   be   said that   it can never be eliminated –   the   market   is   uncertain,   and   it   always will   be! 
Whenever the “market”   is   referenced, there could   be   many possibilities,   but   usually   is   some broad   index measure.    An index is   usually the   (weighted)   average   of the   stock price of some   number of companies.    For example, the SP   500   (Standard   and   Poor’s   500   Index)   is the weighted average of the   largest 500 companies traded on an exchange (either the   New York Stock   Exchange (NYSE),   National Association of Securities   Dealers Automatic Quotation System   (NASDAQ), or Chicago   Board of Exchange   (CBoE)).    Other indexes   include the   Dow Jones   Industrial Average (DJIA) and the   NASDAQ composite.    The index   itself is   not and   cannot   be traded,   though   there   are other funds (index funds, exchange traded funds (ETFs),   etc.) that   mimic   the indexes themselves as closely as possible and these funds can be   traded.      These indexes do change over time,   both   in composition and definition.      For   example, the   SP   started as the SP Composite, which contained only   a few   companies,   then   grew   to   90      companies in   1926, and 500 companies   in   1957,   launching the   SP   500. 
Another index   is the Consumer Price   Index   (CPI), which   is   not a   traded   index   at   all. This concept   is completely different than a market   index.      The   CPI   is   a   measure   of   how   expensive a basket of goods costs, for example, the   price   of vehicle fuel, food, and utilities.    The CPI   is a measure of inflation,   showing   how   much   things   cost   in   relation   to      various   points   in history.    The CPI   helps us determine real dollars, which   is   the   raw   cost   of something free of inflation, or, in other words, so that   two   dollar-figures   in   different eras can be compared equivalently.    This   helps   us to determine   whether   the   market returns are really what they calculate to be.      For   example,   if the   market   returns   2%   one   year but   inflation   is 3%, the growth of the cost of goods exceeded   the   growth   of the index that we’ve   presumably   invested   in, which   means we’ve actually lost   purchasing   power of our account.    We will eventually study inflation,   but   not yet. 
Lastly, the Trinity Study is a study of safe withdrawal   rates.    This study   examined different   portfolio mixes (different   percentages of stocks and   bonds) along with withdrawal   rates and market return rates.    The   ultimate   retirement   conundrum   is   how   much money you can withdraw from your retirement account   before   running   out   of money, yet, optimally, you want to spend as much of that   money   as   possible. Considering both   randomness of the market and   in   life experiences, the   correct withdrawal amount   is certainly quite the conundrum.    The   results of the   study   can   be   read   here:
https://www.aaii.com/files/pdf/6794_retirement-savings-choosing-a-withdrawal- rate-that-is-sustainable.pdf 
Once again, we will eventually study stocks and   bonds,   but   not yet.      For the   purposes of this   project, we only   need the   raw account values of some   investment fund, not   necessarily its   composition. As   a   study   of   the    market    and    benchmarking,   just    how    good    are    the    returns    of    the   market?    Do you think you   could   do   better? [Rhetorical questions only; do not answer in the project itself].
Problem 1 
You are   provided a   link to a spreadsheet containing the SP   Composite   values   dating   back to   1871:
• https://shillerdata.com/ 
o   Scroll down and download the ie_data.xls data   set
Use only the   information contained   in the Data tab
This contains monthly values of the   index along with the dividends   paid,   earnings,   and         the consumer price   index at the time, among other   information.      Right   now, you will   only   concern yourself with the SP Composite values.
1.      Use only annual data from   1871 – 2020.    Paste   this   information   into   the Shiller Data Dump sheet   in the spreadsheet provided on   D2L.      You   may   copy   this   data   into other sheets as needed.      I recommend that   the   data   dump   sheet   is unmodified in case you make a mistake   somewhere   and   need   the   original   data   again, you don’t   have to download or recopy anything from   multiple files. 
a.      Use the information   starting   in January of each year.    To   filter   out   these
other months, you can   use   Excel’s filter tool, create an   indicator variable for   January   of   each   year, use   the   ROW   function, or   some   combination   of these, among other options.      That means your final   row should   be   January   2020. 
2.      Calculate various return   rates.
a.      Calculate the   1-year, 5-year,   10-year, and 20-year moving geometric   average annual   return rates for all available   period   ranges.
i.       For example, for a 5-year annual   return rate, you will calculate   the   5-year average annual effective   return rate for the 5-year   period starting   in   1871   (e.g. the   range   1871 –   1875), again for the period starting   in   1872   (e.g. the   range   1872 –   1876), et cetera, all the   way   to the   period ending in   2019. 
1.      This end will use the January   2020   data,   but   this   is      essentially the same as the   end of   December   2019.
2.      Repeat this for all   1-year, 5-year,   10-year, and 20-year   periods.
b.      Graph each of the sequences of average annual   return   rates vs. time
(period) on separate   bar graphs (e.g. all   1-year returns   on   one   graph,   all   5-year average annual returns on a   different   graph).
i.      What do you   notice within the graphs?
ii.      What do you   notice across the   graphs?
c.      Calculate the percentage of positive   return rates for   each   of the   moving   geometric averages.    For perspective, also   calculate the   percentage   of      non-positive   return rates for each of the moving   averages.
i.      What do you   notice about these   percentages across the   length of   the averaging   periods?
1.      How does this   relate to 2.b.i and   2.b.ii?
ii.       In a forecasting perspective, these percentages   can   be viewed   as      probabilities.    In other words, these figures project   answers to   the question “What is the   probability that my   account value   will   grow   in   the   next   x-years?”
1.      Keep in mind that   magnitude   is   important,   not   just these
binary   results.    If the   returns are 0.1%, 0.2%,   and   -50%,   the   account   has a 67% chance to grow,   but the overall   account   value would   be substantially less.    However,   this would   be reflected as a   negative annual average return   rate over the      three-year period, which   is   much more indicative   of the growth of the account.
d.      Create a five-number-summary, arithmetic and geometric means   of the   return   rates, and histograms of   return   rates.
i.       For each of the   n-year periods above, calculate the five-number-
summary:    minimum,   1st    quartile,   median (2nd   quartile), 3rd    quartile,   and   maximum.
1.      The quartiles are each 25th    percentile.      For instance, the   1st         quartile   is the 25th    percentile, the median (2nd    quartile)   is the   50th   percentile, etc.
a.    A   percentile   is the value for which   p% of the   data   lies   below.    You may calculate these   using   the
PERCENTILE   function.
2.      Calculate the arithmetic mean and geometric   mean of the   returns for each set of return   periods.
a.      Compute the arithmetic   mean of the   return rates.
i.      This   is the “traditional” average:

b.      Compute the geometric   mean of the   return rates.
i.      This   is the “compounded” average:

3.      Make a histogram of the data   using   bins of   2%   ranging   from   the minimum to the   maximum value.    Histograms   show   the   percentage of values that fall within these ranges.    This   is, essentially, a distribution of the   return rates, which   is, furthermore, a set of probabilities of the   return   rates.
a.    A   bin   is essentially a   “bucket”   that   data   are   placed   in.      For instance,   return   rates of 4.3%,   1.5%, 4.9%,   1.2%,   and 4.0% would have a   1% bin   containing   a   count   of 2, and a 4% bin   containing   a   count   of   3.      Equivalently, the percent   in each bin   could   also   be   displayed instead of the count, meaning that the   1%   bin would         have a 40% value, and the 4%   bin would   have a   60%   value. 
e.      Exploratory (not graded)
i.      Compare the   histograms,   bar graphs, etc. and draw your own
conclusions about returns over different   investing   periods.    You may   like to change the bin   size, clamp   the   return   rate   region   (e.g. have an underflow   bin of ≤    10%   and /   or an overflow   bin   of   ≥    15%),   or even change the date   range (for example,   analyzing   a   more modern period of something   like   1950+ or maybe the   most   recent   two   decades.). 
Problem 2 - The 4% Rule and Sequencing Risk 
The Trinity Study   is one of the first,   if not the first, studies to   propose the 4% rule: withdrawing 4% of your initial portfolio value   is a safe   amount to withdraw   during retirement   (with the goal of   not going   into   ruin).    Of course, this   is   never   100% guaranteed, but it gives a   place to   start.      For example,   if a   portfolio   has   $1,000,000, then,   ignoring any other deposits or returns, withdrawing 4% ($40,000)   each year would   last 25 years on the principal alone, which   is a   long   enough   period for   many   people entering   retirement, say, at age 65.    Notice   that   this   is   a static withdrawal   rate.      Many   suggest that a dynamic withdrawal   rate   is much   better which could   be either   1) withdrawing 4% of the current portfolio value, or 2) withdrawing lower   or   higher than   4%   depending on market   conditions. 
1.    You are   provided with an   Excel file on   D2L   containing   sequences   of   return   rates   over a period of 25   years.    There are three   sequences –   sequence   one   is   a random order of return rates; sequence two contains   the   exact   same   values   but   in ascending order; sequence three   is a constant sequence.      For   all sequences:
a.      Compute the arithmetic   mean of the   return rates.
i.      This is the “traditional”   average:  
b.      Compute the geometric   mean of the   return rates.
i.      This is the “compounded”   average:  
c.      Assume that you have an account with $1,000,000   currently at   time   0.
Compute the account values at the end of each year assuming   interest   is credited at the end of the year and withdrawals of 4% of the   initial account   value (e.g., $40,000) occur at   y代 写MTH 360 – Project 1Java
代做程序编程语言ear-end   as well.
2.      Financial advisors often charge a fee for their services   in   managed accounts.
These are seemingly small(ish) fees,   usually around   1-2% of the return, though,   as you’d   imagine, over 20+ years, these fees certainly add   (compound)   up.
a.      For the   random sequence of returns, apply a   1%   additive   reduction to   the   return rates and compare the account values to   those without   the reduction.   [An additive reduction of   1%   is called a   reduction of   100 basis points to avoid confusion with a   1% multiplicative   reduction, that   is, a   99%   multiplier:    Ex: (1+0.05 –   0.01) vs.   (1+0.05*0.99)] 
i.      Calculate the   ratio of account values for comparison.    For example,   if one account has $1000 and the   managed account   (with   the fee)         has $900, then the managed account   has   90% of the   account without the fee.    Alternatively, this   is a   10% reduction   in the account   value. 
b.      Repeat with the ordered sequence.
c.      Repeat with the constant sequence.
d.      Exploratory (not graded):    Change the annual effective   interest   rate   and
the fee and see the effects of the fee.    Try extending   the   investing   period (e.g. change 25 years   to 40 years, etc.).    The   interaction of the   parameters   can   be quite surprising.    For example, a   return   rate   of   1% will   allow   the account to grow, and compound   interest will allow a   lot of growth   over   a long period of time.    After 20 years, the account should   have grown   by more than 20% (it would   be 20% using   simple   interest, so   compound interest should   be   more).    If the   management fee   is   1%, then the   net growth of the account   is 0%, and any fee   larger than   1% will   reduce the amount in the account.      The same “intuitive” figures   would   hold   for,   say,   a   5%   return rate – the account should   have at   least doubled after   20   years      (5%   ×   20 years   =   100%   increase), and much more than that for compound   interest, so how   much would this   have   been reduced   by introducing a fee of various values? The   opposite scenario   is also true –   suppose that a manager takes a   1% fee   but   realizes an   extra   2% over what you would do   by yourself, then you are up that   extra   1%,   not   down 1%.    Typically,   people do   better with   investing advisors than on their own,   but this shows you just how much better the   advisors   need   to   do   to   be 
“worth   it.”
e.      For reference, calculate two   lump sum figures:      (1.   10)25   , and   (1.09)25      and   compare their ratios.
i.       Exploratory:    Change the   interest   rate amounts so you can   see   the   disparity of the difference effect.    For   instance,   a   principal   of
$100,000 at 6% produces   an   accumulated value   of about
$430,000.    A 4% rate produces about $267,000, which   is   about   a   40% reduction   in account value.
f.       For the constant   sequence,   check   the   account value   at   time   25   by   using
standard actuarial figures / annuity figures such   as  
i.       Note:    This   means that the   prior calculations   in   parts (a) –   (e)
should be done without these formulas (reminder: see   the Grading Comments below).
3.      Exploratory (not graded)
a.      Visit this website   here:
i. https://engaging-data.com/early-retirement-calculators-and-tools/ 
b.    This website contains a few financial   calculators with   great   graphs.      My
personal favorite   is the one that   incorporates mortality   into the analysis and projection, but this material   is   more for STT   455 /   456.      You will   notice   a   lot of similarities   in these graphs and this project, though this   project   is more focused on the pure   mathematics of it all   and   demystifying   how the   above website creates these graphs and analyses. 
Problem 3 - Your Own Investment and Timing the Market 
One standard piece of investing advice is   that   it   is   not   about   timing the   market,   it’s   about   time in the market.    Studies have shown that   missing   only   a   small fraction   of the   best trading days over a 20-year period can   reduce a final   portfolio   value   by over FIFTY percent.    Roughly speaking, there are approximately 250 trading   days   in   a   year, which   is 5000 trading days   in 20 years, and   missing as   something   as   small   as the   10   best trading days out of the 5000 can result   in this   50%   portfolio   value   reduction.
You have a pretend $10,000 to   invest   in the   stock   market.      You   may   invest   this   money   in the market however you choose,   but   it must   be   a   traded   stock   on   the   exchange.    An   easy way to search for companies is obviously through any   search   engine,   but   also something   like YahooFinance where you can search for companies by sector   (e.g. technology, medicine, etc.) and see the ticker to track   (e.g.   Microsoft   is   MSFT,   Apple   is   AAPL (yes, two As   and   not   Ps)). 
This   problem   is semester-long and   is for you to track on a weekly basis,   so   I would   recommend   keeping this simple, but here are   a few   guidelines:
1.    Your performance does   not affect   your   grade.      This   is   simply for fun,   but   also   to      increase your competency and mastery of portfolio values,   return   rates,   buying /   selling,   etc.
2.    You must   participate.    This   means you   cannot simply   hold   $10,000   and   do   nothing with   it.
a.    Yes,   holding cash   is a valid strategy,   but   we’re   trying   to   do   some   math   on   the topic, and zero trading volume doesn’t lend   itself well to computation.
b.    You can hold some cash   as   part of   a   trading   strategy   (e.g.   you want   some   cash to   be able to purchase something   at   a   better   price),   but   not   all $10,000.
3.      No   cryptocurrencies, non-fungible tokens, crowd-funded funds,   real estate, art,   or   anything that isn’t   basically a   stock.
a.    Yes, these are valid   forms of   investment,   but we’re trying   to   keep   it   simple.   Your tasks are:
1.      Record the date and fund value on that date.      Keep the   frequency   regular,   such         as   recording the fund value every Saturday when the market   is   closed   and   prices   have settled.
2.    Your fund value can be   composed of different   assets,   so   if you choose   to   mix
assets, you’ll   have to   record the amount of shares that you   buy, sell,   or otherwise   trade, and the amount of cash you’re   holding.    You may trade   fractional   shares.
3.      Calculate the weekly return rates of your total   portfolio.
a.      Remember that any cash   is also part   of the   portfolio value.
4.      Plot the weekly   portfolio values and   return rates versus time on   separate   graphs.   Additionally:
1.      Record the value of the SP 500 (^SPX)   and   calculate   the weekly   return   rates.
a.      Optionally, you may like to calculate   the total   return   (the   cumulative   return)   to compare   how your portfolio   is doing against this   benchmark.    We will eventually do this comparison   in   Project 4 when we have   much   more data, so this   is not   necessary at   this   moment.   The columns   are: 
•          Date – The date you   record your prices and calculate your values.      These   should   be exactly weekly periodic (e.g.   every   Saturday).
•         Ticker – The “abbreviation” or “code” for the security.
•          Buy / Sell /   Hold –   Enter what you are doing this week.      If buying   a   new   security,            enter “Buy.”    If you are selling, enter “Sell.”    If you   are doing   nothing,   enter “   Hold.”
•          Price   per Share – The current   trading price   of the security.
•         # Shares –   How many shares of the security you   are trading   or   currently   own.
•         Cost – The total cost of the purchase   (or negative   if   sold).      This   will   be   0   if you   have   no activity.
•         Cash –   How   much   leftover cash you are   holding.
•          Portfolio Value – This is the value of your assets,   equal to   the   current   price   per   share times the number of shares   (for every security) plus   any   leftover   cash.      If   you   have multiple securities, you should   have an additional   entry for the   total portfolio value: the sum of the values of your securities and   cash.
•          Return   Rate – This   is the weekly   return   rate of your securities.    Ultimately,   I   am   interested   in the return rate of your total   portfolio   (which   can   be   one   single security),   but you   may like to   keep track of how each   security   is   individually   performing. 
One other item you may find useful   is   the weight of each   security   in   your   portfolio,   which   would   be the   percentage value contribution of the security to the entire   portfolio.      For instance, you may   initially buy two securities that compose   50%   of the   portfolio   each (say, you spend $5000 on two securities,   but perhaps   at   different   prices   and /   or   amount   of shares), but, after some time, one security may   be   worth   $8000   and   another worth $4000, and then your portfolio has a 67%/33%   split.      This   can   lead   to   sensitivity   in   your   portfolio with   having too   much   importance on one single security.    You may   decide   to rebalance, go all-in, or do   nothing, but   it may   be   of   interest   to   you   to   know.      This   is   not necessary,   but you   may   use the column and include   it   if you so   choose.    As   you   will come to   learn   in this class, calculating the total   portfolio   return can   be calculated   directly   from the total   portfolio value or it can be   reconstituted   by   using   the   individual   asset returns with the respective weights.
You may find tools   such   as
• https://www.portfoliovisualizer.com/and
• https://www.etfrc.com/ 
valuable. 
Grading Comments 
This   project   is to be completed using an electronic   spreadsheet   such   as   Microsoft   Excel   or OpenOffice.    I have   included an   electronic version   of the   required spreadsheet   on D2L with designated sheets for the problems.    When completing the   problems,   cell   referencing   is   important,   but you   may copy / paste any values from other sheets   as   convenient. 
The   problems should be completed using very   little   “shortcut” formulas that   we   know from the course material and should   be   more   by a   term-by-term   calculation,   unless otherwise   instructed.    As a general statement,   pretend that you don’t   know any shortcut   formulas and   must calculate the values term-by-term using basic   arithmetic.    You   may         like to check your answer using the shortcut formulas,   but   do   not   use   them   to   compute      the actual values for the   problem   (again, unless otherwise   instructed). 
To be submitted 
You will submit your spreadsheet   file to   D2L.    Please format the file   name   as:
Last_name, First_name - MTH 360 - Project 1 
Please   include your group members’ names somewhere   in the file, whether   it   be   in the         file   name, in some of the cells on the   problem   sheet,   or   in   a   note   in your   upload   on   D2L.





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
