1.Sample Space

For the experiment of flipping a coin, and for each one of the following choices, determine whether we have a legitimate sample space:

Ω={Heads and it is raining, Heads and it is not raining, Tails}

Yes

Ω={Heads and it is raining, Tails and it is not raining, Tails}

No

2. Tree Presentations

Paul checks the weather forecast. If the forecast is good, Paul will go out for a walk. If the forecast is bad, then Paul will either stay home or go out. If he goes out, he might either remember or forget his umbrella. In the tree diagram below, identify the leaf that corresponds to the event that the forecast is bad and Paul stays home.
A tree diagram in which the left most node splits into two nodes on its right. The top node on the right is labelled 1 and the bottom node on the right further splits into two nodes even further to the right. The top of these two nodes is labeled 2 and the bottom one is again split into two nodes again further to the right, with the one on top labelled 3 and the one on the bottom labelled 4.

2

3. Axioms

Let A and B be events on the same sample space, with P(A)=0.6 and P(B)=0.7. Can these two events be disjoint?

No

4. Simple Properties

Let A, B, and C be disjoint subsets of the sample space. For each one of the following statements, determine whether it is true or false. Note: "False" means "not guaranteed to be true."

a) P(A)+P(Ac)+P(B)=P(A∪Ac∪B)

False

b) P(A)+P(B)≤1

True

c) P(Ac)+P(B)≤1

False

d) P(A∪B∪C)≥P(A∪B)

True

5. More Properties

Let A, B, and C be subsets of the sample space, not necessarily disjoint. For each one of the following statements, determine whether it is true or false. Note: “False" means “not guaranteed to be true."

a) P((A∩B)∪(C∩Ac))≤P(A∪B∪C)

True

b) P(A∪B∪C)=P(A∩Cc)+P(C)+P(B∩Ac∩Cc)

True

6. Discrete Probability Calculations

Consider the same model of two rolls of a tetrahedral die, with all 16 outcomes equally likely. Find the probability of the following events:

a) The value in the first roll is strictly larger than the value in the second roll.

3/8
 
b) The sum of the values obtained in the two rolls is an even number.

1/2
 
7.Continuous Probability Calculations

Consider a sample space that is the rectangular region [0,1]×[0,2], i.e., the set of all pairs (x,y) that satisfy 0≤x≤1 and 0≤y≤2. Consider a “uniform" probability law, under which the probability of an event is half of the area of the event. Find the probability of the following events:

a) The two components x and y have the same values.

0
 
b) The value, x, of the first component is larger than or equal to the value, y, of the second component.

1/4
  
c) The value of x2 is larger than or equal to the value of y.

1/6

8. Using countable additivity

Let the sample space be the set of positive integers and suppose that P(n)=1/2n, for n=1,2,…. Find the probability of the set {3,6,9,…}, that is, of the set of of positive integers that are multiples of 3.

1/7

9. Uniform probabilities on the integers

Let the sample space be the set of all positive integers. Is it possible to have a “uniform" probability law, that is, a probability law that assigns the same probability c to each positive integer?

No

Explanation: Suppose that c=0. Then, by countable additivity,

1=P(Ω)=P({1}∪{2}∪{3}⋯)=P({1})+P({2})+P({3})+⋯=0+0+0+⋯=0,
 
which is a contradiction.

Suppose that c>0. Then, there exists an integer k such that kc>1. By additivity,

P({1,2,…,k})=kc>1,
 
which contradicts the normalization axiom.

10. On countable additivity

Let the sample space be the two-dimensional plane. For any real number x, let Ax be the subset of the plane that consists of all points of the vertical line through the point (x,0), i.e., Ax={(x,y):y∈Re}.

a) Do the axioms of probability theory imply that the probability of the union of the sets Ax (which is the whole plane) is equal to the sum of the probabilities P(Ax)?

No
 
b) Do the axioms of probability theory imply that

P(A1∪A2∪⋯)=∑x=1∞P(Ax)?
 
(In other words, we consider only those lines for which the x coordinate is a positive integer.)

Yes
 
 Explanation:
 
 a) The collection of sets Ax is not countable because the set of real numbers is not countable (i.e., cannot be arranged in a sequence), and so the additivity axiom does not apply.

b) The countable additivity axiom applies because we are dealing with a sequence (in particular, a countable collection) of disjoint events.
 
 

 
