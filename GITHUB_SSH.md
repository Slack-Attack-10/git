## 1. SSH-Schlüssel generieren
`ssh-keygen -t ed25519 -C "your_email@example.com"`

## 2. Schlüssel sichtbar machen
`eval "$(ssh-agent -s)"`
