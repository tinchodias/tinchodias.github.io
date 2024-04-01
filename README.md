This is my personal site. 

It is generated and deployed with [Ecstatic](https://guillep.github.io/ecstatic/).

# How to use

1. Install Ecstatic at `~/opt/ecstatic`.
2. Clone `source` branch.
3. Generate web content with `~/opt/ecstatic/ecstatic generate` (transform pillar files and templates into the website).
4. Test locally with `~/opt/ecstatic/ecstatic serve`.
5. Edit pillar files.
6. Re-generate and test (steps 3 and 4 in one line: `~/opt/ecstatic/ecstatic generate && ~/opt/ecstatic/ecstatic serve`).
7. Deploy with `~/opt/ecstatic/_scripts/publish-github-io.sh`.
