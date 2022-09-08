# Evostra Algorithms

[_Documentation generated by Documatic_](https://www.documatic.com)

<!---Documatic-section-Codebase Structure-start--->
## Codebase Structure

<!---Documatic-block-system_architecture-start--->
```mermaid
None
```
<!---Documatic-block-system_architecture-end--->

# #
<!---Documatic-section-Codebase Structure-end--->

<!---Documatic-section-evostra.algorithms.evolution_strategy.worker_process-start--->
## [evostra.algorithms.evolution_strategy.worker_process](3-evostra_algorithms.md#evostra.algorithms.evolution_strategy.worker_process)

<!---Documatic-section-worker_process-start--->
<!---Documatic-block-evostra.algorithms.evolution_strategy.worker_process-start--->
<details>
	<summary><code>evostra.algorithms.evolution_strategy.worker_process</code> code snippet</summary>

```python
def worker_process(arg):
    (get_reward_func, weights) = arg
    return get_reward_func(weights)
```
</details>
<!---Documatic-block-evostra.algorithms.evolution_strategy.worker_process-end--->
<!---Documatic-section-worker_process-end--->

# #
<!---Documatic-section-evostra.algorithms.evolution_strategy.worker_process-end--->

[_Documentation generated by Documatic_](https://www.documatic.com)