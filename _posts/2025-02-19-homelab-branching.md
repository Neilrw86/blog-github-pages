## Evolving My Git Branching Strategy

### The Early Days

In the early days of my homelab project, I relied on Git as a simple version control system. A `git pull` would suffice to update my servers, and any changes I made would be an afterthought. I didn't really consider branching or separating ops-based repos from dev-friendly ones.

![Git Branching Strategy](/assets/images/git_branch.jpeg)

### The Journey to Dev-First Development

As my repositories grew and management became more complex, I started to explore more advanced Git strategies. Here are the stages I've gone through:

#### Linting

Initially, I focused on linting as a way to catch errors early.

#### CI Testing on Git

Next, I set up Continuous Integration (CI) testing directly in my Git workflow.

#### Runners for Pulling and Executing

I introduced runners that would pull changes and execute tasks automatically.

#### Runners for Pulling and Executing with Tagging Commits

Later, I added the ability to tag commits as releases, which helped me plan for upcoming versions.

### The Evolution of Monthly Branches

One approach I've found useful is to use monthly feature branches. I'll create a new branch at the end of each month, keep my active work in that branch, and merge it occasionally with the runner jobs triggered only on merge to main. This allows me to:

- Review TODOs in the README file regularly
- Plan for what I want to accomplish in the next month
- Create a pin-pointed commit at the end of each month to mark the release

By adopting this strategy, I've found that feature branches tend to become less effective when my attention span is short-term. The monthly branch approach helps me stay organized and focused on delivering value.