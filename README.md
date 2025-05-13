# stat4ds-homework-3-solved
**TO GET THIS SOLUTION VISIT:** [Stat4DS Homework 3 Solved](https://www.ankitcodinghub.com/product/stat4ds-homework-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93912&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Stat4DS Homework 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Who let the DAGs out?

Remember DAGs? Good. It’s now time to learn-how-to-learn their topology (at least in the Gaussian case) and then put them to work in a biological setup.

Our statistical recipe needs a lot of ingredients, namely:

1. The basics of the Likelihood Ratio Test (lrt) method.

2. The concept and ideas behind Universal Inference.

3. The notion of Gaussian DAGs and their (constrained) likelihood functions 4. The incarnation of lrt for testing directed connections in Gaussian DAGs

…I guess, we better start…

Ingredient (A): The Likelihood Ratio Test

The Wald test is useful for testing a scalar parameter. The Likelihood Ratio Test (lrt) is more general and can be used for testing a vector–valued parameter. More specifically:

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
The Likelihood Ratio Test

Within a parametric model F = {fθ(·) : θ ∈ Θ ⊆ Rp}, consider testing H0:θ∈Θ0 vs H1:θ∈/Θ0

Given an iid sample Dn = {X1, . . . , Xn} ∼ fθ(·) with the associated likelihood function L(θ | Dn) = 􏱀i fθ(Xi), the likelihood ratio test rejects the null if Un &gt; c for some suitable critical level c, with

Un = supθ∈Θ L(θ|Dn) = L(θ􏰸|Dn) , supθ∈Θ0 L(θ|Dn) L(θ􏰸0|Dn)

where θ􏰸0 denotes the constrained to Θ0 mle (i.e. assuming H0 is true), whereas θ􏰸 denotes the unconstrained mle.

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Remarks:

<ul>
<li>Replacing Θc0 with Θ in the denominator has little effect on the test statistic and the unconstrained version simplifies the theoretical properties of the test statistics.</li>
<li>The likelihood ratio test is most useful when Θ0 consists of all parameter values θ such that some coordinates of θ are fixed at particular values.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Let’s now look at a famous example on testing for the mean of a Normal population: one of the few cases where we have exact, finite sample, results.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Example: Student’s t–test Let Dn = {X1,…,Xn} be iid from a N(μ,σ2) and we want to test

H0 :μ=μ0 vs H1 :μ̸=μ0 􏰺 Un = L(μ􏰸,σ􏰸|Dn) , L(μ0, σ􏰸0 | Dn)

where σ􏰸0 maximizes the likelihood under the null, that is, subject to μ = μ0.

After some simple but tedious algebra, it can be shown that Un &gt; c ⇔ Tn &gt; c′ where

X ̄n−μ0underH0 2 1􏰷 ̄2

So the final two–sided test on the mean μ of a Normal population is:

Reject H0 if |Tn| &gt; tn−1,α/2 (Student’s t–test).

</div>
</div>
<div class="layoutArea">
<div class="column">
Tn= σ􏰸/√n ∼ tn−1 with σ􏰸 =n

</div>
<div class="column">
(Xi−Xn).

</div>
</div>
<div class="layoutArea">
<div class="column">
i

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Similarly to the Wald test, in more general situations where we are dealing with non-Gaussian (but still regular!) populations, all we can do to appropriately tune the critical value c in order to control the type-I error probability of our lrt, is to appeal to some suitable, broadly applicable, asymptotic result.

More specifically, here’s two classics:

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Asymptotic approximation / scalar

ConsidertestingH0 :θ=θ0 versusH1 :θ̸=θ0 whereθ∈R.

Then, under H0 (+ regularity conditions on the population model F),

d2 Tn =2logUn −→χ1.

Hence an asymptotic level α test is: Reject H0 when Tn &gt; χ21,α.

Asymptotic approximation / vector

Consider testing a null H0 : θ ∈ Θ0 ⊆ Rp where we are fixing some parameters. Then, under H0 (+ regularity conditions on the population model F),

d2

Tn = 2logUn −→ χν where ν = dim(Θ)−dim(Θ0).

Hence an asymptotic level α test is: Reject H0 when Tn &gt; χ2ν,α.

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Ingredient (B): Universal Inference

As we all should know at this point, in classical frequentist statistics, confidence sets and tests are often obtained by starting from asymptotically Gaussian estimators or other large sample results.

As a consequence, their validity relies on large sample asymptotic theory and requires that the statistical model satisfy certain regularity conditions. When these conditions do not hold, or the sample is not large “enough”, there is no general method for statistical inference, and these settings are typically considered in an ad-hoc manner.

Recently a new, universal method simply based on sample splitting has been introduced which yields tests and confidence sets for any statistical model (regular or not) and comes also with finite-sample guarantees.

Focusing on hypothesis testing, historically speaking sample splitting was first analysed computationally and theoretically in a 1975-4-pages-long paper by sir David Cox, one of the greatest statisticians of all times, and then further discussed in his 1977 review (2, Section 3.2), where he describes the method as well known and refers to an American Statistician paper with a wide-ranging discussion of “snooping”, “fishing”, and “hunting” in data analysis.

Honestly? An easy read way more relevant now than then! Let’s now describe this idea in the context of lrt:

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
Universal Hypothesis Test

Let D2n = {X1,…,X2n} be an iid sample from a population model F having density fθ(·) and consider testing H0:θ∈Θ0 vs H1:θ∈/Θ0.

To this end, (randomly) split the data D2n in two groups having the same size n (just to simplify the notation), and build the two corresponding likelihood functions:

D 􏰺􏰲DTr,DTe􏰳􏰺􏱂L(θ|DTr)=􏱀 Tr f (X), L(θ|DTe)=􏱀 Te f (X)􏱃 2n n n n i∈Dn θ i n i∈Dn θ i

Consider now the following two mle’s for θ

Tr Tr Te Te

</div>
</div>
<div class="layoutArea">
<div class="column">
swap

</div>
<div class="column">
Tr

</div>
</div>
<div class="layoutArea">
<div class="column">
θ􏰸0=argmaxL(θ|Dn ) θ∈Θ0

</div>
<div class="column">
θ􏰸 =argmaxL(θ|Dn ) All θ

</div>
</div>
<div class="layoutArea">
<div class="column">
H0-constrained estimator based on the Training Data

At this point we are ready to define the following two universal test statistics:

􏰮Te 􏰯

L θ􏰸 |DTr U +Uswap

</div>
</div>
<div class="layoutArea">
<div class="column">
n􏰮Tr􏰯 n L θ􏰸 |DTr

</div>
</div>
<div class="layoutArea">
<div class="column">
Unconstrained estimator based on the Test Data

</div>
</div>
<div class="layoutArea">
<div class="column">
U= n and W=n n (1)

</div>
</div>
<div class="layoutArea">
<div class="column">
2

Cross-Fit Likelihood Ratio

Te

Split LRT Cross-Fit LRT

By simply using Markov inequality and under no assumptions on the population model F, in Theorem 3 the Authors show that in finite sample the Split and Cross-Fit LRTs control the type-I error probability at level α.

</div>
</div>
<div class="layoutArea">
<div class="column">
0n Split Likelihood Ratio

</div>
</div>
<div class="layoutArea">
<div class="column">
and Dn .

Based on Un and Wn, we get the following two univeral testing procedures:

</div>
</div>
<div class="layoutArea">
<div class="column">
where Un

</div>
<div class="column">
is the same as Un after swapping the roles of Dn

RejectH0 ifUn&gt;α1, and RejectH0 ifWn&gt;α1 (2)

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Ingredient (C): Gaussian DAGs and their (constrained) Likelihood

We (should) know that we use DAG models to encode the joint distribution f(x) of a random vector X = [X1, . . . , Xp]T ∈ Rp: the nodes and the directed edges represent, respectively, the variables and the parent-child dependence relations between any two variables. We also know that the joint f(x) is Markov w.r.t. a graph G if it admits the following factorization

p

f (x) = 􏱁 f 􏰮xj | pa(xj )􏰯,

j=1

where pa(xj) denotes the set of variables with an arrow towards Xj in the (directed) graph G.

Our main goal here, is to lay down a strategy to infer the pairwise relation imposed by the (local) Markov dependence. To get started, first of all we restrict the scope of our analysis focusing on a Gaussian random vector X ∼ Np.

Under this assumption, we can capture the directional effects induced by directed edges by using a linear structural equation model1

􏰷 iid2

Xj = A[j,k]·Xk +εj where εj ∼ N1(0,σ ), (3)

k:k̸=j

and A is a (p × p) adjacency matrix in which a nonzero entry A[j, k] in position (j, k) corresponds to a directed edge from

parent node k to child node j, with its value indicating the strength of the relation; A[j,k] = 0 when k ̸∈ pa(Xj).

Denoting by θ = (A, σ2) the parameters of our model, to approach the problem from a maximum likelihood perspective, we need to write down:

1. The (log-)likelihood function ln(θ) = ln L(θ | Dn).

2. How to introduce acyclicity constraints to drive the learning process.

1The homoscedasticity of the error {εj}j is not required but useful to induce identifiability and avoid technicalities regarding equivalence classes. In addition, individual means μj could be incorporated by adding intercepts to Equation 3. For simplicity, in what follows we set the means to zero.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Learning Goal

iid Tp

Given a random sample Dn = {X1,…,Xn} ∼ f(·), where Xi = [Xi,1,…,Xi,p] ∈ R , infer the adjacency matrix A subject

to the requirements that A defines a directed acyclic graph.

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
By collecting all the available data in an (n × p) matrix X = [x1 · · · xi · · · xn]T, and because of the Gaussian nature of the structural equation model in Equation 3, the log-likelihood is readily available:

</div>
</div>
<div class="layoutArea">
<div class="column">
p􏰾n 􏰿

ln(A, σ2) = − 􏰷 1 􏰷 􏰴X[i, j] − 􏰶 A[j, k] · X[j, k]􏰵2 + n ln σ2 . (4)

</div>
</div>
<div class="layoutArea">
<div class="column">
2σ2 k:k̸=j 2 j=1 i=1

</div>
</div>
<div class="layoutArea">
<div class="column">
The acyclicity constraints are all but trivial. Fortunately, the hard work has already been done by Yuan et al. in 20192. Based on their Theorem 1, we know that A satisfies the acyclicity constraints if and only if there exist a (p × p) matrix Λ s.t.:

Λ[r,k]+1(j̸=k)−Λ[j,k]􏰻1􏰮A[r,j]̸=0􏰯 forall r,j,k∈{1,…,p}andr̸=j. (5) where 1(·) denotes the indicator function. Although the matrix Λ may not be unique, Equation 5 has three clear pros:

<ol>
<li>It reduces the original super-exponentially many constraints on A to p3 − p2 active constraints on (A, Λ).</li>
<li>Code acyclicity in a simple way: each constraint involves only one parameter in A and is linear in Λ[j, k] and 1􏰮A[r, j] ̸= 0􏰯.</li>
<li>The non-convexity of the constraints in Equation 5 due to the presence of the indicator 1􏰮z ̸= 0􏰯 can be easily handled by replacing it with its computational surrogate: the truncated L1-function: Jτ (z) = min(|z|/τ, 1), a piecewise linear function that converges to the indicator as τ ↓ 0. This yields the following approximated set of acyciclity constraints:
Λ[r,k]+1(j̸=k)−Λ[j,k]􏰻Jτ􏰮A[r,j]􏰯 forall r,j,k∈{1,…,p}andr̸=j. (6)
</li>
</ol>
Now, before putting everything together in a test statistics, one last addition is the introduction of a sparsity/complexity

constraint on A, very useful to handle high-dimensional setups where p &gt;&gt; n:

􏰷 1􏰮A[r,j]̸=0􏰯􏰼κ 􏱄 􏰷 Jτ􏰮A[r,j]􏰯􏰼κ (7)

r,j : r̸=j r,j : r̸=j

Here κ &gt; 0 is a tuning parameter to be selected possibly via a suitable grid-search.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Learning Problem

Squeezing together Equations 4, Equation 6 and Equation 7, the directed acyclic graph learning problem can be

reformulated from a constrained maximum likelihood perspective as follow 􏰮2􏰯 2

</div>
</div>
<div class="layoutArea">
<div class="column">
subject to

</div>
<div class="column">
􏰷 Jτ 􏰮A[r, j]􏰯 􏰼 κ (8) r,j : r̸=j

Λ[r,k]+1(j̸=k)−Λ[j,k]􏰻Jτ􏰮A[r,j]􏰯 forall r,j,k∈{1,…,p}andr̸=j

</div>
</div>
<div class="layoutArea">
<div class="column">
A􏰸,σ􏰸 =argmaxln(A,σ) (A,σ2 ,Λ)

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Ingredient (D): Constrained Likelihood Ratio Test

Now that we know how to fit our Gaussian model enforcing acyclicity (and sparsity!), we are finally in position to build some dedicated lrt to check the presence of some specific directed connection of interest. Along the lines of Li et al. (2019)3, we have two possible types of tests concerning directional pairwise relations, encoded by an adjacency matrix A. More specifically:

1. Test of Graph Linkages

Let F be an index set where an index (j, k) ∈ F represents a directed connection. We are interested in testing:

</div>
</div>
<div class="layoutArea">
<div class="column">
H0 :A[j,k]=0forall(j,k)∈F vs H1 :not H0

􏰸2 􏰸2

</div>
</div>
<div class="layoutArea">
<div class="column">
where (A,σ􏰸 ) are the unconstrained mles solving the optimization problem in Equation 8, whereas (A0,σ􏰸0) are the H0-constrained mles solving the following H0-augmented optimization problem

</div>
</div>
<div class="layoutArea">
<div class="column">
subject to

</div>
<div class="column">
􏰮2􏰯 2 A􏰸,σ􏰸 =argmaxln(A,σ)

(A,σ2 ,Λ)

A[F ] = 0

􏰶r,j : r̸=j Jτ 􏰮A[r, j]􏰯 􏰼 κ (10) Λ[r,k]+1(j̸=k)−Λ[j,k]􏰻Jτ􏰮A[r,j]􏰯 forall r,j,k∈{1,…,p}andr̸=j

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰮􏰸 2􏰽􏰽 􏰯 LA,σ􏰸 Dn

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰺 Un = 􏰮 􏰽 􏰯 (9) 􏰸2􏰽

</div>
</div>
<div class="layoutArea">
<div class="column">
LA0,σ􏰸0 Dn Constrained Likelihood Ratio Statistics

</div>
</div>
<div class="layoutArea">
<div class="column">
2An implementation of their method is available at: https://github.com/ciryiping/TLPDAG.

3An implementation of their method is available at: https://github.com/chunlinli/clrdag. Notice that our sparsity parameter κ is mu in the main function MLEdag(). To install this package on OSX, you need to “brew” gcc and then make it visible to R. Please read this and/or contact us.

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
2. Test of Directed Pathway

A directed pathway is specified by an index set F of size |F| where a common segment is shared by any two consecutive indices, like F = 􏰲(j1, j2), (j2, j3), . . . , (j|F |−1, j|F |)􏰳. We are interested in testing:

H0 :A[j,k]=0forsome(j,k)∈F vs H1 :A[j,k]̸=0forall(j,k)∈F 􏰺 Un = |F| 􏰮 􏰽 􏰯 (11) 􏰸2􏰽

</div>
</div>
<div class="layoutArea">
<div class="column">
A􏰸,σ􏰸 =argmaxln(A,σ) (A,σ2 ,Λ)

</div>
</div>
<div class="layoutArea">
<div class="column">
subject to A[jk, jk+1] = 0 for (jk, jk+1) ∈ F (12) 􏰶r,j : r̸=j Jτ 􏰮A[r, j]􏰯 􏰼 κ

Λ[r,k]+1(j̸=k)−Λ[j,k]􏰻Jτ􏰮A[r,j]􏰯 forall r,j,k∈{1,…,p}andr̸=j

The Data: Cell Signalling

We will use all the machinery above to dig the multivariate flow cytometry data in Sachs et al. (2005). Suppose we are studying the human immune system, in particular the so called T helper cells. To properly understand their normal responses under some specific extracellular stimuli, we can perturb them with a series of chemical stimulatory/inhibitory interventions and then profile the effects of each condition by measuring the expression of relevant proteins and lipids via flow cytometry.

The data collection process is described in Figure 1:

1. each cell is treated as an independent observation;

2. 9 different perturbations were applied to sets of individual cells, namely: cd3cd28, cd3cd28icam2, cd3cd28+aktinhib, cd3cd28+g0076, cd3cd28+psitect, cd3cd28+u0126, cd3cd28+ly, pma, b2camp. The known biological effects of the perturbations employed are described in Table 1 of Sachs et al. (2005);

3. On each cell in each condition, a multiparameter flow cytometer simultaneously records the levels of 11 proteins and lipids, namely: praf, pmek, plcg, PIP2, PIP3, p44/42, pakts473, PKA, PKC, P38, and pjnk. This simultaneous measurements allow researchers to infer causal influences in cellular signalling.

Figure 1: Source: Sachs et al. (2005)

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰮􏰸 2􏰽􏰽 􏰯 LA,σ􏰸 Dn

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰸2 􏰸2

where (A,σ􏰸 ) are the unconstrained mles solving the optimization problem in Equation 8, whereas (A0,k,σ􏰸0,k) are the

H0 -constrained mles solving, for each k ∈ {1, . . . , |F |}, the following H0 -augmented optimization problem: 􏰮2􏰯 2

</div>
</div>
<div class="layoutArea">
<div class="column">
maxk=1L A0,k,σ􏰸0,k Dn Constrained Likelihood Ratio Statistics

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Your Main Goal

Despite the fact that the Authors of the original papers derived and implemented in MLEdag() the χ2-asymptotics for the Likelihood Ratio statistics under both testing scenarios, your goal here is to push the finite-sample envelope and adapt the two universal procedures of Equation 2 to the current framework.

You will be using MLEdag() to get the mles you need and also to compare the results you get 􏰺 install that package!

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
The Exercise: ToDo List

1. Read (really) these notes, and install the clrdag package directly from git:

Notice that our sparsity parameter κ is mu in the main function MLEdag(). To install this package on OSX, you need to “brew” gcc and then make it visible to R. Please read this and/or contact us.

<ol start="2">
<li>By using the MLEdag() function to get constrained and unconstrained mles, adapt and implement in R at least one of the universal tests in Equation 2 to the problem of testing for graph linkages and directed pathway.</li>
<li>Starting from the code in the examples folder of the clrdag package and trying to find some inspiration from Example 1 and Example 2 in Section 5.1 of Li et al., design and run a decent simulation study to check size and power of your
universal test(s) for linkage.
</li>
</ol>
Let’s now move to cell signalling and flow cytometry. By stacking together the data coming from all 9 interventions, Sachs et al. (2005) estimated the DAG in Figure 2 via a data-discretization technique. The edges were categorized as: (i) expected, for connections well-established in the literature that have been demonstrated under numerous conditions in multiple model systems; (ii) reported, for connections that are not well known, but for which we were able to find at least one literature citation; and (iii) missing, which indicates an expected connection that their network failed to find. Of the 17 arcs in their model, 15 were expected, all 17 were either expected or reported, and 3 were missed

Figure 2: Source: Sachs et al. (2005)

<ol start="4">
<li>Looking at the estimated DAG in Figure 2, formalize at least 3 linkage-type hypotheses and 1 pathway-type hypothesis
that you feel it may be interesting to double-check with your own toolkit. Briefly explain why you find them interesting.
</li>
<li>Select one specific intervention out of the 9 available and, based on those data only, test your set of hypotheses using both, your universal procedures and the asymptotics implemented in the MLEdag() function.

Compare the results also as you let the sparsity parameter κ vary.

Achtung! Achtung!

Before running any test, keep in mind we are working under the assumption that the data are zero-mean Gaussian! Use basic tools like boxplot(), hist(), density(), qqplot(), pairs(), to visually check what’s going on with each of your 11 variables, and possibly apply suitable transformations like scale() and MASS::boxcox() to “enforce” it.
</li>
<li>Repeat the previous analysis augmenting the data by stacking together those coming from different conditions. Despite their heterogeneity, ideally we would like to pull together all the data available as Sachs et al. (2005) did. Nevertheless, if you find handling the “über-dataset” computationally infeasible, simply keep stacking data till you can. Compare the results with those in 5. and draw some conclusions. Do you think we need to adjust for multiplicity here? Explain.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>install.packages(devtools)
devtools::install_github("chunlinli/clrdag/pkg/clrdag")
</pre>
</div>
</div>
</div>
