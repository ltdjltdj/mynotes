# mynotes
- \( R_{\text{target}} \)：目标样的R值
- \( C_i \)：第i种染料的浓度
- \( P_i \)：第i种染料的单位克重价格
- \( \text{Cost} \)：染料的总成本
- \( N \)：在配方中使用的染料数量

\[
\text{minimize} \: \Delta E + \lambda \times \text{Cost} + \gamma \times N
\]

其中，\(\Delta E\) 是与目标样之间的色差，\(\text{Cost} = \sum_i C_i \times P_i \times 2 \) (因为是2kg材料)，\( N \) 是非零浓度的染料数量。  
\(\lambda\) 和 \(\gamma\) 是权重系数，用于平衡色差、成本和染料数量之间的重要性。
