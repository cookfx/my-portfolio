# LaTeX Test

## Test 1: Inline subscript with braces
- $\mathbf{e}_{1}$ vs $\mathbf{e}_1$
- $\mathbf{h}_{t}$ vs $\mathbf{h}_t$
- $k_{1}$ vs $k_1$
- $n_{q}$ vs $n_q$

## Test 2: Inline superscript with braces
- $x^{(0)}$ vs $x^(0)$
- $y^{(t+1)}$ vs single

## Test 3: Complex inline
- $\mathcal{L}_{aux}$
- $\mathbf{e}_{t+1}^{+}$
- $\mathcal{L}_{target} + \alpha \cdot \mathcal{L}_{aux}$

## Test 4: Block math (should work fine)
$$\mathbf{e}_{1}, \mathbf{e}_{2}, \ldots, \mathbf{e}_{T}$$

$$\mathcal{L}_{aux} = -\frac{1}{T-1}\sum_{t=1}^{T-1}$$
