# Bitcoin Self-Custody Umbrel App Store

Community app store for [Umbrel](https://umbrel.com) with Bitcoin self-custody tools.

## Apps

### SimpleJadePinServer

Self-hosted blind PIN oracle for the [Blockstream Jade](https://blockstream.com/jade/) hardware wallet. Enables QR Pin Unlock for fully air-gapped wallet access.

This is a C# / Blazor Server port of [SimpleJadePinServer](https://github.com/Filiprogrammer/SimpleJadePinServer) by [Filiprogrammer](https://github.com/Filiprogrammer). All credit for the original design and protocol goes to the original author.

**Features:**
- QR Pin Unlock for air-gapped wallet access
- Oracle QR code generation for Jade pairing
- Web-based interface with camera QR scanning
- Works on both x86 and ARM (Raspberry Pi)

**Source:** [Bitcoin-Self-Custody/SimpleJadePinServer.Blazor](https://github.com/Bitcoin-Self-Custody/SimpleJadePinServer.Blazor)

## Installation

1. Open your Umbrel dashboard
2. Go to **App Store** (click the three dots in the top right corner)
3. Select **Community App Stores**
4. Add this repository URL:
   ```
   https://github.com/Bitcoin-Self-Custody/bitcoin-self-custody-umbrel-apps
   ```
5. The apps will appear in your App Store under "Bitcoin Self-Custody"

*Collaboration by Claude*
