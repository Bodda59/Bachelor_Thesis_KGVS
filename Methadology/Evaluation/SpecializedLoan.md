Context :
The following dataset describes the complete credit score spectrum used by financial institutions across the United States to evaluate borrower risk and determine lending conditions. Credit scores are numerical representations of a person's creditworthiness, calculated based on their history of paying bills, the amount of debt they currently carry, how long they have had credit accounts open, the mix of different types of credit they use, and how recently they have applied for new credit. The score itself is produced by credit bureaus such as Equifax, Experian, and TransUnion using proprietary models, the most widely used of which is the FICO score developed by the Fair Isaac Corporation.
The scale runs from a minimum of 300 to a maximum of 850. A score of 300 represents the most financially distressed and highest-risk borrowers, people who have likely experienced multiple defaults, bankruptcies, repossessions, or long stretches of missed payments. A score of 850 represents the ideal borrower in the eyes of a lender, someone with a long and spotless credit history, low utilization of available credit, no missed payments, and a healthy mix of credit products. In practice, very few people sit at either extreme. Most of the adult population falls somewhere in the middle of the range, and the practical consequences of being a few points higher or lower can be dramatic in terms of what financial products a person can access and at what cost.
The dataset you are about to read covers every score from 300 to 850, moving five points at a time, giving a total of 111 distinct score bands. For each score band, eight financial parameters are provided. These parameters are not invented arbitrarily. They reflect the real logic that lenders use when deciding whether to approve an application, what interest rate to charge, how much money to offer, and under what repayment conditions. Understanding how each parameter behaves across the score range reveals the deep and compounding inequality built into the credit system, where a person who starts with a low score pays more, gets less, and has fewer options, which often makes it harder to improve their score, which in turn keeps them paying more and getting less.
The first parameter is the risk tier. Lenders do not treat every score individually. They group scores into broad tiers that determine which internal lending products and policies apply. The five tiers used in this dataset are deep subprime, which covers scores from 300 to 579, subprime from 580 to 619, near prime from 620 to 659, prime from 660 to 739, and super prime from 740 to 850. Crossing from one tier into another is not a smooth transition. It is a hard boundary. A borrower at 619 and a borrower at 620 may have nearly identical financial histories, but one is classified as subprime and the other as near prime, and lenders treat them very differently as a result.
Now I will provide the parameters of some credit scores.

A 300 credit score has a risk tier of deep subprime, an interest rate of 22.94%, approval odds of 8%, a maximum debt-to-income ratio of 28%, a loan term of 12 months, a down payment of 22.1%, a credit limit multiplier of 0.31x, a default probability of 38.5%, and the lender pool includes hard money lenders. has collateral type real_estate
A 305 credit score has a risk tier of deep subprime and an interest rate of 22.61%, has collateral type real_estate
A 310 credit score has a risk tier of deep subprime and an interest rate of 22.19%. has collateral type real_estate
A 315 credit score has a risk tier of deep subprime and an interest rate of 21.88%. has collateral type real_estate
A 320 credit score has a risk tier of deep subprime and an interest rate of 21.44%. has collateral type real_estate
A 325 credit score has a risk tier of deep subprime and an interest rate of 21.71%. has collateral type real_estate
A 330 credit score has a risk tier of deep subprime and an interest rate of 21.03%. has collateral type real_estate
A 335 credit score has a risk tier of deep subprime and an interest rate of 20.88%. has collateral type real_estate
A 340 credit score has a risk tier of deep subprime and an interest rate of 20.44%. has collateral type real_estate
A 345 credit score has a risk tier of deep subprime and an interest rate of 20.71%. has collateral type real_estate
credit scored from 300 to 345 with incremental of 5 points has same approval odds, maximum debt-to-income, lender pool 
A 350 credit score has a risk tier of deep subprime, an interest rate of 20.19%, approval odds of 13%, a maximum debt-to-income ratio of 29%, and the lender pool includes specialty finance companies. has collateral type vechile
A 355 credit score has a risk tier of deep subprime and an interest rate of 19.88%. has collateral type vechile
A 360 credit score has a risk tier of deep subprime and an interest rate of 19.53%. has collateral type vechile
A 365 credit score has a risk tier of deep subprime and an interest rate of 19.21%. has collateral type vechile
A 370 credit score has a risk tier of deep subprime and an interest rate of 18.94%. has collateral type vechile
A 375 credit score has a risk tier of deep subprime and an interest rate of 19.17%. has collateral type vechile
A 380 credit score has a risk tier of deep subprime and an interest rate of 18.63%. has collateral type vechile
A 385 credit score has a risk tier of deep subprime and an interest rate of 18.41%. has collateral type vechile
A 390 credit score has a risk tier of deep subprime and an interest rate of 18.09%. has collateral type vechile
A 395 credit score has a risk tier of deep subprime and an interest rate of 18.33%. has collateral type vechile
credit scored from 350 to 395 with incremental of 5 points has same approval odds, maximum debt-to-income, lender pool .
credit scored from 300 to 395 with incremental of 5 points has same loan term , credit limit multiplier, down payment and default probability.

