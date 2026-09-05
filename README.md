# EquiSettle 💸
> Web3 Finance, Web2 UX. Built for Sui Track 1: Payments & Stablecoins.

🌍 **Live Demo:** [EquiSettle Vercel Deployment](https://equisettle-d0o0bduav-brian0406-s-projects.vercel.app/)  
🎥 **Demo Video:** [Insert YouTube/Loom Link Here]  
📊 **Pitch Deck:** [Insert Pitch Deck Link Here]

---

## 👁️ The Vision

Couples, roommates, and travelers frequently share expenses, but settling those debts is a manual nightmare. Traditional banking relies on high FX fees for international groups, and centralized e-wallets have the power to arbitrarily freeze user funds without warning.

**EquiSettle is a mobile-first expense-sharing app that doesn't just *track* debt—it *erases* it instantly on-chain.** By leveraging the Sui blockchain, we offer an experience that feels completely frictionless (like Touch 'n Go or Venmo), while maintaining the security, speed, and self-custody of Web3.

## ✨ Key Features (Powered by Sui)

*   **Zero-Friction Onboarding (Sui zkLogin):** We eliminated seed phrases and browser extensions. Users authenticate with their existing Google OAuth credentials to securely generate a self-custodial wallet in 3 seconds.
*   **Smart Debt Simplification:** Tangled group debts (e.g., 10 different cross-payments) are mathematically compressed into the absolute minimum number of transfers (at most N-1).
*   **1-Tap Gasless Settlement (Sponsored PTBs):** When users click "Settle Up", we use Sui Programmable Transaction Blocks to batch all transfers. The user settles instantly in USDC while our relayer sponsors the network gas—meaning 100% zero crypto friction for the end-user.
*   **Trustless Escrow (Sui Move):** For high-trust payments like rental security deposits, we wrote a native `TimeLockedEscrow` Sui Move Smart Contract. Funds are locked immutably on-chain and rely on the decentralized Sui Clock for release, removing the need to trust landlords with cash.

## 🛠️ Tech Stack

*   **Frontend:** Next.js (App Router), React, Tailwind CSS, shadcn/ui.
*   **Blockchain Integration:** Sui Testnet, `@mysten/sui` (Modern SDK), `@mysten/dapp-kit`.
*   **Authentication:** Sui zkLogin.
*   **Smart Contracts:** Sui Move.

## 🚀 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/equisettle.git
   cd equisettle
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```

4. **View the app:**
   Open [http://localhost:3000](http://localhost:3000) in your browser.

## 👥 The Team

To build a consumer-ready product rapidly, our team utilized a strict divide-and-conquer strategy:

*   **Liew Lik Yi** – Lead Full-Stack & Web3 Developer 
    *(Architecture, Sui Move Contracts, zkLogin Integration, UI/UX Implementation)*
*   **Nguyen Tran Thao An** – Frontend & UI/UX Developer
    *(Responsive mobile UI (using Next.js/React and Tailwind CSS), zkLogin flow implemantation)*
*   **Ng Lai Ying** – Product Manager & Pitch Lead
    *(oversees project management, user flow design, and presentation preparation)*
*   **Chai Xin Yi** – Demo & Video Lead
    *(Testing and pre presentation preparation)*
