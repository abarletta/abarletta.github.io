***
## About myself
My name is Andrea Barletta and I work as postdoctoral researcher in Quantitative Finance at Aarhus BSS, Denmark. 
In this page I share some MATLAB codes that I have developed for my research.

- [My webpage at Aarhus BSS](http://pure.au.dk/portal/en/persons/id(e161f76b-35b6-4903-b768-e8b172cbede5).html)
- [My SSRN profile](https://papers.ssrn.com/sol3/cf_dev/AbsByAuth.cfm?per_id=2059845)

***
### <b>rndfittool</b> - _Risk-neutral Density Fitting Tool_
The _Risk-neutral Density Fitting Tool_ tool (rndfittool) allows the user to infer the risk-neutral density (RND), the risk-neutral moments and the greeks embedded in a set of observed call and put option prices. The underlying  methodology is fully non-structural, meaning that it does not rely on any parametric model, and it consists in approximating the RND through orthogonal polynomial expansions. A detailed description of this methodology is provided in <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2943964">this paper</a>.

#### Latest downloads (updated 2017-11-15)
- [MATLAB App installer v17.10 (recommended)](https://github.com/abarletta/rndfittool/releases/download/v17.10/RND.Fitting.Tool.v17.10.mlappinstall)
- [Zip archive containing all codes v17.10](https://github.com/abarletta/rndfittool/releases/download/v17.10/RND.Fitting.Tool.v17.10.zip)

<b> [See more](https://abarletta.github.io/rndfittool/) </b>

***
### <b>viximpv</b> - _VIX Implied Volatility Toolbox_

This toolbox computes approximate values of the Black & Scholes implied volatility of VIX options using the perturbative technique described in <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2942262">this paper</a>. The modelling setup requires that the VIX index dynamics is explicitly computable as a smooth transformation of a purely diffusive, one-dimensional Markov process Y. Specifically:

#### Latest downloads (updated 2017-11-23)

- [MATLAB Toolbox installer (recommended)](https://github.com/abarletta/viximpv/releases/download/17.11/VIX.Implied.Volatility.mltbx)
- [Zip archive containing all codes](https://github.com/abarletta/viximpv/releases/download/17.11/VIX.Implied.Volatility.zip)

<b> [See more](https://abarletta.github.io/viximpv/) </b>
