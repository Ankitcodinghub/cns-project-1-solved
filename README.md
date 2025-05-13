# cns-project-1-solved
**TO GET THIS SOLUTION VISIT:** [CNS Project 1 Solved](https://www.ankitcodinghub.com/product/cns-project-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94216&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CNS Project 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
The writing of the project report, either in LaTeX or R Markdown, should detail all the theo- retical aspects of the methods and provide all the necessary graphical displays necessary to the understanding of the particular cases.

Random variable generation

In the resolution of the following problems do not use any of the R random variable generation built-in functions, nor any R function referring to the densities of random variables.

1. Let X ∼ TruncatedPareto(α,L,H), which has probability density function αLα x−α−1

f(x)= 1−(HL)α , α,L&gt;0, H&gt;L x∈[L,H].

Fix your R random seed to 123 in the simulations.

<ol>
<li>(a) &nbsp;Analytically derive the cumulative distribution function (c.d.f.) F of X as well as its inverse F−1.</li>
<li>(b) &nbsp;Describe in detail (theory + algorithm) the inverse-transform (IT) method for gener- ating samples from continuous distributions (as is our case). Implement this method in R. Call your routine sim.IT() and let it receive as input a generic sample size m as well as generic α, L and H parameters.</li>
<li>(c) &nbsp;Use routine sim.IT() to generate a sample of size m = 10000 of X ∼ T runcatedP areto(0.5, 2, 4).
Report the first 10 simulated values. Explicitly derive and simplify the expression of the p.d.f.. Plot the sample histogram with the true p.d.f. superimposed.
</li>
<li>(d) &nbsp;Describe in detail (theory + algorithm) the acceptance-rejection (AR) method for generating samples from continuous distributions (as is our case). Identify the candi- date density function for the particular case of the X ∼ T runcatedP areto(0.5, 2, 4) and compute by hand the constants of the AR method (namely, M and the acceptance prob- ability α). Use the R function optimize() or other to confirm the result you obtained for M.
1
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
Deadline: 15/11/21

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ol start="5">
<li>(e) &nbsp;Implement the AR method in R. Call your routine sim.AR() and let it receive as input a generic sample size m as well as generic α, L and H parameters. Besides returning the simulated values of the target distribution, the sim.AR() routine should also return the simulated values that were rejected.</li>
<li>(f) &nbsp;Use routine sim.AR() to generate a sample of size m = 10000 of X ∼ T runcatedP areto(0.5, 2, 4).
Report the first 10 simulated values of the T runcatedP areto(0.5, 2, 4) and the rejection rate. Plot the sample histogram with the true p.d.f. superimposed.

Graphically display, the candidate and p.d.f. functions against the hits and misses of the AR method (as done in class – week 2) when used to simulate just m = 15 sample values.
</li>
<li>(g) &nbsp;Compare the computational times of routines sim.IT() and sim.AR() for generating a sample of size m = 50000 from the truncated Pareto distribution (you can use the R routine proc.time() as done in class – week 2).</li>
</ol>
2. Some random variables can be generated from the exponential distribution (exponential- based method), which we know how to obtain from the U(0,1) distribution. Such is the case of the random variable X ∼ Gamma(α, θ):

Fix your R random seed to 654 in the simulations. a) Implement the exponential-based method in R for generating a sample from X ∼

Gamma(α, θ), which has probability density function (p.d.f.)

</div>
</div>
<div class="layoutArea">
<div class="column">
α

If Yi ∼ Exp(1) then X = θ􏰀Yi ∼ Gamma(α,θ), α = 1,2,…

</div>
</div>
<div class="layoutArea">
<div class="column">
iid

</div>
<div class="column">
i=1

</div>
</div>
<div class="layoutArea">
<div class="column">
θ−α −x α−1

</div>
</div>
<div class="layoutArea">
<div class="column">
e θ x , α,θ &gt; 0, x ≥ 0,

</div>
</div>
<div class="layoutArea">
<div class="column">
f(x) = where Γ is the gamma function.

Call your routine sim.gam() and let it receive as input a generic sample size m and the Gamma distribution parameters α (note that here α ∈ N) and θ. Provide both algorithm and R code.

b) Use routine sim.gam() to generate a sample of size m = 10000 from X ∼ Gamma(2, 1). Plot the histogram with the pdf superimposed.

2

</div>
</div>
<div class="layoutArea">
<div class="column">
Γ(α)

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Monte Carlo methods: integration

</div>
</div>
<div class="layoutArea">
<div class="column">
In the resolution of the problems in this section you may already use the R random variable gener- ation built-in functions as well as any R function referring to the densities of random variables.

</div>
</div>
<div class="layoutArea">
<div class="column">
Let

</div>
<div class="column">
Fix your R random seed to 987 in the simulations. 􏰉1 e−x

</div>
</div>
<div class="layoutArea">
<div class="column">
I =

a) Use the R function integrate() to compute the value of I.

</div>
</div>
<div class="layoutArea">
<div class="column">
1 + x2 dx.

<ol start="2">
<li>b) &nbsp;Describe and implement in R the Monte Carlo method for estimating I (use size m = 10000).
Report an estimate of the variance of the Monte Carlo estimator IˆMC of I.
</li>
<li>c) &nbsp;Describe and implement in R the Monte Carlo methods of based on antithetic variables, control variables and importance sampling for estimating I (size m = 10000). Report an estimate of the variance of all the Monte Carlo estimators Iˆant, Iˆcont and Iˆis of I.</li>
<li>d) &nbsp;What’s the percentage of variance reduction that is achieved when using those MC estimators instead of IˆMC?</li>
</ol>
Monte Carlo methods: confidence intervals

In the resolution of the problems in this section you may already use the R random variable gener- ation built-in functions as well as any R function referring to the densities of random variables.

Fix your R random seed to 569 in all simulations. 4. Assume X ∼ N(μ,σ2) with μ unknown and σ2 known. Let X1,…,Xn be a random sample

</div>
</div>
<div class="layoutArea">
<div class="column">
of population X. One has that the random interval given by 􏰇 ̄σ ̄σ􏰈

</div>
</div>
<div class="layoutArea">
<div class="column">
X−z1−α2 √n,X+z1−α2 √n ,

is a (1 − α) × 100% confidence interval (CI) for μ regardless of sample size n.

</div>
</div>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
<div class="layoutArea">
<div class="column">
In this exercise, one wishes to assess how a certain type of data contamination affects the coverage probability of a 95% CI for μ, given a random sample of a population X ∼ N (μ, 1) of size n = 20, via a Monte Carlo simulation study (with m = 10000 simulations). For that purpose, consider that 90% of those n observations are drawn from a X ∼ N(0,1) distribution and that the remaining 10% are drawn from the contaminated normal distribution X ∼ N (k, 1) with k = 1, 5, 9. The bad data points generated in this way are called shift outliers because the bad data points are shifted from μ = 0 in k standard deviations.

Present a thorough discussion of your results. How harmful can this type of contamination be in terms of the level of confidence of a CI? Would your results still hold for other levels of confidence other than 95%?

3

</div>
</div>
</div>
