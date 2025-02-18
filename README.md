To test:

0. [Install `uv`](https://docs.astral.sh/uv/getting-started/installation/)
1. Run:
    ```bash
    git clone https://github.com/multimeric/AriadneCodegenBug`
    uv run ariadne-codegen
    ```
2. Open `graphql_client/custom_queries.py`, and note the following signature:
```python
    def boards(cls, *, ids: Optional[str] = None) -> GraphQLField:
```
