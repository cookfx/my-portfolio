# LaTeX Test 2

## Test A: subscript with English word, using \text{}
- $\mathcal{L}_{\text{target}}$
- $\mathcal{L}_{\text{aux}}$
- $\mathbf{e}_{\text{candidate}}$
- $\mathbf{v}_{\text{female}}$

## Test B: same but using \mathrm{}
- $\mathcal{L}_{\mathrm{target}}$
- $\mathcal{L}_{\mathrm{aux}}$
- $\mathbf{e}_{\mathrm{candidate}}$

## Test C: block math with English subscripts
$$\mathcal{L}_{\text{target}} + \alpha \cdot \mathcal{L}_{\text{aux}}$$

$$\mathbf{v}_{female}$$

## Test D: complex inline formulas from the doc
- $\mathcal{L}_\text{aux} = -\frac{1}{T-1}\sum_{t=1}^{T-1}[\log p(\mathbf{h}_{t}, \mathbf{e}_{t+1}^{+}) + \log(1-p(\mathbf{h}_{t}, \mathbf{e}_{t+1}^{-}))]$
- $\mathbf{e}_{t+1}^{+}$ is positive, $\mathbf{e}_{t+1}^{-}$ is negative
- $\mathcal{L} = \mathcal{L}_\text{target} + \alpha \cdot \mathcal{L}_\text{aux}$
