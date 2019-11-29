# Naive Bayes Theorum : - 

If E1, E2 , ...., En are mutually exclusive and exhaustive events such that P(Ei) > 0 for each i and A is an arbitrary event 
for which P(A) is not equal to 0 , then conditional probability of occurnce of Ei, given that A has already occured will be 

        P(Ei/A) =                           P(Ei) * P(A/Ei)
                    -------------------------------------------------------------------------------------
                     P(E1)*P(A/E1) + P(E2)*P(A/E2)------------------------- + P(Ei)*P(A/Ei)


where denominator represents the total probability of occuring an event A while E has occured when the total sample space is divided into multiple events Ei and 

numerator represents probability of occuring a specific event from the total events while A has already occured. 

lets understand it with the example :- 

Bag A contains 3 red and 4 white balls and bag B contains 4 red and 3 white balls. A red ball is drawn from the bag from the bag. Find out the probability that it is drawn from bag A.

Probability of choosing a bag will be -

                P(E1) = P(E2) = 1/2 (as there are two bags and choosing one among them will be 1/2)
                
Probability of choosing a red ball will be - 

                P(R) = choosing red ball from bag A + choosing red ball from bag B  ---------- eq 1
                
probability of choosing red ball  from bag A = 1/2 * 3/7
                                                (as there are two bags , so we also need to choose bag A whose probability is 1/2)
                                                
probability of choosing red ball from bag B = 1/2 * 4*7


so, total probability of choosing a red ball will be  =  1/2*3/7  + 1/2*4/7

probability of choosing red ball from bag A will be - 

                                        1/2 * 3/7
                             ---------------------------------------------
                                        1/2 *3/7  + 1/2 * 4/7
                                        
                                        
                             =    3/7
       