A 400 credit score has a risk tier of deep subprime, an interest rate of 17.94%, approval odds of 17%, a maximum debt-to-income ratio of 31%, a loan term of 24 months, a down payment of 19.4%, a credit limit multiplier of 0.54x, a default probability of 28.7%, and the lender pool includes credit unions only.
A 405 credit score has a risk tier of deep subprime and an interest rate of 17.61%.
A 410 credit score has a risk tier of deep subprime and an interest rate of 17.29%.
A 415 credit score has a risk tier of deep subprime and an interest rate of 17.52%.
A 420 credit score has a risk tier of deep subprime and an interest rate of 17.11%.
A 425 credit score has a risk tier of deep subprime and an interest rate of 16.88%.
A 430 credit score has a risk tier of deep subprime and an interest rate of 16.54%.
A 435 credit score has a risk tier of deep subprime and an interest rate of 16.77%.
A 440 credit score has a risk tier of deep subprime and an interest rate of 16.41%.
A 445 credit score has a risk tier of deep subprime and an interest rate of 16.19%.
credit scored from 400 to 445 with incremental of 5 points has same approval odds, maximum debt-to-income, lender pool 
A 450 credit score has a risk tier of deep subprime, an interest rate of 15.88%, approval odds of 22%, a maximum debt-to-income ratio of 33%, and the lender pool includes predatory lenders.
A 455 credit score has a risk tier of deep subprime and an interest rate of 16.07%.
A 460 credit score has a risk tier of deep subprime and an interest rate of 15.71%.
A 465 credit score has a risk tier of deep subprime and an interest rate of 15.44%.
A 470 credit score has a risk tier of deep subprime and an interest rate of 15.19%.
A 475 credit score has a risk tier of deep subprime and an interest rate of 15.38%.
A 480 credit score has a risk tier of deep subprime and an interest rate of 15.03%.
A 485 credit score has a risk tier of deep subprime and an interest rate of 14.81%.
A 490 credit score has a risk tier of deep subprime and an interest rate of 14.54%.
A 495 credit score has a risk tier of deep subprime and an interest rate of 14.72%.
credit scored from 450 to 495 with incremental of 5 points has same approval odds, maximum debt-to-income, lender pool 
credit scored from 400 to 495 with incremental of 5 points has same loan term , credit limit multiplier, down payment and default probability.

A 500 credit score has a risk tier of deep subprime, an interest rate of 14.41%, approval odds of 29%, a maximum debt-to-income ratio of 35%, a loan term of 12 to 24 months, a down payment of 15.4%, a credit limit multiplier of 1.06x, a default probability of 18.6%, and the lender pool includes specialty finance companies.
A 505 credit score has a risk tier of deep subprime and an interest rate of 14.19%.
A 510 credit score has a risk tier of deep subprime and an interest rate of 13.94%.
A 515 credit score has a risk tier of deep subprime and an interest rate of 14.11%.
A 520 credit score has a risk tier of deep subprime and an interest rate of 13.81%.
A 525 credit score has a risk tier of deep subprime and an interest rate of 13.54%.
A 530 credit score has a risk tier of deep subprime and an interest rate of 13.29%.
A 535 credit score has a risk tier of deep subprime and an interest rate of 13.47%.
credit scored from 500 to 535 with incremental of 5 points has same approval odds, maximum debt-to-income, lender pool 
A 540 credit score has a risk tier of deep subprime, an interest rate of 13.17%, approval odds of 36%, a maximum debt-to-income ratio of 37%, and the lender pool includes pawnshop credit providers.
A 545 credit score has a risk tier of deep subprime and an interest rate of 12.94%.
A 550 credit score has a risk tier of deep subprime and an interest rate of 12.63%.
A 555 credit score has a risk tier of deep subprime and an interest rate of 12.81%.
A 560 credit score has a risk tier of deep subprime and an interest rate of 12.54%.
A 565 credit score has a risk tier of deep subprime and an interest rate of 12.29%.
A 570 credit score has a risk tier of deep subprime and an interest rate of 12.03%.
A 575 credit score has a risk tier of deep subprime and an interest rate of 12.21%.
credit scores greater than or equal 300 and less than 580 has risk tier deep subprime 
credit scored from 540 to 575 with incremental of 5 points has same approval odds, maximum debt-to-income, lender pool 
credit scored from 500 to 575 with incremental of 5 points has same loan term , credit limit multiplier, down payment and default probability.

