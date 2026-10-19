# Labels einrichten (einmalig)

Mit der GitHub-CLI (`gh`) im Repository-Ordner:

```bash
gh label create bug          --color d73a4a --description "Fehler / bug" --force
gh label create enhancement  --color a2eeef --description "Wunsch / feature request" --force
gh label create data         --color 0e8a16 --description "Spots, Referenzen, Länder / spots, references, countries" --force
gh label create "in progress" --color fbca04 --description "wird umgesetzt / being worked on" --force
gh label create "on dev"     --color c5def5 --description "auf dem Testsystem /dev / on the test system" --force
gh label create done         --color 5319e7 --description "live / released" --force
gh label create wontfix      --color ffffff --description "wird nicht umgesetzt / won't be done" --force
```

Oder im Browser unter *Issues → Labels → New label*.
