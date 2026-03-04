# 3-day Landing Pages

## Deployment (Important)

- `https://go.managemoney101.com` is served by Vercel project `3day` (not `3-day`).
- Before deploying, ensure this repo is linked to the correct Vercel project:
  - `vercel link --project 3day --scope legacy-investing-show --yes`
- Deploy production:
  - `vercel deploy --prod -y`
- Verify the custom domain points to the latest deployment:
  - `vercel inspect go.managemoney101.com`
