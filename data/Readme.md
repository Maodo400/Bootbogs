
- `B{step}`: Indicates the bootstrap step number (e.g., `B1` = first bootstrap iteration).
- `METRIC`: The evaluation metric used for the model:
  - `R` = Root Mean Squared Error (RMSE)
  - `S`  = S-Score
- `LRA` or `LRNA`: Refers to how the learning rate is handled:
  - `A` = **Rounded** learning rate
  - `NA` = **Non-rounded** learning rate
- `{nb_epoch}`: Number of training epochs (e.g., `10`, `20`, etc.)

---

## Examples

### `B1RLRNA10`
- **B1**: First bootstrap step  
- **R**: Metric used: RMSE  
- **LRNA**: Learning rate not rounded  
- **10**: Trained for 10 epochs

### `B1SLRA10`
- **B1**: First bootstrap step  
- **S**: Metric used: S-Score  
- **LRA**: Learning rate rounded  
- **10**: Trained for 10 epochs


