## Hi, I'm Sara 

Software & QA engineer. I test whether AI systems are actually governed by their stated standards - behavior, training, mechanism. I learn by building, and I like checking that things actually work - including the checker.

### AI testing projects

| # | Project | About | Repo | Article | Post |
|---|---|---|---|---|---|
| 0 | LLM API Testing *(precursor)* | The model answers differently every call, so a test passes when 7 of 10 runs are right | [repo](https://github.com/sbezjak/llm-api-testing) | [dev.to](https://dev.to/sara_bezjak/a-qa-engineers-first-ai-testing-project-fastapi-local-llm-pytest-5b1c) | [LinkedIn](https://www.linkedin.com/posts/sara-bezjak_a-qa-engineers-first-ai-testing-project-share-7453403711353241600-Ghbg/) |
| 1 | LLM Eval Harness | An LLM judge passed a made-up Python flag, with the same score on all five reruns | [repo](https://github.com/sbezjak/llm-eval-harness) | [dev.to](https://dev.to/sara_bezjak/five-ways-to-test-an-llms-answer-and-what-each-one-misses-5k2) | [LinkedIn](https://www.linkedin.com/posts/sara-bezjak_five-ways-to-test-an-llms-answer-and-what-share-7462437884919226368-7tnD/) |
| 2 | RAG + Observability | Asked about a feature its documents didn't cover, the model made one up | [repo](https://github.com/sbezjak/llm-rag) | [dev.to](https://dev.to/sara_bezjak/search-bug-or-model-bug-testing-a-rag-system-to-tell-them-apart-2fa7) | [LinkedIn](https://www.linkedin.com/posts/sara-bezjak_search-bug-or-model-bug-testing-a-rag-system-share-7470045953647972352-YiOx/) |
| 3 | Red Team Test Suite | A scanner said 100% of attacks worked; when I read the replies, about 2% did | [repo](https://github.com/sbezjak/llm-red) | [dev.to](https://dev.to/sara_bezjak/the-hard-part-of-attacking-an-ai-isnt-breaking-it-its-telling-real-harm-from-fake-9ca) | [LinkedIn](https://www.linkedin.com/posts/sara-bezjak_the-hard-part-of-attacking-an-ai-isnt-breaking-share-7478745951218614272-okBk/) |
| 4 | Agent Testing | An agent answered confidently about a city it never read. Only its trace showed it | [repo](https://github.com/sbezjak/llm-agent) | [dev.to](https://dev.to/sara_bezjak/with-an-ai-agent-the-answer-is-the-last-place-the-bug-shows-up-4kgb) | [LinkedIn](https://www.linkedin.com/posts/sara-bezjak_with-an-ai-agent-the-answer-is-the-last-share-7483782228104237062-RaiK/) |
| 5 | Model Benchmarking | When the same two answers swapped order, the cheaper judge picked a different winner nearly half the time | [repo](https://github.com/sbezjak/llm-benchmark) | [dev.to](https://dev.to/sara_bezjak/a-benchmark-is-only-as-good-as-the-model-you-use-to-grade-it-4h01) | [LinkedIn](https://www.linkedin.com/posts/sara-bezjak_a-benchmark-is-only-as-good-as-the-model-activity-7496181344872513536-deUq/) |

Here's what building them taught me about working *with* the model: **[The model said it read the report. It didn't.](https://dev.to/sara_bezjak/the-model-said-it-read-the-report-it-didnt-12a6)**

### Fine-tuning

The projects above test models. Here I trained one myself, then tested if I could trust it.

| Project | About | Repo | Article | Post |
|---|---|---|---|---|
| Fine-Tuning (Content Moderation) | Accuracy rose, but more real threats got through | [repo](https://github.com/sbezjak/fine-tuning-cm) | [dev.to](https://dev.to/sara_bezjak/fine-tuning-a-content-moderation-model-on-a-laptop-is-easy-trusting-the-result-is-not-50fb) | [LinkedIn](https://www.linkedin.com/posts/sara-bezjak_fine-tuning-a-content-moderation-model-on-activity-7503372226734469120-RCpX) |

### Theory testing

Does a model's verdict actually follow its stated reasons? The first probe catches AI judges that say the outcome doesn't matter, then score it anyway. The second looks inside a small open model for where the outcome gets in, and takes most of it out.

| Project | About | Repo | Article | Post |
|---|---|---|---|---|
| Judge Outcome-Bias Probe | Every Claude model said the outcome shouldn't change the score, then scored the same decision lower when it went wrong | [repo](https://github.com/sbezjak/judge-outcome-bias-probe) | [dev.to](https://dev.to/sara_bezjak/your-ai-judge-might-be-grading-luck-not-decisions-c2p) | [LinkedIn](https://www.linkedin.com/posts/sara-bezjak_an-ai-coding-agent-upgrades-a-library-and-share-7516808895030427649-zRb2/) |
| Interpretability Grounds Testing | Taking one direction out where the outcome enters cut 70% of the extra blame, then worked once and flipped once on new stories | [repo](https://github.com/sbezjak/interpretability-grounds-testing) | [dev.to](https://dev.to/sara_bezjak/i-looked-inside-a-small-ai-model-to-find-where-luck-changes-its-answer-4d5g) | [LinkedIn](https://www.linkedin.com/posts/sara-bezjak_i-tried-interpretability-for-the-first-time-share-7523342698624274432-5yhe/) |
