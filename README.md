# 🕵️ Cyber Forensics Investigator Desk

A immersive, interactive web-based digital forensics & incident investigation puzzle game. Step onto the oak desk of a lead cyber investigator, inspect classified Manila case folders, analyze digital artifacts, cross-reference server logs & transaction ledgers, and construct your evidence board to solve high-stakes corporate incidents.

---

## 🌟 Features

### 📁 1. Realistic Manila Case Folders
* **Physical Aesthetic**: Staggered cut tabs, coffee ring stains, metallic paperclips, red classified stamps, and brass fastener accents.
* **Dynamic Case Pipeline**: Supports multiple case files out of the box with procedural case dispatching once existing files are solved.
* **Selective Content Loading**: Dynamic game state rendering so only active case artifacts and ledgers are loaded into the workspace canvas.

### 🔍 2. Digital Artifact & Lightbox Ledger Inspection
* **Multi-Format Evidence**: Examine incident emails, wire transfer receipts, system authentication logs, and network architecture blueprints.
* **Metadata EXIF Inspector**: Uncover hidden SHA-256 hashes, server shards, process owner permissions, and IP headers.
* **Interactive Lightbox Table**: Filter transaction records, toggle UV/backlight mode, highlight anomalous rows, and pin critical evidence.

### 📌 3. Interactive Evidence Corkboard
* **Red-String Connections**: Connect related evidence pins with interactive red string lines.
* **Custom Notes & Tags**: Organize case leads, tag suspicious process IDs (PIDs), and track timeline markers.

### 📄 4. Document Analysis & OCR Tool
* **Keyword Search**: Scan logs and documents for critical numbers, cron schedules, or reboot triggers.
* **Entity Extraction**: Auto-detect extracted Process IDs, IP addresses, financial amounts, and timestamps.

### 🤖 5. Detective Companion & Investigator Notepad
* **100% Offline AI Assistant**: Local forensic rule engine providing progressive hints without requiring external API keys or cloud connections.
* **Case Notepad**: Keep structured investigation notes, track progress checklists, and calculate debrief scores.

---

## 🚀 Tech Stack

* **Frontend Framework**: React 18 + TypeScript
* **Build Tool**: Vite
* **State Management**: Zustand (with LocalStorage persistence)
* **Styling**: Tailwind CSS
* **Animations**: Motion (`motion/react`)
* **Icons**: Lucide React Icons

---

## 💻 Getting Started

### Prerequisites
* Node.js (v18 or higher recommended)
* npm or yarn

### Installation

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm run dev
   ```

4. Open `http://localhost:3000` in your browser.

---

## 🛠️ Build & Lint Scripts

* **Development mode**: `npm run dev`
* **Production Build**: `npm run build`
* **Type-Check / Linting**: `npm run lint`

---

## 🔒 Privacy & Local Execution

* **Zero External Dependencies**: Operates entirely client-side inside the browser sandbox.
* **No API Keys Required**: All case generation, OCR scanning, and detective assistant advice run locally with zero network calls.
