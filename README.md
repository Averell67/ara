# Base Chain Explorer (lite)

Tiny, no-build explorer for **Base Mainnet**:
- Latest block & gas price (RPC)
- Address balance (RPC)
- Last 10 transactions of an address (Blockscout API – no key)

## Run (static)
Open `index.html` locally, or host on GitHub Pages / Vercel / Netlify.  
No server required.

## Tech
- Ethers v6 (CDN)
- RPC: `https://mainnet.base.org`
- Tx list: `https://base.blockscout.com/api?module=account&action=txlist&...`

## Notes
- Read-only; no private keys used
- CORS is allowed by Blockscout API at the time of writing
- Feel free to submit PRs (pagination, ENS, CSV export, etc.)

## License
MIT

## Roadmap
- [ ] Pagination (Next/Prev 10 txs)
- [ ] CSV export
- [ ] Base Sepolia switch
Contributions are welcome!  
If you'd like to improve the template, fix a bug, or add a new example, follow these steps:

1. Fork this repository  
2. Create a new branch (`git checkout -b feature/my-improvement`)  
3. Commit your changes (`git commit -m 'Add my improvement'`)  
4. Push to your branch (`git push origin feature/my-improvement`)  
5. Open a Pull Request 🚀

We review all PRs as fast as possible!

---

## 💬 Support

If you encounter any issues or have questions about building your Farcaster MiniApp, feel free to:

- Open an issue on this repository  
- Reach out on Farcaster  
- Check the [official MiniApp documentation](https://miniapps.farcaster.xyz/) for guidance  

Built with ❤️ by the community.