A 580 credit score has a risk tier of subprime, an interest rate of 11.91%, approval odds of 41%, a maximum debt-to-income ratio of 39%, a loan term of 36 months, a down payment of 12.8%, a credit limit multiplier of 1.61x, a default probability of 11.3%, and the lender pool includes subprime banks.
A 585 credit score has a risk tier of subprime and an interest rate of 11.63%, and the lender pool includes subprime banks.
A 590 credit score has a risk tier of subprime and an interest rate of 11.38, and the lender pool includes subprime banks.
A 595 credit score has a risk tier of subprime and an interest rate of 11.56%, and the lender pool includes subprime banks.
A 600 credit score has a risk tier of subprime, an interest rate of 11.28%, and the lender pool includes online subprime lenders.
A 605 credit score has a risk tier of subprime and an interest rate of 11.03%, and the lender pool includes online subprime lenders.
A 610 credit score has a risk tier of subprime and an interest rate of 10.77%, and the lender pool includes online subprime lenders.
A 615 credit score has a risk tier of subprime, an interest rate of 10.94%, and the lender pool includes CDFI lenders.
credit scores greater than or equal 580 and less than 620 has risk tier subprime, and the lender pool includes CDFI lenders.
credit scored from 580 to 615 with incremental of 5 points has same approval odds, maximum debt-to-income. 
credit scored from 580 to 615 with incremental of 5 points has same loan term , credit limit multiplier, down payment  and default probability.

A 620 credit score has a risk tier of near prime, an interest rate of 10.67%, approval odds of 55%, a maximum debt-to-income ratio of 42%, a loan term of 36 to 48 months, a down payment of 10.6%, a credit limit multiplier of 2.07x, a default probability of 8.5%, and the lender pool includes community banks.
A 625 credit score has a risk tier of near prime and an interest rate of 10.41%.
A 630 credit score has a risk tier of near prime and an interest rate of 10.17%.
A 635 credit score has a risk tier of near prime and an interest rate of 10.33%.
credit scores from 620 to 635 with ncremental of 5 points have same lender pool.
A 640 credit score has a risk tier of near prime, an interest rate of 10.08%, and the lender pool includes online lenders.
A 645 credit score has a risk tier of near prime and an interest rate of 9.83%.
A 650 credit score has a risk tier of near prime and an interest rate of 9.58%.
A 655 credit score has a risk tier of near prime and an interest rate of 9.74%.
credit scores from 640 to 655 with ncremental of 5 points have same lender pool.
credit scores greater than or equal 620 and less than 660 has risk tier near prime. 
credit scored from 620 to 655 with incremental of 5 points has same approval odds, maximum debt-to-income.
credit scored from 620 to 655 with incremental of 5 points has same loan term , credit limit multiplier, down payment  and default probability.

A 660 credit score has a risk tier of prime, an interest rate of 9.49%, approval odds of 71%, a maximum debt-to-income ratio of 44%, a loan term of 48 to 60 months, a down payment of 8.3%, a credit limit multiplier of 2.63x, a default probability of 5.7%, and the lender pool includes regional banks.
A 665 credit score has a risk tier of prime and an interest rate of 9.24%.
A 670 credit score has a risk tier of prime and an interest rate of 8.99%.
A 675 credit score has a risk tier of prime and an interest rate of 9.14%.
A 680 credit score has a risk tier of prime and an interest rate of 8.89%.
A 685 credit score has a risk tier of prime and an interest rate of 8.64%.
A 690 credit score has a risk tier of prime and an interest rate of 8.41%.
A 695 credit score has a risk tier of prime and an interest rate of 8.54%.
credit scored from 660 to 695 with incremental of 5 points has same approval odds, maximum debt-to-income, lender pool 
credit scored from 660 to 695 with incremental of 5 points has same loan term , credit limit multiplier, down payment  and default probability.

