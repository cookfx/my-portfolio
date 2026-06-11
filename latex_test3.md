# LaTeX Test 3 - Comprehensive

## Test 1: Simple inline (should work per GitHub docs)
- $\mathbf{e}_{1}$
- $\mathbf{h}_{t}$
- $k_{1}$
- $n_{q}$

## Test 2: Inline with English word subscripts (known issue)
- $\mathcal{L}_{aux}$
- $\mathcal{L}_{target}$
- $\mathbf{e}_{candidate}$
- $\mathbf{v}_{female}$

## Test 3: Same but using backtick syntax $`...`$
- $`\mathcal{L}_{aux}`$
- $`\mathcal{L}_{target}`$
- $`\mathbf{e}_{candidate}`$
- $`\mathbf{v}_{female}`$

## Test 4: Same but with \text{} inside backtick syntax
- $`\mathcal{L}_{\text{aux}}`$
- $`\mathcal{L}_{\text{target}}`$
- $`\mathbf{e}_{\text{candidate}}`$
- $`\mathbf{v}_{\text{female}}`$

## Test 5: Block math with English subscripts
$$\mathcal{L}_{target} + \alpha \cdot \mathcal{L}_{aux}$$

$$\mathcal{L}_{\text{target}} + \alpha \cdot \mathcal{L}_{\text{aux}}$$

## Test 6: Complex inline formulas - original format
- $\mathcal{L}_{aux} = -\frac{1}{T-1}\sum_{t=1}^{T-1}[\log p(\mathbf{h}_{t}, \mathbf{e}_{t+1}^{+}) + \log(1-p(\mathbf{h}_{t}, \mathbf{e}_{t+1}^{-}))]$
- $\mathbf{e}_{t+1}^{+}$ is positive, $\mathbf{e}_{t+1}^{-}$ is negative
- $\mathcal{L} = \mathcal{L}_{target} + \alpha \cdot \mathcal{L}_{aux}$

## Test 7: Complex inline formulas - backtick syntax
- $`\mathcal{L}_{aux} = -\frac{1}{T-1}\sum_{t=1}^{T-1}[\log p(\mathbf{h}_{t}, \mathbf{e}_{t+1}^{+}) + \log(1-p(\mathbf{h}_{t}, \mathbf{e}_{t+1}^{-}))]`$
- $`\mathbf{e}_{t+1}^{+}`$ is positive, $`\mathbf{e}_{t+1}^{-}`$ is negative
- $`\mathcal{L} = \mathcal{L}_{target} + \alpha \cdot \mathcal{L}_{aux}`$

## Test 8: Complex inline with text subscript - backtick syntax
- $`\mathcal{L}_{\text{aux}} = -\frac{1}{T-1}\sum_{t=1}^{T-1}[\log p(\mathbf{h}_{t}, \mathbf{e}_{t+1}^{+}) + \log(1-p(\mathbf{h}_{t}, \mathbf{e}_{t+1}^{-}))]`$
- $`\mathbf{e}_{t+1}^{+}`$ is positive, $`\mathbf{e}_{t+1}^{-}`$ is negative
- $`\mathcal{L} = \mathcal{L}_{\text{target}} + \alpha \cdot \mathcal{L}_{\text{aux}}`$

## Test 9: FFM-style formulas
- $\langle \mathbf{v}_{i,f_j}, \mathbf{v}_{j,f_i} \rangle$
- $`\langle \mathbf{v}_{i,f_j}, \mathbf{v}_{j,f_i} \rangle`$

## Test 10: DIN/DIEN attention formulas
- $a_i = \text{MLP}_{attention}([\mathbf{e}_i; \mathbf{e}_{candidate}; \mathbf{e}_i - \mathbf{e}_{candidate}; \mathbf{e}_i \odot \mathbf{e}_{candidate}])$
- $`a_i = \text{MLP}_{attention}([\mathbf{e}_i; \mathbf{e}_{candidate}; \mathbf{e}_i - \mathbf{e}_{candidate}; \mathbf{e}_i \odot \mathbf{e}_{candidate}])`$
