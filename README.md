# ALPE Token (Alpencoin)

Dies ist der **offizielle Smart Contract** für den ALPE Token – inspiriert von der Alpenregion.

### 🔍 Details
- ✅ Standard: ERC-20 (mit `burn()` & `mint()`)
- 🔢 Initial Supply: 21.000.000 ALPE
- 🔐 Nur der Owner kann zusätzliche Token `mint()`en
- 🔥 Jeder Holder kann Token verbrennen (`burn()`)

### 🌐 Netzwerk
- **Netzwerk:** OP Sepolia Testnet
- **Contract-Adresse:** folgt nach Deployment

### ⚙️ Funktionen
- `mint(address to, uint256 amount)` → nur Owner
- `burn(uint256 amount)` → für jeden Holder
- `transfer(address to, uint256 amount)` → Standard-ERC20

---

### 🛠 Deployment
Wurde mit **Remix + MetaMask** durchgeführt. Besitzeradresse ist der Contract-Ersteller.