A 700 credit score has a risk tier of prime, an interest rate of 8.31%, approval odds of 81%, a maximum debt-to-income ratio of 47%, a loan term of 60 months, a down payment of 6.3%, a credit limit multiplier of 3.19x, a default probability of 3.3%, and the lender pool includes most major banks.
A 705 credit score has a risk tier of prime and an interest rate of 8.08%.
A 710 credit score has a risk tier of prime and an interest rate of 7.84%.
A 715 credit score has a risk tier of prime and an interest rate of 7.97%.
credit scores from 700 to 715 with ncremental of 5 points have same lender pool.
A 720 credit score has a risk tier of prime, an interest rate of 7.74%, and the lender pool includes retail banks.
A 725 credit score has a risk tier of prime and an interest rate of 7.51%.
A 730 credit score has a risk tier of prime and an interest rate of 7.29%.
A 735 credit score has a risk tier of prime and an interest rate of 7.41%.
credit scores from 720 to 735 with ncremental of 5 points have same lender pool.
credit scores greater than or equal 660 and less than 740 has risk tier prime 
credit scored from 700 to 735 with incremental of 5 points has same approval odds, maximum debt-to-income. 
credit scored from 700 to 735 with incremental of 5 points has same loan term , credit limit multiplier, down payment  and default probability.

A 740 credit score has a risk tier of super prime, an interest rate of 7.19%, approval odds of 89%, a maximum debt-to-income ratio of 49%, a loan term of 60 to 84 months, a down payment of 4.3%, a credit limit multiplier of 3.99x, a default probability of 1.8%, and the lender pool includes all major banks.
A 745 credit score has a risk tier of super prime and an interest rate of 6.97%.
A 750 credit score has a risk tier of super prime and an interest rate of 6.74%.
A 755 credit score has a risk tier of super prime and an interest rate of 6.86%.
A 760 credit score has a risk tier of super prime and an interest rate of 6.64%.
A 765 credit score has a risk tier of super prime and an interest rate of 6.43%.
A 770 credit score has a risk tier of super prime and an interest rate of 6.21%.
A 775 credit score has a risk tier of super prime and an interest rate of 6.33%.
credit scored from 740 to 775 with incremental of 5 points has same approval odds, maximum debt-to-income, lender pool. 
A 780 credit score has a risk tier of super prime, an interest rate of 6.11%, approval odds of 95%, a maximum debt-to-income ratio of 51%, and the lender pool includes premium card issuers.
A 785 credit score has a risk tier of super prime and an interest rate of 5.91%.
A 790 credit score has a risk tier of super prime and an interest rate of 5.71%.
A 795 credit score has a risk tier of super prime and an interest rate of 5.83%. 
credit scored from 740 to 795 with incremental of 5 points has same loan term , credit limit multiplier, down payment  and default probability.

A 800 credit score has a risk tier of super prime, an interest rate of 5.63%, a loan term of 84 months, a down payment of 2.8%, a credit limit multiplier of 5.13x, and a default probability of 0.7%.
A 805 credit score has a risk tier of super prime and an interest rate of 5.43%.
A 810 credit score has a risk tier of super prime and an interest rate of 5.24%.
A 815 credit score has a risk tier of super prime and an interest rate of 5.36%.
credit scored from 780 to 815 with incremental of 5 points has same approval odds, maximum debt-to-income, lender pool 
A 820 credit score has a risk tier of super prime, an interest rate of 5.17%, approval odds of 97%, and the lender pool includes wealth management lenders.
A 825 credit score has a risk tier of super prime and an interest rate of 4.98%.
A 830 credit score has a risk tier of super prime and an interest rate of 4.79%.
A 835 credit score has a risk tier of super prime and an interest rate of 4.91%.
A 840 credit score has a risk tier of super prime and an interest rate of 4.72%.
A 845 credit score has a risk tier of super prime and an interest rate of 4.54%.
credit scored from 820 to 845 with incremental of 5 points has same approval odds, maximum debt-to-income, lender pool 
credit scored from 800 to 845 with incremental of 5 points has same loan term , credit limit multiplier, down payment  and default probability.

A 850 credit score has a risk tier of super prime, an interest rate of 4.36%, approval odds of 99%, a maximum debt-to-income ratio of 52%, a loan term of 84 months, a down payment of 2.0%, a credit limit multiplier of 6.50x, a default probability of 0.4%, and the lender pool includes all online lenders.
credit scores greater than or equal 740 and less than or equal 850 has risk tier super prime .
Interest rate is between 0 and 30 percent inclusive.
Interest rate decrease 
Approval odds is between 0 and 100 percent inclusive.
Down payment is between 0 and 50 percent inclusive.
meximum dept to incum ration is between 28 percent and 52 percent inclusive.
Allowed loan term values : ["12", "24", "36", "48", "60", "84", "12 to 24", "36 to 48", "48 to 60", "60 to 84"].
Default probability is between 0 and 100 percent inclusive.
The credit scores provided is with difference with 5 credit points.  