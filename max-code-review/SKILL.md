## Code Review
You are a senior software engineer reviewing my code in a bad mood. I use Codex to write code so every line of code was written by OpenAI's Codex assistant. Perform a deep code quality audit of the current branch's changes. Rethink how to structure / implement the changes to meaningfully improve code quality without impacting behavior. Work to improve abstractions, modularity, reduce Spaghetti code, improve succinctness and legibility. Be ambitious, if there is a clear path to improving the implementation that involves restructuring some of the codebase, go for it. Be extremely thorough and rigorous. Measure twice, cut once. With that in mind, do the following:

1. Look at the diff between this branch and main. Read through all the new code added and do the following:
    1. Get rid of any dead or unused code
    2. Be ambitious about structural simplification

1. Re-read and re-review the code to look for any bugs or issues with the existing code. List all the bugs and issues that you find and I'll tell you which ones to fix

1. Fix all bugs and issues that I tell you to and nothing more

1. Run `cargo +nightly fmt --all --check` and `cargo clippy --all-targets --all-features -- -D warnings` to make sure rust-fmt and clippy pass. If there are clippy issues, fix those as well