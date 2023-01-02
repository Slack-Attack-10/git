## 1. SSH-Schlüssel generieren
`ssh-keygen -t ed25519 -C "your_email@example.com"`

## 2. Schlüssel sichtbar machen
`eval "$(ssh-agent -s)"`

`ssh-add ~/.ssh/id_ed25519`

## 3. Verbindung prüfen
`ssh -T git@github.com`
