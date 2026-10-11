# DeepBook Wallet Dashboard

Static dashboard for DeepBook wallet activity, collateral, and estimated fees.

## Deploy with Vercel and GitHub

1. Create a new GitHub repository.
2. Upload the complete contents of this folder:
   - `deepbook-wallet-dashboard.html`
   - `vercel.json`
   - `README.md`
3. In Vercel, choose **Add New → Project**, import that GitHub repository, and click **Deploy**.

No framework, build command, environment variables, or backend are required. The included `vercel.json` makes the dashboard available at the root URL (`/`).

## Notes

The dashboard reads directly from the public DeepBook Indexer in the visitor's browser. It stores no wallet credentials and makes no transactions.
