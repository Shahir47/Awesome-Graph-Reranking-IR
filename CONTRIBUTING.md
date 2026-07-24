# Contribution Guidelines

Thanks for taking the time to improve this list. It accompanies our survey on graph-based re-ranking, so the goal is to keep it accurate, current, and genuinely useful to IR researchers rather than exhaustive for its own sake.

## Suggesting a Paper

- The paper must propose or evaluate a graph-based re-ranking method — i.e., it builds a graph over queries, documents, passages, or entities and uses it (via GNNs, PageRank-style propagation, graph traversal, etc.) to reorder retrieval results.
- Search the existing tables first; do not submit a paper that is already listed.
- Add the paper to the category that matches its primary application: Question Answering, General Information Retrieval, Retrieval-Augmented Generation, or Auxiliary and Specialized Tasks. If you're unsure which category fits, say so in your PR and we'll place it.
- Provide, at minimum: the model/method name (if any), the paper title, the publication venue, the year, a link to the paper, and a link to the official code repository if one exists.
- Prefer linking to the venue's official proceedings page (ACM DL, ACL Anthology, IEEE Xplore, Springer, etc.) over arXiv when both exist.
- New rows go at the bottom of their table, matching the existing column order: `Model | Paper | Venue | Date | Resources`.

## Pull Requests

- One paper (or one focused change) per pull request — this makes review fast and keeps history clean.
- In the PR description, briefly explain why the paper belongs in the collection (what graph structure it uses and how it's applied to re-ranking).
- Verify every link resolves before submitting.
- Keep formatting consistent with the surrounding rows (table syntax, markdown link style, venue abbreviations).
