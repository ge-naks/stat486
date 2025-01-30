# Stat486 - Applied Statistical learning

What does "understand data statistically and scientifically" mean?
- We want to know both what the data says and what it does not say
- The focus of statistics is on both extracting signal from datam adn modeling and minimizing the noise or uncertainty in data
- recall from hypothesis testng in Stat I and II:
- Type I eerror: Beleiving the alternative hypothesis when the null hypothesis is true (false positive)
- Type II error: Beleiving the null hypothesis when the alternative is true (False negative)
- Type III error: Answerin the wrong quetsion

- Null vs alternative hypothesis
- NULL, the hypothesis to disprove
- How does this work
    - Quality assurance: your job is to ensue your customer never gets out of spec products
        - You set up a test which gives ytou a fixed probability of rejecting the test if it is wrong. (this is your alpha)
        - Given this test you can calculate the probability under a specific alternative 
        that the test rejects when it should (like sensitivity in medicine, only here it is
        called the power of the test).
        - Medicine: Your job is to try to find better drugs. The null hypothesis is
        that the new drug is the same (or worse) than the current drug.

### Types of errors
– Type I error rejecting the null hypothesis when it is true
– Type II error not rejecting the null hypothesis when it is false
– Type III error answering the wrong question

### What is Type III Error
- Building a very precise model based on the wrong question
- For example:
    - Challenger space shuttle - to launch or not to launch at below freezing temperature


### Survival Curve
- The survival function or curve is defined as S(t) = Pr(T > t)
- A decreasing function quantifies the probability of surviving past time t
- For example, suppose that a company is interested in modeling customer churn. Let T represent the time that a customer cancels a subscription to the company's service
- Then S(t) represents the probability that a customer cancels later than time t.