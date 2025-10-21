# SMB commands

| Categorie   | Commando                                                                                                                    | Omschrijving                                               |   Voorbeeld |   Opmerkingen |
|:------------|:----------------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------|------------:|--------------:|
| SMB connect | smbclient -L \\192.168.143.227\ -U anonymous                                                                                | Connect anonymously via SMB                                |         nan |           nan |
| SMB connect | smbclient //10.10.11.174/support-tools -U anonymous --option='client min protocol=SMB2' --option='client max protocol=SMB3' | Interactive session with SMB with a min and a max protocol |         nan |           nan |
| nan         | smbclient -L //172.16.171.83 -N                                                                                             | Werkt op windows                                           |         nan |           nan |
