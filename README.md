# Ultimate-Github-Actions
A collection of ultimate github actions to use in github

With GitHub Actions you can automate your workflow from idea to production.

---

## 📌 How to Contribute

1. **Fork & Star** ⭐ this repo  
2. **Add your Action** under the correct category  
3. **Follow the format**: `- [action-name](link) - Short, clear description.`  
4. **Submit a PR** — we review fast!

> **Pro Tip**: Use the [GitHub Actions Marketplace](https://github.com/marketplace?type=actions) to discover more.

---

## 🛠️ Core Categories (Add Your Actions Here!)

### Official Resources
- [Workflow Syntax](https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions) – Full reference
- [Events that Trigger Workflows](https://docs.github.com/en/actions/reference/events-that-trigger-workflows)
- [Contexts and Expressions](https://docs.github.com/en/actions/reference/context-and-expression-syntax-for-github-actions)

#### Workflow Examples
- [actions/hello-world-composite-action](https://github.com/actions/hello-world-composite-action)
- [actions/first-interaction](https://github.com/actions/first-interaction) – Auto-welcome new contributors

#### Official Actions
- [actions/checkout](https://github.com/actions/checkout) – Checkout repo
- [actions/upload-artifact](https://github.com/actions/upload-artifact) / [download-artifact](https://github.com/actions/download-artifact)
- [actions/setup-node](https://github.com/actions/setup-node), [setup-python](https://github.com/actions/setup-python), etc.

#### Create Your Actions
- [Creating a JavaScript Action](https://docs.github.com/en/actions/creating-actions/creating-a-javascript-action)
- [Docker Container Actions](https://docs.github.com/en/actions/creating-actions/creating-a-docker-container-action)
- [Composite Actions](https://docs.github.com/en/actions/creating-actions/creating-a-composite-action)

---

## 🌍 Community Resources

### GitHub Tools & Management
- [peter-evans/create-pull-request](https://github.com/peter-evans/create-pull-request) – Auto-create PRs
- [actions/stale](https://github.com/actions/stale) – Close inactive issues/PRs
- [release-drafter/release-drafter](https://github.com/release-drafter/release-drafter) – Auto-generate release notes

### Collection of Actions
- [sdras/awesome-actions](https://github.com/sdras/awesome-actions) – The original awesome list (legacy)
- [marketplace](https://github.com/marketplace?type=actions) – Official directory

---

### Utility
- [actions/cache](https://github.com/actions/cache) – Cache dependencies & build outputs
- [dawidd6/action-get-latest-release](https://github.com/dawidd6/action-get-latest-release) – Fetch latest GitHub release
- [jitterbit/get-changed-files](https://github.com/jitterbit/get-changed-files) – Get modified files in PR

### Static Analysis
- [super-linter/super-linter](https://github.com/super-linter/super-linter) – All-in-one linter
- [sonarqube-community/sonarqube-scan-action](https://github.com/sonarqube-community/sonarqube-scan-action)
- [eslint/eslint-action](https://github.com/eslint/eslint-action)

### Dynamic Analysis & Testing
- [cypress-io/github-action](https://github.com/cypress-io/github-action) – Run Cypress tests
- [playwright-community/playwright-github-action](https://github.com/playwright-community/playwright-github-action)
- [codecov/codecov-action](https://github.com/codecov/codecov-action) – Upload coverage

### Monitoring & Observability
- [mikepenz/action-junit-report](https://github.com/mikepenz/action-junit-report) – Display test results in PR
- [dorny/test-reporter](https://github.com/dorny/test-reporter) – Show test & lint results
- [snyk/actions](https://github.com/snyk/actions) – Security scanning

### Pull Requests
- [pull-request-size/pull-request-size](https://github.com/pull-request-size/pull-request-size) – Label PR by size
- [takanabe/github-actions-label-syncer](https://github.com/takanabe/github-actions-label-syncer)
- [kentaro-m/auto-assign](https://github.com/kentaro-m/auto-assign) – Auto-assign reviewers

### GitHub Pages
- [peaceiris/actions-gh-pages](https://github.com/peaceiris/actions-gh-pages) – Deploy to GitHub Pages
- [crazy-max/ghaction-github-pages](https://github.com/crazy-max/ghaction-github-pages)

### Notifications & Messages
- [slackapi/slack-github-action](https://github.com/slackapi/slack-github-action) – Send to Slack
- [jasonetco/create-an-issue](https://github.com/jasonetco/create-an-issue) – Create issues from templates
- [raineorshine/npm-download-count-action](https://github.com/raineorshine/npm-download-count-action)

### Deployment
- [appleboy/scp-action](https://github.com/appleboy/scp-action) – SCP files to server
- [GoogleCloudPlatform/github-actions](https://github.com/GoogleCloudPlatform/github-actions) – Deploy to GCP
- [Azure/webapps-deploy](https://github.com/Azure/webapps-deploy) – Deploy to Azure

#### Cloud Providers
| Platform | Action |
|--------|--------|
| AWS | [aws-actions/configure-aws-credentials](https://github.com/aws-actions/configure-aws-credentials) |
| GCP | [google-github-actions/deploy-cloudrun](https://github.com/google-github-actions/deploy-cloudrun) |
| Vercel | [amondnet/vercel-action](https://github.com/amondnet/vercel-action) |
| Netlify | [nwtgck/actions-netlify](https://github.com/nwtgck/actions-netlify) |

### External Services
- [firebase/firebase-action](https://github.com/w9jds/firebase-action)
- [stripe/stripe-action](https://github.com/stripe/stripe-action) – Trigger Stripe webhooks

### Frontend Tools
- [wentwrong/bundlewatch-action](https://github.com/wentwrong/bundlewatch-action) – Track bundle size
- [lighthouse-ci/action](https://github.com/treosh/lighthouse-ci-action) – Performance audits

### Machine Learning & MLOps
- [iterative/setup-cml](https://github.com/iterative/setup-cml) – CML for reports in PRs
- [pytorch/pytorch-github-actions](https://github.com/pytorch/pytorch-github-actions)
- [huggingface/hf-transfer-action](https://github.com/huggingface/hf-transfer-action) – Fast model upload

### Build & Packaging
- [docker/build-push-action](https://github.com/docker/build-push-action) – Build & push Docker images
- [crazy-max/ghaction-chocolatey](https://github.com/crazy-max/ghaction-chocolatey) – Windows packages
- [game-ci/unity-builder](https://github.com/game-ci/unity-builder)

### Database
- [tensorchord/setup-pgvecto.rs](https://github.com/tensorchord/setup-pgvecto.rs) – Vector DB
- [supabase/setup-cli](https://github.com/supabase/setup-cli) – Supabase CLI
- [mongodb/mongodb-github-action](https://github.com/mongodb/mongodb-github-action)

### Networking
- [cloudflare/wrangler-action](https://github.com/cloudflare/wrangler-action) – Deploy to Workers
- [ngrok/ngrok-github-action](https://github.com/ngrok/ngrok-github-action) – Expose local server

### Localization & i18n
- [wearerequired/lint-action](https://github.com/wearerequired/lint-action) – Lint translations
- [crowdin/github-action](https://github.com/crowdin/github-action) – Sync with Crowdin

### Fun & Creative
- [lowlighter/metrics](https://github.com/lowlighter/metrics) – Generate GitHub stats SVG
- [marocchino/sticky-pull-request-comment](https://github.com/marocchino/sticky-pull-request-comment)
- [wow-actions/welcome-bot](https://github.com/wow-actions/welcome-bot)

----

> We welcome your contributions!
Feel free to open a PR with new actions or resources — check out `CONTRIBUTING.md` (CONTRIBUTING.md) for guidelines.
