# LotPilot for Windows

[Download LotPilot Setup 1.2.1](https://github.com/AbdulNafeh10/lotpilot-downloads/releases/download/v1.2.1/LotPilot-Setup-1.2.1.exe)

[Latest release and downloads](https://github.com/AbdulNafeh10/lotpilot-downloads/releases/latest)

## Install on another computer

1. Use a Windows x64 computer with Google Chrome installed and access to the dealership printer network.
2. Download and run LotPilot Setup. Python and PDF/QR dependencies are included; Codex is not needed.
3. Printer setup opens. Select existing printer queues, or install the official Canon driver using the linked Canon download page and create LotPilot PT/BG queues with the printer address. Windows may ask for administrator approval.
4. In BOTH queues' Canon Driver preferences, select Multi-purpose Tray and Heavy 5. Set the physical Canon tray to Letter / Heavy 5. PT is landscape/color/one-sided; BG is portrait/black and white/duplex long-edge.
5. Choose Verify and save. It verifies queue, Letter size, tray and duplex/color capability. Heavy 5 must be confirmed in Canon preferences.
6. Generate a vehicle's PDFs and deliberately confirm a PT/BG print test. Confirm physical paper handling on each new computer.

The first installer is unsigned. It was tested on the development Windows PC, not yet on an independent clean second PC. Windows security or your IT policy may require publisher approval. Do not disable security controls.

The Impact font is used for the designed price-tag appearance; if absent the application uses a different font. Review the generated price tag before printing on a new system.

## Updates

Open **Updates** in LotPilot: **Check for updates > Download update > Restart & Install**. Downloads are checksum-verified. Updates cannot start while LotPilot is collecting, generating or printing. An offline update check does not prevent normal app use.

Each PC stores its own batches, PDF files and settings in `Documents/LotPilot`. No shared database and no automatic batch backups. Updates preserve settings and local data. The installer replaces application files only and creates a desktop shortcut.

Only release downloads and installation documentation are hosted here. No dealership batches, VIN input lists, saved documents, printer credentials or print history are uploaded.

## Report a problem

Use **Report a bug** in LotPilot. Describe the steps, expected result and error. Save a local report or choose **Open GitHub draft** to review and submit it yourself. GitHub issues are public; do not include customer details or credentials. No VINs, logs, files or printer addresses are attached automatically.

Printer setup has four steps: choose printer entries, set Windows preferences, load/configure the physical Canon tray, then verify and optionally print two labeled sample sheets. Verification does not claim the paper printed. Confirm the output yourself.
