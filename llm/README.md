# LLM Zoomcap

Link: https://github.com/DataTalksClub/llm-zoomcamp

# Cohere Free Tier with 100requests/min

- Get Cohere AI key: https://cohere.com/blog/free-developer-tier-announcement
- LiteLLM docs: https://litellm.vercel.app/docs/providers/cohere

# Git prune untracked branches

https://stackoverflow.com/questions/7726949/remove-tracking-branches-no-longer-on-remote

`git fetch -p && for branch in $(git branch -vv | grep ': gone]' | awk '{print $1}'); do git branch -D $branch; done`

# Helpful links
- Ollama pull for docker: https://github.com/docker/genai-stack
