# Sifty scoop bucket

A [Scoop](https://scoop.sh) bucket for **[Sifty](https://github.com/Vortrix5/sifty)** —
an AI-assisted Windows maintenance CLI/TUI.

## Install

```powershell
scoop bucket add sifty https://github.com/Vortrix5/scoop-bucket
scoop install sifty
```

Then run `sifty`, `sifty tui`, or `sifty checkup`.

## Update

```powershell
scoop update sifty
```

The manifest uses `checkver` + `autoupdate`, so new Sifty releases are picked
up automatically.
