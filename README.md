# ippogrifo-redirect

Reindirizza `associazioneippogrifo.com` (senza www) a `https://www.associazioneippogrifo.com`, mantenendo percorso e parametri.

Serve perché il DNS del dominio è su Webnode, che non consente record ALIAS verso CloudFront.
Il sito vero è su AWS (S3 + CloudFront). Qui ci sono solo due pagine statiche servite da GitHub Pages.

DNS (Webnode): i record A dell'apex puntano a 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153.
